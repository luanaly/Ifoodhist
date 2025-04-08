# <!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>iFood - Seu Delivery Favorito</title>
    <style>
        /* Estilos Gerais */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            overflow-x: hidden; /* Evita rolagem horizontal */
        }
        header {
            background-color: #ff2e2e;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        main {
            padding: 20px;
            text-align: center;
        }
        /* Galeria de Imagens */
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
            margin-top: 20px;
        }
        .gallery img {
            width: 300px;
            height: auto;
            border-radius: 10px;
            transition: transform 0.3s ease-in-out;
        }
        .gallery img:hover {
            transform: scale(1.1);
        }
        /* Animação de Fade-in */
        .fade-in {
            opacity: 0;
            animation: fadeInAnimation 1.5s ease-in forwards;
        }
        @keyframes fadeInAnimation {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
        /* Rodapé */
        footer {
            background-color: #ff2e2e;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://logospng.org/download/ifood/logo-ifood-4096.png" alt="Logo iFood" width="150">
        <h1>Bem-vindo ao iFood</h1>
    </header>
    <main>
        <p class="fade-in">Os melhores restaurantes e pratos na palma da sua mão.</p>
        <div class="gallery">
            <img src="https://www.pexels.com/photo/assorted-indian-food-2684099/" alt="Prato Indiano" class="fade-in">
            <img src="https://www.pexels.com/photo/pizza-on-brown-wooden-table-825661/" alt="Pizza Italiana" class="fade-in">
            <img src="https://www.pexels.com/photo/burger-and-fries-70497/" alt="Hambúrguer e Batatas Fritas" class="fade-in">
            <img src="https://www.pexels.com/photo/sushi-on-plate-357756/" alt="Sushi Japonês" class="fade-in">
        </div>
    </main>
    <footer>
        <p>&copy; 2025 iFood. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
