<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Aprenda a investir em imóveis com segurança e estratégia. Baixe nosso e-book gratuito e comece a construir seu futuro financeiro.">
  <meta name="keywords" content="investimento imobiliário, imóveis, renda passiva, e-book gratuito">
  <meta name="robots" content="index, follow">
  <meta name="author" content="Investimento Imobiliário">
  
  <!-- Open Graph / Facebook -->
  <meta property="og:type" content="website">
  <meta property="og:title" content="Investimento Imobiliário: Construa seu Futuro">
  <meta property="og:description" content="Descubra como investir em imóveis pode transformar sua vida financeira. Baixe nosso e-book gratuito!">
  <meta property="og:image" content="https://example.com/images/investimento-imoveis-og.jpg">
  <meta property="og:url" content="https://example.com/investimento-imobiliario">
  
  <!-- Twitter -->
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="Investimento Imobiliário: Construa seu Futuro">
  <meta name="twitter:description" content="Descubra como investir em imóveis pode transformar sua vida financeira. Baixe nosso e-book gratuito!">
  <meta name="twitter:image" content="https://example.com/images/investimento-imoveis-og.jpg">
  
  <title>Investimento Imobiliário: Construa seu Futuro Financeiro</title>
  
  <!-- Favicon -->
  <link rel="icon" href="favicon.ico">
  <link rel="apple-touch-icon" sizes="180x180" href="apple-touch-icon.png">
  <link rel="manifest" href="site.webmanifest">
  
  <!-- Preload de fontes -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  
  <!-- Font Awesome otimizado (apenas ícones necessários) -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" integrity="sha512-Avb2QiuDEEvB4bZJYdft2mNjVShBftLdPG8FJ0V7irTLQ8Uo0qcPxh4Plq7G5tGm0rU+1SPhVotteLpBERet7yg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  
  <style>
    /* Variáveis CSS */
    :root {
      --color-background: #0a0a0a;
      --color-text: #ffffff;
      --color-text-secondary: #e0e0e0;
      --color-accent: #ffd700; /* Gold */
      --color-button: #ffffff;
      --color-button-hover: #bbbbbb;
      --color-form-bg: #1a1a1a;
      --color-footer: #111111;
      --color-footer-text: #cccccc;
      --font-primary: 'Roboto', -apple-system, BlinkMacSystemFont, 'Segoe UI', Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
      --transition-default: 0.3s ease;
      --border-radius-default: 8px;
      --border-radius-button: 50px;
      --spacing-sm: 10px;
      --spacing-md: 20px;
      --spacing-lg: 40px;
      --spacing-xl: 80px;
    }

    /* Reset e estilos base */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    
    body {
      margin: 0;
      font-family: var(--font-primary);
      background-color: var(--color-background);
      color: var(--color-text);
      overflow-x: hidden;
      line-height: 1.6;
      font-size: 16px;
    }
    
    /* Acessibilidade - Skip to content */
    .skip-to-content {
      position: absolute;
      left: -9999px;
      top: auto;
      width: 1px;
      height: 1px;
      overflow: hidden;
    }
    
    .skip-to-content:focus {
      position: fixed;
      top: 0;
      left: 0;
      width: auto;
      height: auto;
      padding: 15px;
      background: var(--color-accent);
      color: var(--color-background);
      font-weight: bold;
      z-index: 9999;
    }
    
    /* Layout e componentes */
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 var(--spacing-md);
    }
    
    header {
      text-align: center;
      padding: var(--spacing-xl) 0;
      background: linear-gradient(90deg, #000000 0%, #1a1a1a 100%);
      animation: slideIn 2s ease;
    }
    
    main {
      display: flex;
      flex-direction: column;
      gap: var(--spacing-xl);
    }
    
    section {
      padding: var(--spacing-xl) 0;
      animation: fadeIn 2s ease;
    }
    
    /* Tipografia */
    h1, h2, h3, h4, h5, h6 {
      margin-bottom: var(--spacing-md);
      line-height: 1.2;
    }
    
    h1 {
      font-size: 2.5rem;
      margin-bottom: var(--spacing-lg);
    }
    
    h2 {
      font-size: 2rem;
      color: var(--color-text);
    }
    
    h3 {
      font-size: 1.5rem;
      color: var(--color-accent);
    }
    
    p {
      font-size: 1.1rem;
      line-height: 1.6;
      margin-bottom: var(--spacing-md);
      color: var(--color-text-secondary);
    }
    
    ul {
      padding-left: var(--spacing-lg);
      margin-bottom: var(--spacing-md);
    }
    
    li {
      margin-bottom: var(--spacing-sm);
    }
    
    /* Botões e links */
    .btn {
      display: inline-block;
      margin: var(--spacing-md) var(--spacing-sm);
      padding: 15px 30px;
      background-color: var(--color-button);
      color: var(--color-background);
      text-decoration: none;
      font-weight: bold;
      border-radius: var(--border-radius-button);
      transition: var(--transition-default);
      border: none;
      cursor: pointer;
      text-align: center;
    }
    
    .btn:hover, .btn:focus {
      background-color: var(--color-button-hover);
      transform: translateY(-3px);
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }
    
    .btn:focus {
      outline: 3px solid var(--color-accent);
      outline-offset: 2px;
    }
    
    .btn-primary {
      background-color: var(--color-accent);
      color: #000000;
    }
    
    .btn-primary:hover, .btn-primary:focus {
      background-color: #e6c200;
    }
    
    .btn-group {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: var(--spacing-md);
      margin: var(--spacing-lg) 0;
    }
    
    /* Formulário */
    .form-container {
      background-color: var(--color-form-bg);
      padding: var(--spacing-lg);
      border-radius: var(--border-radius-default);
      max-width: 500px;
      margin: var(--spacing-lg) auto;
      text-align: center;
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
    }
    
    .form-container label {
      display: block;
      margin-bottom: var(--spacing-sm);
      font-size: 1rem;
      color: var(--color-text);
      text-align: left;
    }
    
    .form-container input {
      width: 100%;
      padding: 12px;
      margin-bottom: var(--spacing-md);
      border: 1px solid #333;
      border-radius: var(--border-radius-default);
      background-color: #222;
      color: var(--color-text);
      transition: var(--transition-default);
    }
    
    .form-container input:focus {
      border-color: var(--color-accent);
      outline: none;
      box-shadow: 0 0 0 2px rgba(255, 215, 0, 0.3);
    }
    
    .form-container button {
      padding: 12px 25px;
      width: 100%;
      margin-top: var(--spacing-md);
    }
    
    .form-message {
      margin-top: var(--spacing-md);
      padding: var(--spacing-sm);
      border-radius: var(--border-radius-default);
      display: none;
    }
    
    .form-message.success {
      background-color: rgba(0, 128, 0, 0.2);
      color: #00ff00;
      border: 1px solid #00ff00;
    }
    
    .form-message.error {
      background-color: rgba(255, 0, 0, 0.2);
      color: #ff6666;
      border: 1px solid #ff6666;
    }
    
    /* Listas com ícones */
    .icon-list {
      list-style: none;
      padding-left: 0;
    }
    
    .icon-list li {
      margin-bottom: var(--spacing-md);
      font-size: 1.1rem;
      display: flex;
      align-items: center;
    }
    
    .icon-list i {
      color: var(--color-accent);
      margin-right: var(--spacing-md);
      font-size: 1.2rem;
      width: 24px;
      text-align: center;
    }
    
    /* Citações */
    blockquote {
      border-left: 4px solid var(--color-accent);
      margin: var(--spacing-lg) 0;
      padding: var(--spacing-md) var(--spacing-lg);
      font-style: italic;
      color: var(--color-text-secondary);
      background-color: rgba(255, 215, 0, 0.05);
      border-radius: 0 var(--border-radius-default) var(--border-radius-default) 0;
    }
    
    blockquote p {
      margin-bottom: var(--spacing-sm);
    }
    
    blockquote cite {
      display: block;
      font-style: normal;
      font-weight: bold;
      margin-top: var(--spacing-sm);
      color: var(--color-text);
    }
    
    /* FAQ */
    .faq-container {
      margin: var(--spacing-lg) 0;
    }
    
    .faq-item {
      margin-bottom: var(--spacing-lg);
      border-bottom: 1px solid #333;
      padding-bottom: var(--spacing-md);
    }
    
    .faq-item:last-child {
      border-bottom: none;
    }
    
    .faq-item h3 {
      margin-bottom: var(--spacing-sm);
      color: var(--color-accent);
      font-size: 1.3rem;
    }
    
    /* Blog */
    .blog-list {
      list-style: none;
      padding: 0;
    }
    
    .blog-list li {
      margin-bottom: var(--spacing-md);
      padding: var(--spacing-md);
      background-color: rgba(255, 255, 255, 0.05);
      border-radius: var(--border-radius-default);
      transition: var(--transition-default);
    }
    
    .blog-list li:hover {
      background-color: rgba(255, 255, 255, 0.1);
      transform: translateX(5px);
    }
    
    /* Footer */
    footer {
      text-align: center;
      padding: var(--spacing-lg) var(--spacing-md);
      background-color: var(--color-footer);
      color: var(--color-footer-text);
      margin-top: var(--spacing-xl);
    }
    
    /* Animações */
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
    
    /* Loading spinner */
    .spinner {
      display: none;
      width: 24px;
      height: 24px;
      border: 3px solid rgba(255, 255, 255, 0.3);
      border-radius: 50%;
      border-top-color: var(--color-accent);
      animation: spin 1s ease-in-out infinite;
      margin: 0 auto;
    }
    
    @keyframes spin {
      to { transform: rotate(360deg); }
    }
    
    /* Responsividade */
    @media (max-width: 992px) {
      h1 {
        font-size: 2.2rem;
      }
      
      h2 {
        font-size: 1.8rem;
      }
      
      section {
        padding: var(--spacing-lg) 0;
      }
    }
    
    @media (max-width: 768px) {
      h1 {
        font-size: 2rem;
      }
      
      h2 {
        font-size: 1.6rem;
      }
      
      .btn-group {
        flex-direction: column;
        align-items: center;
      }
      
      .btn {
        width: 100%;
        max-width: 300px;
        margin: var(--spacing-sm) 0;
      }
    }
    
    @media (max-width: 576px) {
      h1 {
        font-size: 1.8rem;
      }
      
      section {
        padding: var(--spacing-md) 0;
      }
      
      .form-container {
        padding: var(--spacing-md);
      }
    }
    
    /* Preferências de usuário */
    @media (prefers-reduced-motion: reduce) {
      * {
        animation-duration: 0.01ms !important;
        animation-iteration-count: 1 !important;
        transition-duration: 0.01ms !important;
        scroll-behavior: auto !important;
      }
    }
    
    /* Modo escuro (já está em modo escuro por padrão) */
    @media (prefers-color-scheme: light) {
      :root {
        --color-background: #f5f5f5;
        --color-text: #333333;
        --color-text-secondary: #555555;
        --color-form-bg: #ffffff;
        --color-footer: #333333;
        --color-footer-text: #f0f0f0;
      }
      
      .form-container input {
        background-color: #ffffff;
        border-color: #dddddd;
        color: #333333;
      }
      
      .btn {
        background-color: #333333;
        color: #ffffff;
      }
      
      .btn:hover, .btn:focus {
        background-color: #555555;
      }
    }
  </style>
  
  <!-- Schema.org JSON-LD -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Product",
    "name": "E-book Investimento Imobiliário",
    "description": "Aprenda a investir em imóveis com segurança e estratégia. Baixe nosso e-book e comece a construir seu futuro financeiro.",
    "offers": {
      "@type": "Offer",
      "price": "0",
      "priceCurrency": "BRL",
      "availability": "https://schema.org/InStock"
    }
  }
  </script>
