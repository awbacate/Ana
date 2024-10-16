<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Floricultura Wonderland Garden</title>
    <style>
        body {
            font-family: 'Cursive', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #e7b8b8;
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
            font-size: 2.5em; /* Ajuste para telas menores */
        }
        nav {
            background-color: #B0C4DE;
            padding: 1em;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 10px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.2em;
        }
        section {
            padding: 20px;
            margin: 20px auto;
            max-width: 90%; /* Mantém o conteúdo em 90% da tela */
            background-color: #fff;
            border-radius: 15px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }
        section h2 {
            font-family: 'Fantasy', serif;
            font-size: 2.2em;
            color: #B0C4DE;
        }
        section p {
            font-size: 1.2em;
            line-height: 1.6;
        }
        footer {
            background-color: #B0C4DE;
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
            background-position: center;
            height: 50vh; /* Ajuste baseado na altura da tela */
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
            font-size: 1.8em; /* Ajuste para dispositivos móveis */
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
            color: #B0C4DE;
        }

        /* Responsividade para telas pequenas (celulares) */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2em;
            }
            nav a {
                font-size: 1em;
                margin: 0 5px;
            }
            section h2 {
                font-size: 1.8em;
            }
            .flower {
                flex: 1 1 100%; /* As flores ocupam toda a largura em telas pequenas */
            }
            .banner h2 {
                font-size: 1.5em; /* Reduz tamanho do texto no banner em telas pequenas */
            }
        }

        /* Responsividade para telas muito pequenas (smartphones) */
        @media (max-width: 480px) {
            header h1 {
                font-size: 1.8em;
            }
            nav a {
                font-size: 0.9em;
                margin: 0 3px;
            }
            .banner {
                height: 40vh; /* Reduz altura do banner em smartphones */
            }
            .flowers {
                flex-direction: column; /* Exibe as flores em uma coluna */
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Floricultura Wonderland Garden</h1>
        <p>Uma floricultura inspirada em "Alice no País das Maravilhas", onde os clientes são transportados para um cenário mágico com flores raras, cores vibrantes e detalhes encantadores. A loja combina uma decoração surreal com elementos fantásticos, como relógios derretidos e xícaras transbordando flores, criando uma experiência única e mágica.</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#sobre">Sobre</a>
        <a href="#flores">Nossas Flores</a>
    </nav>

    <section class="banner">
        <h2>Descubra arranjos florais mágicos que desafiam a realidade!</h2>
    </section>

    <section id="sobre">
        <h2>Sobre Nós</h2>
        <p>Bem-vindo à Floricultura Wonderland Garden, onde as flores são mais do que belas — elas são encantadas! Inspirada no universo de Alice no País das Maravilhas, nossa loja traz arranjos florais únicos que combinam charme, cor e fantasia, tornando cada momento inesquecível.</p>
    </section>

    <section id="flores">
        <h2>Nossas Flores</h2>
        <div class="flowers">
            <div class="flower">
                <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEif1mU8zy72_DEaM9yNi6qw2Ygdmp32AwlpIBhJZi19UjZDfiriZ0oHMRxA3m2QygOXfVthou2We005HXg4VMIFFwGTCncQAcOYWKRzBl_Sv0oYj9tjCEOW4Dz8eFmEP5dL7tm5Gh_HjDM/s1600/540396_348637918529412_1654764275_n.jpg" alt="Rosa Encantada">
                <h3>Rosa Encantada</h3>
                <p>Uma rosa tão linda quanto as do jardim da Rainha de Copas.</p>
            </div>
            <div class="flower">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQlNYoh7I637mcPLwjVxLzkQETuHWbrnkMbDA&s" alt="Margarida Sonhadora">
                <h3>Margarida Sonhadora</h3>
                <p>Leve e alegre, como os sonhos mais doces de Alice.</p>
            </div>
            <div class="flower">
                <img src="https://cptstatic.s3.amazonaws.com/imagens/enviadas/materias/materia8034/producao-de-lirios-propagacao-plantio-adubacao-e-cultivo-cpt.jpg" alt="Lírio do Chapeleiro">
                <h3>Lírio do Chapeleiro</h3>
                <p>Flor exótica e cheia de personalidade, perfeita para quem adora aventuras.</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Floricultura Wonderland Garden - Inspirada no País das Maravilhas</p>
    </footer>
</body>
</html>

