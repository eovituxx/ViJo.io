<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vijo Shop - Verificação de Segurança</title>
    
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
    
    <!-- Google Ads Conversion Code -->
    <script>
      gtag('event', 'conversion', {
          'send_to': 'AW-17997715261/hBCoCKqWkLkcEL2u_YVD',
          'value': 1.0,
          'currency': 'BRL',
          'transaction_id': ''
      });
    </script>
    
    <noscript><img height="1" width="1" style="display:none"
    src="https://www.facebook.com/tr?id=918341774492381&ev=PageView&noscript=1"
    /></noscript>
    
    <style>
        /* CONFIGURAÇÃO DE CORES */
        :root {
            --verde-vijo: #39A935;
            --azul-vijo: #1A65B1;
            --amarelo-meli: #FFF159;
            --texto-escuro: #2C3E50;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        /* FUNDO COM UTENSÍLIOS DE COMPRA EM VERDE E AMARELO */
        body {
            background-color: #FAFAFA;
            /* Ícones SVG embutidos direto no CSS para criar o padrão de compras */
            background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='120' height='120' viewBox='0 0 120 120'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg opacity='0.12'%3E%3Cpath d='M20 20h10l5 15h20l5-15h10M25 35l3 15h24l3-15' stroke='%2339A935' stroke-width='2' stroke-linecap='round' stroke-linejoin='round'/%3E%3Crect x='80' y='15' width='20' height='16' rx='2' stroke='%23FFF159' stroke-width='2'/%3E%3Cpath d='M85 15v-3a3 3 0 0 1 6 0v3' stroke='%23FFF159' stroke-width='2'/%3E%3Ccircle cx='20' cy='85' r='8' stroke='%23FFF159' stroke-width='2'/%3E%3Cpath d='M40 85h40' stroke='%2339A935' stroke-width='2' stroke-linecap='round'/%3E%3Cpath d='M90 80l5 5-5 5' stroke='%2339A935' stroke-width='2' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
            color: var(--texto-escuro);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        /* CARD CENTRAL BRANCO COM BORDA CONTORNADA MULTICOLORIDA */
        .container {
            text-align: center;
            background: #ffffff;
            padding: 40px 30px;
            border-radius: 20px;
            max-width: 450px;
            width: 100%;
            position: relative;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.08);
        }

        /* Efeito de contorno variado/degradê em volta do card branco */
        .container::before {
            content: '';
            position: absolute;
            top: -4px;
            left: -4px;
            right: -4px;
            bottom: -4px;
            background: linear-gradient(45deg, var(--verde-vijo), var(--azul-vijo), var(--amarelo-meli), var(--verde-vijo));
            background-size: 400% 400%;
            z-index: -1;
            border-radius: 24px;
            animation: gradientBorder 8s ease infinite;
        }

        @keyframes gradientBorder {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
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

        /* ÍCONE DE VERIFICAÇÃO CONCLUÍDA */
        .success-box {
            display: flex;
            justify-content: center;
            align-items: center;
            margin-bottom: 30px;
        }

        .checkmark-circle {
            width: 60px;
            height: 60px;
            position: relative;
            display: inline-block;
            vertical-align: top;
            border-radius: 50%;
            border: 4px solid var(--verde-vijo);
            background-color: #fff;
        }

        .checkmark {
            border-radius: 5px;
        }

        .checkmark.draw:after {
            animation-duration: 800ms;
            animation-timing-function: ease;
            animation-name: checkmark;
            transform: scaleX(-1) rotate(135deg);
        }

        .checkmark:after {
            opacity: 1;
            height: 30px;
            width: 15px;
            transform-origin: left top;
            border-right: 4px solid var(--verde-vijo);
            border-top: 4px solid var(--verde-vijo);
            content: '';
            left: 12px;
            top: 26px;
            position: absolute;
        }

        @keyframes checkmark {
            0% { height: 0; width: 0; opacity: 1; }
            20% { height: 0; width: 15px; opacity: 1; }
            40% { height: 30px; width: 15px; opacity: 1; }
            100% { height: 30px; width: 15px; opacity: 1; }
        }

        /* BOTÃO DE REDIRECIONAMENTO COMPATÍVEL COM GOOGLE ADS */
        .btn-Meli {
            display: inline-block;
            width: 100%;
            padding: 16px 20px;
            background-color: var(--amarelo-meli);
            color: #333333;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.05rem;
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

        <h1>Link Seguro Verificado!</h1>
        <p>Clique no botão abaixo para acessar a oferta do Galaxy S25 Ultra em nossa vitrine oficial.</p>

        <div class="success-box">
            <div class="checkmark-circle">
                <div class="checkmark draw"></div>
            </div>
        </div>

        <a href="https://meli.la/2Jg4bmf" id="Meli-link" class="btn-Meli">
            ACESSAR OFERTA NO MERCADO LIVRE
        </a>

        <div class="footer-text">
            Ambiente seguro certificado por Vijo Shop
        </div>
    </div>

    <script>
        // CONFIGURAÇÃO: Link oficial para onde o usuário será enviado ao clicar
        const LINK_MELI = "https://meli.la/2Jg4bmf";
        
        // Atualiza o link do botão dinamicamente na página
        document.getElementById('Meli-link').href = LINK_MELI;
    </script>

</body>
</html>
