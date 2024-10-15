<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Floricultura Maravilhas</title>
    <style>
        body {
            font-family: 'Cursive', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0e8e8;
            color: #333;
        }
        header {
            background-color: #8f4ba0;
            color: #fff;
            text-align: center;
            padding: 2em;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
        }
        header h1 {
            font-family: 'Fantasy', serif;
            font-size: 3em;
        }
        nav {
            background-color: #b065c1;
            padding: 1em;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.2em;
        }
        section {
            padding: 20px;
            margin: 20px auto;
            max-width: 800px;
            background-color: #fff;
            border-radius: 15px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }
        section h2 {
            font-family: 'Fantasy', serif;
            font-size: 2.5em;
            color: #8f4ba0;
        }
        section p {
            font-size: 1.2em;
            line-height: 1.6;
        }
        footer {
            background-color: #8f4ba0;
            color: white;
            padding: 1em 0;
            text-align: center;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .banner {
            background-image: url('https://via.placeholder.com/1200x400?text=Floricultura+Maravilhas');
            background-size: cover;
            height: 400px;
            position: relative;
        }
        .banner h2 {
            position: absolute;
            bottom: 20px;
            left: 20px;
            color: white;
            background-color: rgba(0, 0, 0, 0.6);
            padding: 10px;
            border-radius: 10px;
            font-size: 2em;
        }
        .flowers {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .flower {
            flex: 1 1 30%;
            background-color: #f5f5f5;
            margin: 15px;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .flower img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 15px;
        }
        .flower h3 {
            font-size: 1.5em;
            color: #8f4ba0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Floricultura Maravilhas</h1>
        <p>Flores e Magia Inspiradas no País das Maravilhas</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#sobre">Sobre</a>
        <a href="#flores">Nossas Flores</a>
        <a href="#contato">Contato</a>
    </nav>

    <section class="banner">
        <h2>Descubra um Mundo de Encantos Florais</h2>
    </section>

    <section id="sobre">
        <h2>Sobre Nós</h2>
        <p>Bem-vindo à Floricultura Maravilhas, onde as flores são mais do que apenas lindas — elas são mágicas! Inspirada pelo mundo de Alice no País das Maravilhas, nossa floricultura traz para você arranjos florais cheios de charme, cor e fantasia. Deixe-se levar por esse universo e escolha a flor perfeita para tornar seus momentos inesquecíveis.</p>
    </section>

    <section id="flores">
        <h2>Nossas Flores</h2>
        <div class="flowers">
            <div class="flower">
                <img src="https://via.placeholder.com/300?text=Rosa+Encantada" alt="Rosa Encantada">
                <h3>Rosa Encantada</h3>
                <p>Uma rosa tão linda quanto as do jardim da Rainha de Copas.</p>
            </div>
            <div class="flower">
                <img src="https://via.placeholder.com/300?text=Margarida+Sonhadora" alt="Margarida Sonhadora">
                <h3>Margarida Sonhadora</h3>
                <p>Leve e alegre, como os sonhos mais doces de Alice.</p>
            </div>
            <div class="flower">
                <img src="https://via.placeholder.com/300?text=Lírio+do+Chapeleiro" alt="Lírio do Chapeleiro">
                <h3>Lírio do Chapeleiro</h3>
                <p>Flor exótica e cheia de personalidade, perfeita para quem adora aventuras.</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Floricultura Maravilhas - Inspirada no País das Maravilhas</p>
    </footer>
</body>
</html>
