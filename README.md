<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Investimento Imobiliário</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
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
    ul {
      padding-left: 20px;
    }
    .btn {
      display: inline-block;
      margin: 50px 20px;
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
    }
    .form-container {
      background-color: #1a1a1a;
      padding: 40px;
      border-radius: 10px;
      max-width: 500px;
      margin: 40px auto;
      text-align: center;
    }
    .form-container input {
      width: 80%;
      padding: 10px;
      margin: 10px 0;
      border: none;
      border-radius: 5px;
    }
    .form-container button {
      padding: 12px 25px;
      background-color: #ffffff;
      color: #000;
      font-weight: bold;
      border: none;
      border-radius: 25px;
      cursor: pointer;
      transition: 0.3s;
    }
    .form-container button:hover {
      background-color: #bbbbbb;
    }
    .icon-list li {
      margin-bottom: 15px;
      font-size: 1.1em;
    }
    .icon-list i {
      color: gold;
      margin-right: 10px;
    }
    blockquote {
      border-left: 4px solid gold;
      margin: 20px 0;
      padding-left: 20px;
      font-style: italic;
      color: #cccccc;
    }
    .faq-item {
      margin-bottom: 20px;
    }
    .faq-item h3 {
      margin-bottom: 5px;
      color: gold;
    }
  </style>
</head>
<body>
  <header>
    <h1 class="floating">Investimento Imobiliário: Construa seu Futuro</h1>
    <p>Descubra como investir em imóveis pode transformar sua vida financeira.</p>
  </header>

  <section class="form-container">
    <h2>Baixe o E-book Gratuito</h2>
    <p>Aprenda os primeiros passos para investir em imóveis com segurança e estratégia.</p>
    <form id="leadForm">
      <input type="text" id="nome" name="nome" placeholder="Seu Nome" required>
      <input type="email" id="email" name="email" placeholder="Seu E-mail" required>
      <button type="submit">Quero Receber</button>
    </form>
  </section>

  <section>
    <h2>Por que investir em imóveis?</h2>
    <p>Investir em imóveis é uma das formas mais seguras e inteligentes de proteger e multiplicar seu patrimônio.</p>
    <p>Imóveis tendem a valorizar com o tempo e podem gerar renda passiva através de aluguéis, além de serem um excelente escudo contra a inflação.</p>
  </section>

  <section>
    <h2>O que você vai encontrar no nosso E-book?</h2>
    <ul>
      <li>Como escolher o melhor imóvel para investir;</li>
      <li>Estratégias para lucrar com aluguel ou revenda;</li>
      <li>Como evitar armadilhas comuns no mercado imobiliário;</li>
      <li>Como iniciar mesmo com pouco dinheiro.</li>
    </ul>
    <a href="https://pay.kirvano.com/111dffa9-6610-420f-a9ee-5dc2a3dcbb31" class="btn floating">Comprar Agora</a>
    <a href="https://www.instagram.com/investimento_72828" class="btn floating" target="_blank">Nosso Instagram</a>
    <a href="mailto:valdemirbarbosa595@gmail.com" class="btn floating">Fale Conosco</a>
  </section>

  <section>
    <h2>Vantagens com o nosso método</h2>
    <ul class="icon-list">
      <li><i class="fas fa-chart-line"></i> Alta valorização dos imóveis</li>
      <li><i class="fas fa-hand-holding-usd"></i> Renda passiva com aluguel</li>
      <li><i class="fas fa-user-shield"></i> Segurança financeira</li>
      <li><i class="fas fa-lightbulb"></i> Estratégias práticas e atualizadas</li>
    </ul>
  </section>

  <section>
    <h2>Depoimentos de leitores</h2>
    <blockquote>
      <p>"Consegui investir com confiança mesmo sem muita experiência. O conteúdo é direto e prático!"</p>
      <cite>– Mariana Oliveira</cite>
    </blockquote>
    <blockquote>
      <p>"Já estou colhendo os frutos. Comecei com pouco e hoje tenho meu primeiro imóvel alugado."</p>
      <cite>– João Carlos</cite>
    </blockquote>
  </section>

  <section>
    <h2>Perguntas Frequentes</h2>
    <div class="faq-item">
      <h3>Preciso de muito dinheiro para começar?</h3>
      <p>Não! O e-book mostra estratégias para começar com pouco e evoluir com segurança.</p>
    </div>
    <div class="faq-item">
      <h3>O conteúdo é indicado para iniciantes?</h3>
      <p>Sim, foi pensado especialmente para quem está dando os primeiros passos.</p>
    </div>
    <div class="faq-item">
      <h3>Recebo o e-book na hora?</h3>
      <p>Sim, após preencher o formulário você será redirecionado automaticamente para o link de acesso.</p>
    </div>
  </section>

  <section>
    <h2>Últimas do Blog</h2>
    <ul>
      <li><strong>5 erros que todo iniciante comete no mercado imobiliário</strong></li>
      <li><strong>Como identificar uma boa oportunidade de investimento</strong></li>
      <li><strong>O que muda nos imóveis com a alta da Selic?</strong></li>
    </ul>
  </section>

  <section style="text-align:center;">
    <h2>Fale direto com a gente no WhatsApp</h2>
    <a class="btn floating" href="https://wa.me/5511930558981" target="_blank"><i class="fab fa-whatsapp"></i> WhatsApp</a>
  </section>

  <footer>
    <p>&copy; 2025 Investimento Imobiliário. Todos os direitos reservados.</p>
  </footer>

  <script>
    document.getElementById('leadForm').addEventListener('submit', function(e) {
      e.preventDefault();
      const nome = document.getElementById('nome').value;
      const email = document.getElementById('email').value;
      window.location.href = "obrigado.html?nome=" + encodeURIComponent(nome);
    });
  </script>
</body>
</html><