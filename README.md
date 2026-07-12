<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meus Achadinhos & Promoções</title>
    <style>
        /* Reset e Estilos Globais */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        /* Container Principal */
        .container {
            width: 100%;
            max-width: 480px;
            text-align: center;
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(10px);
            padding: 40px 20px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        /* Perfil */
        .profile-img {
            width: 96px;
            height: 96px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid #ff4757;
            margin-bottom: 15px;
        }

        .profile-name {
            font-size: 1.4rem;
            font-weight: 700;
            margin-bottom: 5px;
            color: #2f3542;
        }

        .profile-bio {
            font-size: 0.95rem;
            color: #57606f;
            margin-bottom: 30px;
            line-height: 1.4;
        }

        /* Links/Botões */
        .links-container {
            display: flex;
            flex-direction: column;
            gap: 16px;
        }

        .link-card {
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: #ffffff;
            color: #2f3542;
            text-decoration: none;
            padding: 16px 20px;
            border-radius: 12px;
            font-size: 1.05rem;
            font-weight: 600;
            border: 2px solid #e4e7eb;
            transition: all 0.25s ease;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.02);
        }

        /* Efeito de passar o mouse/clicar */
        .link-card:hover {
            background-color: #ff4757;
            color: #ffffff;
            border-color: #ff4757;
            transform: translateY(-2px);
            box-shadow: 0 6px 12px rgba(255, 71, 87, 0.3);
        }

        /* Destaque para o melhor produto ou promoção do dia */
        .link-card.featured {
            background-color: #2ed573;
            color: white;
            border-color: #2ed573;
            animation: pulse 2s infinite;
        }

        .link-card.featured:hover {
            background-color: #26af5f;
            border-color: #26af5f;
        }

        /* Rodapé */
        .footer {
            margin-top: 40px;
            font-size: 0.8rem;
            color: #a4b0be;
        }

        /* Animação do botão em destaque */
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.02); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Foto de Perfil (Substitua a URL pela sua imagem) -->
        <img src="https://via.placeholder.com/150" alt="Logo do Perfil" class="profile-img">

        <!-- Informações do Perfil -->
        <h1 class="profile-name">Achados e Promoções</h1>
        <p class="profile-bio">🔥 Os melhores produtos com descontos exclusivos todos os dias! Clique nos links abaixo para conferir:</p>

        <!-- Lista de Links -->
        <div class="links-container">
            
            <!-- Link em Destaque (Promoção Principal) -->
            <a href="SEU_LINK_AQUI" target="_blank" class="link-card featured">
                ⭐ PROMOÇÃO DO DIA: Menor Preço!
            </a>

            <!-- Links Normais -->
            <a href="SEU_LINK_AQUI" target="_blank" class="link-card">
                🛍️ Minha Loja Completa na Shopee
            </a>

            <a href="SEU_LINK_AQUI" target="_blank" class="link-card">
                📦 Top Achadinhos da Semana
            </a>

            <a href="SEU_LINK_AQUI" target="_blank" class="link-card">
                📱 Grupo de Ofertas no WhatsApp / Telegram
            </a>

            <a href="SEU_LINK_AQUI" target="_blank" class="link-card">
                🔥 Descontos de até 70% em Eletrônicos
            </a>

        </div>

        <!-- Rodapé opcional -->
        <div class="footer">
            &copy; 2026 Todos os direitos reservados.
        </div>
    </div>

</body>
</html>
