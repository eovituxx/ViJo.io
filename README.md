<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vijo Shop - Verificação de Segurança</title>
    
    <link rel="icon" type="image/jpeg" href="m11.jpeg">
    
    <script>
        fbq('track', 'ViewContent');
    </script>
    
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

        /* FUNDO ANIMADO COM ONDAS DE CORES (VERDE E AMARELO) */
        body {
            background: linear-gradient(135deg, #39A935, #FFF159, #2b8228, #e5d64b);
            background-size: 400% 400%;
            animation: ondasDeCor 12s ease infinite;
            color: var(--texto-escuro);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
            overflow-x: hidden;
        }

        /* Animação que faz o degradê se mover como ondas fluídas */
        @keyframes ondasDeCor {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        /* CARD CENTRAL RESPONSIVO */
        .container {
            text-align: center;
            background: #ffffff;
            padding: 40px 30px;
            border-radius: 20px;
            max-width: 450px;
            width: 100%;
            position: relative;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.15);
            transition: all 0.3s ease;
        }

        /* Borda contornada animada do card */
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

        /* LOGO ADAPTÁVEL NO TOPO */
        .logo-box {
            margin-bottom: 25px;
        }

        .logo-box img {
            max-width: 100%;
            width: 180px;
            height: auto;
            object-fit: contain;
        }

        /* TEXTOS */
        h1 {
            font-size: 1.4rem;
            color: var(--azul-vijo);
            margin-bottom: 10px;
            line-height: 1.3;
        }

        p {
            font-size: 0.95rem;
            color: #666;
            margin-bottom: 30px;
            line-height: 1.4;
        }

        /* ÍCONE DE VERIFICAÇÃO */
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

        /* BOTÃO OTIMIZADO PARA CLIQUES */
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

        .footer-text {
            margin-top: 25px;
            font-size: 0.75rem;
            color: #aaa;
        }

        /* MEDIA QUERIES: AJUSTES EXCLUSIVOS PARA CELULARES PEQUENOS */
        @media (max-width: 400px) {
            body {
                padding: 10px;
            }
            .container {
                padding: 30px 20px;
            }
            h1 {
                font-size: 1.25rem;
            }
            p {
                font-size: 0.88rem;
                margin-bottom: 20px;
            }
            .btn-Meli {
                padding: 14px 15px;
                font-size: 0.95rem;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="logo-box">
            <img src="jpg" alt="ViJo Shop">
        </div>

        <h1>Link Seguro Verificado!</h1>
        <p>VEJA A OFERTA EXCLUSIVA NO BOTAO A BAIXO</p>

        <div class="success-box">
            <div class="checkmark-circle">
                <div class="checkmark draw"></div>
            </div>
        </div>

        <a href="https://meli.la/2acEwUf" id="Meli-link" class="btn-Meli">
            ACESSAR OFERTA NO MERCADO LIVRE
        </a>

        <div class="footer-text">
            Ambiente seguro certificado por Vijo Shop
        </div>
    </div>

    <script>
        // CONFIGURAÇÃO: Link oficial para onde o usuário será enviado ao clicar
        const LINK_MELI = "https://meli.la/2acEwUf";
        
        // Atualiza o link do botão dinamicamente na página
        document.getElementById('Meli-link').href = LINK_MELI;
    </script>

</body>
</html>