</head>
<body>
  <!-- Skip to content link para acessibilidade -->
  <a href="#main-content" class="skip-to-content">Pular para o conteúdo</a>

  <header>
    <div class="container">
      <h1 class="floating">Investimento Imobiliário: Construa seu Futuro</h1>
      <p>Descubra como investir em imóveis pode transformar sua vida financeira.</p>
    </div>
  </header>

  <main id="main-content">
    <section>
      <div class="container">
        <div class="form-container">
          <h2>Baixe o E-book Gratuito</h2>
          <p>Aprenda os primeiros passos para investir em imóveis com segurança e estratégia.</p>
          <noscript>
            <p style="color: #ff6666; text-align: center; padding: 10px; background-color: rgba(255, 0, 0, 0.1); border-radius: 5px; margin-bottom: 20px;">
              Por favor, habilite o JavaScript para enviar o formulário.
            </p>
          </noscript>
          <form id="leadForm">
            <label for="nome">Seu Nome</label>
            <input type="text" id="nome" name="nome" placeholder="Digite seu nome completo" required aria-required="true">
            
            <label for="email">Seu E-mail</label>
            <input type="email" id="email" name="email" placeholder="Digite seu melhor e-mail" required aria-required="true">
            
            <div class="form-message" id="formMessage"></div>
            
            <button type="submit" class="btn btn-primary">
              <span id="submitText">Quero Receber Gratuitamente</span>
              <span class="spinner" id="submitSpinner"></span>
            </button>
          </form>
        </div>
      </div>
    </section>

    <section>
      <div class="container">
        <h2>Por que investir em imóveis?</h2>
        <p>Investir em imóveis é uma das formas mais seguras e inteligentes de proteger e multiplicar seu patrimônio.</p>
        <p>Imóveis tendem a valorizar com o tempo e podem gerar renda passiva através de aluguéis, além de serem um excelente escudo contra a inflação.</p>
      </div>
    </section>

    <section>
      <div class="container">
        <h2>O que você vai encontrar no nosso E-book?</h2>
        <ul class="icon-list">
          <li><i class="fas fa-check-circle"></i> Como escolher o melhor imóvel para investir</li>
          <li><i class="fas fa-check-circle"></i> Estratégias para lucrar com aluguel ou revenda</li>
          <li><i class="fas fa-check-circle"></i> Como evitar armadilhas comuns no mercado imobiliário</li>
          <li><i class="fas fa-check-circle"></i> Como iniciar mesmo com pouco dinheiro</li>
        </ul>
        
        <div class="btn-group">
          <a href="https://pay.kirvano.com/111dffa9-6610-420f-a9ee-5dc2a3dcbb31" class="btn btn-primary" rel="noopener noreferrer">Adquirir E-book</a>
          <a href="https://www.instagram.com/investimento_72828" class="btn" target="_blank" rel="noopener noreferrer"><i class="fab fa-instagram"></i> Nosso Instagram</a>
          <a href="mailto:valdemirbarbosa595@gmail.com" class="btn" rel="noopener noreferrer"><i class="fas fa-envelope"></i> Fale Conosco</a>
        </div>
      </div>
    </section>

    <section>
      <div class="container">
        <h2>Vantagens com o nosso método</h2>
        <ul class="icon-list">
          <li><i class="fas fa-chart-line"></i> Alta valorização dos imóveis</li>
          <li><i class="fas fa-hand-holding-usd"></i> Renda passiva com aluguel</li>
          <li><i class="fas fa-user-shield"></i> Segurança financeira</li>
          <li><i class="fas fa-lightbulb"></i> Estratégias práticas e atualizadas</li>
        </ul>
      </div>
    </section>

    <section>
      <div class="container">
        <h2>Depoimentos de leitores</h2>
        <blockquote>
          <p>"Consegui investir com confiança mesmo sem muita experiência. O conteúdo é direto e prático!"</p>
          <cite>– Mariana Oliveira</cite>
        </blockquote>
        <blockquote>
          <p>"Já estou colhendo os frutos. Comecei com pouco e hoje tenho meu primeiro imóvel alugado."</p>
          <cite>– João Carlos</cite>
        </blockquote>
      </div>
    </section>

    <section>
      <div class="container">
        <h2>Perguntas Frequentes</h2>
        <div class="faq-container">
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
            <p>Sim, após a confirmação do pagamento você receberá o acesso imediato ao material.</p>
          </div>
          <div class="faq-item">
            <h3>Posso acessar em qualquer dispositivo?</h3>
            <p>Sim, o e-book está em formato PDF e pode ser acessado em computadores, tablets e smartphones.</p>
          </div>
        </div>
      </div>
    </section>

    <section>
      <div class="container">
        <h2>Últimas do Blog</h2>
        <ul class="blog-list">
          <li><strong>5 erros que todo iniciante comete no mercado imobiliário</strong></li>
          <li><strong>Como identificar uma boa oportunidade de investimento</strong></li>
          <li><strong>O que muda nos imóveis com a alta da Selic?</strong></li>
        </ul>
      </div>
    </section>

    <section>
      <div class="container" style="text-align:center;">
        <h2>Fale direto com a gente no WhatsApp</h2>
        <div style="text-align: center; margin: 20px 0;">
          <p style="margin-bottom: 10px; color: var(--color-text-secondary);">Nosso WhatsApp:</p>
          <div style="display: flex; align-items: center; justify-content: center; gap: 10px; flex-wrap: wrap;">
            <span id="whatsappNumber" style="background-color: #1a1a1a; padding: 10px 15px; border-radius: 8px; font-family: monospace; font-size: 1.1rem; color: var(--color-accent); border: 1px solid #333;">(11) 91253-4148</span>
            <button id="copyWhatsApp" class="btn" style="margin: 0; padding: 8px 15px; font-size: 0.9rem;" onclick="copyWhatsAppNumber()">
              <i class="fas fa-copy"></i> Copiar
            </button>
            <a class="btn" href="https://wa.me/5511912534148" target="_blank" rel="noopener noreferrer" style="margin: 0; padding: 8px 15px; font-size: 0.9rem;">
              <i class="fab fa-whatsapp"></i> Abrir WhatsApp
            </a>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">
      <p>&copy; <span id="currentYear"></span> Investimento Imobiliário. Todos os direitos reservados.</p>
      <p>Este site não constitui oferta de investimento. Consulte um especialista antes de tomar decisões financeiras.</p>
    </div>
  </footer>

  <script>
    // Atualiza o ano atual no footer
    document.getElementById('currentYear').textContent = new Date().getFullYear();
    
    // Função para copiar o número do WhatsApp
    function copyWhatsAppNumber() {
      const phoneNumber = '11912534148';
      const copyButton = document.getElementById('copyWhatsApp');
      const originalText = copyButton.innerHTML;
      
      // Tenta usar a API moderna do clipboard
      if (navigator.clipboard && window.isSecureContext) {
        navigator.clipboard.writeText(phoneNumber).then(function() {
          // Sucesso
          copyButton.innerHTML = '<i class="fas fa-check"></i> Copiado!';
          copyButton.style.backgroundColor = '#00ff00';
          copyButton.style.color = '#000000';
          
          setTimeout(function() {
            copyButton.innerHTML = originalText;
            copyButton.style.backgroundColor = '';
            copyButton.style.color = '';
          }, 2000);
        }).catch(function() {
          // Fallback se a API falhar
          fallbackCopyTextToClipboard(phoneNumber, copyButton, originalText);
        });
      } else {
        // Fallback para navegadores mais antigos
        fallbackCopyTextToClipboard(phoneNumber, copyButton, originalText);
      }
    }
    
    // Função fallback para copiar texto
    function fallbackCopyTextToClipboard(text, button, originalText) {
      const textArea = document.createElement("textarea");
      textArea.value = text;
      textArea.style.top = "0";
      textArea.style.left = "0";
      textArea.style.position = "fixed";
      textArea.style.opacity = "0";
      
      document.body.appendChild(textArea);
      textArea.focus();
      textArea.select();
      
      try {
        const successful = document.execCommand('copy');
        if (successful) {
          button.innerHTML = '<i class="fas fa-check"></i> Copiado!';
          button.style.backgroundColor = '#00ff00';
          button.style.color = '#000000';
        } else {
          button.innerHTML = '<i class="fas fa-times"></i> Erro';
          button.style.backgroundColor = '#ff0000';
          button.style.color = '#ffffff';
        }
      } catch (err) {
        button.innerHTML = '<i class="fas fa-times"></i> Erro';
        button.style.backgroundColor = '#ff0000';
        button.style.color = '#ffffff';
      }
      
      document.body.removeChild(textArea);
      
      setTimeout(function() {
        button.innerHTML = originalText;
        button.style.backgroundColor = '';
        button.style.color = '';
      }, 2000);
    }
    
    // Manipulação do formulário com feedback visual
    document.getElementById('leadForm').addEventListener('submit', function(e) {
      e.preventDefault();
      
      // Elementos do formulário
      const form = this;
      const submitBtn = form.querySelector('button[type="submit"]');
      const submitText = document.getElementById('submitText');
      const submitSpinner = document.getElementById('submitSpinner');
      const formMessage = document.getElementById('formMessage');
      
      // Validação
      const nome = document.getElementById('nome').value.trim();
      const email = document.getElementById('email').value.trim();
      const emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
      
      // Reset de mensagens anteriores
      formMessage.style.display = 'none';
      formMessage.className = 'form-message';
      
      // Validação de campos
      if (nome === '') {
        showMessage('Por favor, insira seu nome.', 'error');
        return;
      }
      
      if (!emailPattern.test(email)) {
        showMessage('Por favor, insira um e-mail válido.', 'error');
        return;
      }
      
      // Mostrar estado de loading
      submitText.style.display = 'none';
      submitSpinner.style.display = 'block';
      submitBtn.disabled = true;
      
      // Simulação de envio (em produção, substituir por chamada AJAX real)
      setTimeout(function() {
        // Verificar se a página de agradecimento existe
        const img = new Image();
        img.onload = function() {
          // A página existe, redirecionar
          window.location.href = "obrigado.html?nome=" + encodeURIComponent(nome) + "&email=" + encodeURIComponent(email);
        };
        
        img.onerror = function() {
          // A página não existe, mostrar mensagem de sucesso inline
          showMessage('Obrigado! Seu e-book foi enviado para ' + email, 'success');
          form.reset();
          submitText.style.display = 'block';
          submitSpinner.style.display = 'none';
          submitBtn.disabled = false;
        };
        
        // Tentar carregar a página de agradecimento
        img.src = 'obrigado.html';
      }, 1500);
      
      // Função para mostrar mensagens
      function showMessage(text, type) {
        formMessage.textContent = text;
        formMessage.className = 'form-message ' + type;
        formMessage.style.display = 'block';
        
        if (type === 'error') {
          submitText.style.display = 'block';
          submitSpinner.style.display = 'none';
          submitBtn.disabled = false;
        }
      }
    });
  </script>
</body>
</html>