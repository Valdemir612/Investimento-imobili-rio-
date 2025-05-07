<!DOCTYPE html><html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Investimento Imobiliário</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            background-color: #0a0a0a;
            color: #ffffff;
            overflow-x: hidden;
        }
        header {
            text-align: center;
            padding: 100px 100px;
            background: linear-gradient(90deg, #000000 0%, #1a1a1a 100%);
            animation: slideIn 2s ease;
        }
        h1 {
            font-size: 3em;
        }
        p {
            font-size: 1.2em;
            line-height: 1.6;
            margin: 20px 0;
        }
        section {
            padding: 80px 100px;
            max-width: 1200px;
            margin: auto;
            animation: fadeIn 2s ease;
        }
        .btn {
            display: inline-block;
            margin:  50px 20px;
            padding: 15px 30px;
            background-color: #ffffff;
            color: #000000;
            text-decoration: none;
            font-weight: bold;
            border-radius: 50px;
            transition: 0.3s;
        }
        .btn:hover {
            background-color: #bbbbbb;
        }
        footer {
            text-align: center;
            padding: 30px 20px;
            background-color: #111111;
            color: #aaaaaa;
            font-size: 0.9em;
        }
        @keyframes slideIn {
            from { transform: translateY(-50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        .floating {
            animation: floating 4s infinite ease-in-out;
        }
        @keyframes floating {
            0% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0); }
        }/* Chatbot */
    #chatbot {
        position: fixed;
        bottom: 20px;
        right: 20px;
        width: 300px;
        max-height: 400px;
        background: #111;
        border: 1px solid #555;
        border-radius: 10px;
        overflow: hidden;
        display: none;
        flex-direction: column;
        box-shadow: 0 0 10px #333;
    }
    #chatbot-header {
        background: #222;
        padding: 10px;
        text-align: center;
        font-weight: bold;
        color: #fff;
        cursor: pointer;
    }
    #chatbot-messages {
        flex: 1;
        padding: 10px;
        overflow-y: auto;
        font-size: 0.9em;
    }
    #chatbot-input {
        display: flex;
        border-top: 1px solid #555;
    }
    #chatbot-input input {
        flex: 1;
        padding: 10px;
        border: none;
        background: #222;
        color: #fff;
    }
    #chatbot-input button {
        padding: 10px;
        background: #444;
        border: none;
        color: #fff;
        cursor: pointer;
    }
    #chatbot-toggle {
        position: fixed;
        bottom: 20px;
        right: 20px;
        background: #ffffff;
        color: #000000;
        border-radius: 50%;
        width: 60px;
        height: 60px;
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 2em;
        cursor: pointer;
        z-index: 1000;
    }
</style>

</head>
<body><header>
    <h1 class="floating">Investimento Imobiliário: Construa seu Futuro</h1>
    <p>Descubra como investir em imóveis pode transformar sua vida financeira.</p>
</header><section>
    <h2>Por que investir em imóveis?</h2>
    <p>Investir em imóveis é uma das formas mais seguras e inteligentes de proteger e multiplicar seu patrimônio. Imóveis tendem a valorizar com o tempo e podem gerar renda passiva através de aluguéis, além de serem um excelente escudo contra a inflação.</p>
    <p>Se você está começando agora, não se preocupe. Com as informações certas, qualquer pessoa pode dar os primeiros passos e fazer investimentos de forma inteligente e segura.</p>
</section><section>
    <h2>O que você vai encontrar no nosso E-book?</h2>
    <p>Nosso e-book foi pensado para quem quer iniciar ou melhorar seus investimentos imobiliários. De uma maneira simples e direta, você vai aprender:</p>
    <ul>
        <li>Como escolher o melhor imóvel para investir;</li>
        <li>Estratégias para lucrar com aluguel ou revenda;</li>
        <li>Como evitar armadilhas comuns no mercado imobiliário;</li>
        <li>Como iniciar mesmo com pouco dinheiro.</li>
    </ul>
    <p>É como se um amigo que já passou por tudo isso estivesse te passando todas as dicas.</p><a href="https://pay.kirvano.com/111dffa9-6610-420f-a9ee-5dc2a3dcbb31" class="btn floating">Comprar Agora</a>
<a href="https://www.instagram.com/investimento_72828" class="btn floating" target="_blank">Nosso Instagram</a>
<a href="mailto:valdemirbarbosa595@gmail.com" class="btn floating">Fale Conosco</a>

</section><footer>
    <p>&copy; 2025 Investimento Imobiliário. Todos os direitos reservados.</p>
</footer><div id="chatbot">
    <div id="chatbot-header">Assistente</div>
    <div id="chatbot-messages">
        <div><strong>Bot:</strong> Olá! Em que posso te ajudar hoje?</div>
    </div>
    <div id="chatbot-input">
        <input type="text" id="userInput" placeholder="Digite sua mensagem...">
        <button onclick="sendMessage()">Enviar</button>
    </div>
</div>
<div id="chatbot-toggle" onclick="toggleChatbot()">?</div><script>
    function toggleChatbot() {
        const bot = document.getElementById('chatbot');
        if (bot.style.display === 'flex') {
            bot.style.display = 'none';
        } else {
            bot.style.display = 'flex';
        }
    }

    function sendMessage() {
        const input = document.getElementById('userInput');
        const message = input.value.trim();
        if (message) {
            const messages = document.getElementById('chatbot-messages');
            messages.innerHTML += `<div><strong>Você:</strong> ${message}</div>`;
            messages.innerHTML += `<div><strong>Bot:</strong> Obrigado pela sua mensagem! Em breve responderemos.</div>`;
            input.value = '';
            messages.scrollTop = messages.scrollHeight;
        }
    }
</script></body>
</html>
