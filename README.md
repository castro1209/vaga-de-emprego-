<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Supermercado Primavera</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #D32F2F; /* Vermelho */
            color: white;
            text-align: center;
            padding: 20px;
        }
        header h1 {
            margin: 0;
        }
        nav {
            background-color: #388E3C; /* Verde */
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .main-content {
            padding: 20px;
            text-align: center;
        }
        .vaga-annuncio {
            background-color: #FFEB3B;
            padding: 15px;
            margin: 20px 0;
            font-size: 18px;
            border-radius: 8px;
            color: #D32F2F;
            text-align: center;
        }
        .vaga-annuncio a {
            color: #388E3C;
            font-weight: bold;
            text-decoration: none;
        }
        .vaga-annuncio a:hover {
            text-decoration: underline;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        
    </style>
</head>
<body>
    <header>
        <h1>Supermercado Primavera</h1>
        <p>O melhor preço e qualidade para sua casa!</p>
    </header>

    <nav>
        <a href="#home">Início</a>
        <a href="#produtos">Produtos</a>
        <a href="#vagas">Vagas de Emprego</a>
        <a href="#contato">Contato</a>
    </nav>

    <div class="main-content">
        <section id="home">
            <h2>Bem-vindo ao Supermercado Primavera!</h2>
            <p>Venha conhecer nossas ofertas e promoções especiais.</p>
            
            <div class="images">
                <img src="https://via.placeholder.com/600x300?text=Supermercado+Primavera" alt="Imagem do supermercado">
                <img src="https://via.placeholder.com/600x300?text=Promoções" alt="Promoções">
            </div>
        </section>

        <section id="vagas">
            <h2>Anúncio de Vagas de Emprego</h2>
            <div class="vaga-annuncio">
                <p>Estamos contratando! Se você deseja fazer parte da nossa equipe, temos as seguintes vagas:</p>
                <ul>
                    <li>Caixa</li>
                    <li>Repositor</li>
                    <li>Serviços Gerais</li>
                </ul>
                <p>Entre em contato conosco através do WhatsApp para mais informações:</p>
                <a href="https://wa.me/5511999999999" target="_blank">Clique aqui para enviar uma mensagem no WhatsApp</a>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Supermercado Primavera. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
