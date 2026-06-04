colar o codigo meta <!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vijo Shop - Redirecionando...</title> <!-- Meta Pixel Code -->
    <script>
  fbq('track', 'ViewContent');
</script>
<script>
!function(f,b,e,v,n,t,s)
{if(f.fbq)return;n=f.fbq=function(){n.callMethod?
n.callMethod.apply(n,arguments):n.queue.push(arguments)};
if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
n.queue=[];t=b.createElement(e);t.async=!0;
t.src=v;s=b.getElementsByTagName(e)[0];
s.parentNode.insertBefore(t,s)}(window, document,'script',
'https://connect.facebook.net/en_US/fbevents.js');
fbq('init', '918341774492381');
fbq('track', 'PageView');
</script>
<noscript><img height="1" width="1" style="display:none"
src="https://www.facebook.com/tr?id=918341774492381&ev=PageView&noscript=1"
/></noscript>
<!-- End Meta Pixel Code --><style>
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

        /* BOTÃO DE REDIRECIONAMENTO DIRETO */
        .btn-shopee {
            display: inline-block;
            width: 100%;
            padding: 15px 20px;
            background-color: #EE4D2D; /* Laranja Oficial da Shopee */
            color: white;
            text-decoration: none;
            font-weight: bold;
            font-size: 1rem;
            border-radius: 10px;
            transition: transform 0.2s, background-color 0.2s;
            box-shadow: 0 4px 15px rgba(238, 77, 45, 0.3);
        }

        .btn-shopee:hover {
            background-color: #d73f21;
            transform: translateY(-2px);
        }

        .btn-shopee:active {
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
        <p>Aguarde alguns segundos enquanto abrimos a nossa vitrine oficial na Shopee...</p>

        <div class="loader-container">
            <div class="spinner"></div>
        </div>

        <a href="https://collshp.com/vitoloff146?view=storefront" id="shopee-link" class="btn-shopee">
            Ir para a Shopee agora
        </a>

        <div class="footer-text">
            Conexão segura garantida por Vijo Shop
        </div>
    </div>

    <script>
        // CONFIGURAÇÃO: Altere o link entre as aspas para o link da sua loja/vitrine
        const LINK_SHOPEE = "https://collshp.com/vitoloff146?view=storefront";
        
        // Tempo de espera em milissegundos (3000ms = 3 segundos)
        const TEMPO_ESPERA = 3000; 

        // Atualiza o link do botão dinamicamente caso mude na variável acima
        document.getElementById('shopee-link').href = LINK_SHOPEE;

        // Executa o redirecionamento automático após o tempo definido
        setTimeout(() => {
            window.location.href = LINK_SHOPEE;
        }, TEMPO_ESPERA);
    </script>

</body>
</html>
