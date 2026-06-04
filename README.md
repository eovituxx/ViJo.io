<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vijo Shop - Redirecionando...</title>
    
    <!-- Meta Pixel Code -->
    <script>
        fbq('track', 'ViewContent');
    </script>
    
    <!-- Google tag (gtag.js) -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=AW-17997715261"></script>
    <script>
      window.dataLayer = window.dataLayer || [];
      function gtag(){dataLayer.push(arguments);}
      gtag('js', new Date());

      gtag('config', 'AW-17997715261');
    </script>
    <script>
  gtag('event', 'conversion', {
      'send_to': 'AW-17997715261/hBCoCKqWkLkcEL2u_YVD',
      'value': 1.0,
      'currency': 'BRL',
      'transaction_id': ''
      // 'new_customer': true /* calculate dynamically, populate with true/false */,
  });
</script>
    <noscript><img height="1" width="1" style="display:none"
    src="https://www.facebook.com/tr?id=918341774492381&ev=PageView&noscript=1"
    /></noscript>
    <!-- End Meta Pixel Code -->

    <style>
        /* RESET E CONFIGURAÇÕES DE CORES BASEADAS NA SUA LOGO */
        :root {
            --verde-vijo: #39A935;
            --azul-vijo: #1A65B1;
            --fundo-claro: #F9FBF9;
            --texto-escuro: #2C3E50;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--fundo-claro);
            color: var(--texto-escuro);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        /* CARD CENTRAL */
        .container {
            text-align: center;
            background: #ffffff;
            padding: 40px 30px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.05);
            max-width: 450px;
            width: 100%;
            border-top: 5px solid var(--verde-vijo);
        }

        /* LOGO */
        .logo-box {
            margin-bottom: 25px;
        }

        .logo-box img {
            max-width: 180px;
            height: auto;
            object-fit: contain;
        }

        /* TEXTOS */
        h1 {
            font-size: 1.4rem;
            color: var(--azul-vijo);
            margin-bottom: 10px;
        }

        p {
            font-size: 0.95rem;
            color: #666;
            margin-bottom: 30px;
        }

        /* ANIMADOR / SPINNER DE CARREGAMENTO */
        .loader-container {
            display: flex;
            justify-content: center;
            align-items: center;
            margin-bottom: 35px;
        }

        .spinner {
            width: 50px;
            height: 50px;
            border: 5px solid #f3f3f3;
            border-top: 5px solid var(--verde-vijo);
            border-right: 5px solid var(--azul-vijo);
            border-radius: 50%;
            animation: spin 1s linear infinite;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        /* BOTÃO DE REDIRECIONAMENTO DIRETO (MERCADO LIVRE) */
        .btn-Meli {
            display: inline-block;
            width: 100%;
            padding: 15px 20px;
            background-color: #FFF159; /* Amarelo Oficial do Mercado Livre */
            color: #333333; /* Texto escuro para contraste */
            text-decoration: none;
            font-weight: bold;
            font-size: 1rem;
            border-radius: 10px;
            transition: transform 0.2s, background-color 0.2s;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
        }

        .btn-Meli:hover {
            background-color: #e6d950;
            transform: translateY(-2px);
        }

        .btn-Meli:active {
            transform: translateY(0);
        }

        /* FOOTER DA PÁGINA */
        .footer-text {
            margin-top: 25px;
            font-size: 0.75rem;
            color: #aaa;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="logo-box">
            <img src="m11.jpeg" alt="ViJo Shop">
        </div>

        <h1>Você está sendo redirecionado!</h1>
        <p>Aguarde alguns segundos enquanto abrimos a nossa vitrine oficial no Mercado Livre...</p>

        <div class="loader-container">
            <div class="spinner"></div>
        </div>

        <!-- Corrigido o erro de aspas e link duplicado na tag abaixo -->
        <a href="https://meli.la/2Jg4bmf" id="Meli-link" class="btn-Meli">
            Ir para o Mercado Livre agora
        </a>

        <div class="footer-text">
            Conexão segura garantida por Vijo Shop
        </div>
    </div>

    <script>
        // CONFIGURAÇÃO: Link oficial para onde o usuário será enviado
        const LINK_MELI = "https://meli.la/2Jg4bmf";
        
        // Tempo de espera em milissegundos (3000ms = 3 segundos) para o Google Ads processar o clique
        const TEMPO_ESPERA = 3000; 

        // Atualiza o link do botão dinamicamente na página
        document.getElementById('Meli-link').href = LINK_MELI;

        // Executa o redirecionamento automático após os 3 segundos
        setTimeout(() => {
            window.location.href = LINK_MELI;
        }, TEMPO_ESPERA);
    </script>

</body>
</html>
