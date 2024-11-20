<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site de Filmes - Winx Club</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        /* Barra de Navegação */
        nav {
            background-color: #333;
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            z-index: 1000;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 10px 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 1.2em;
            padding: 10px 15px;
            display: block;
            border-radius: 5px;
        }

        nav ul li a:hover {
            background-color: #575757;
        }

        /* Estilos do corpo */
        body {
            margin-top: 60px; /* Deixa espaço para a barra de navegação fixa */
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }

        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin: 20px;
        }

        .movie {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin: 10px;
            width: 250px;
            overflow: hidden;
            transition: transform 0.3s;
        }

        .movie:hover {
            transform: scale(1.05);
        }

        .movie img {
            width: 100%;
            height: auto;
        }

        .movie-info {
            padding: 10px;
        }

        .movie-title {
            font-size: 1.2em;
            font-weight: bold;
        }

        .movie-description {
            font-size: 0.9em;
            color: #666;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        .video-container {
            text-align: center;
            margin-top: 30px;
        }

        iframe {
            width: 100%;
            max-width: 800px;
            height: 450px;
            border: none;
        }

    </style>
</head>
<body>

    <!-- Barra de Navegação -->
    <nav>
        <ul>
            <li><a href="#filmes">Filmes</a></li>
            <li><a href="#videos">Vídeos</a></li>
            <li><a href="#sobre">Sobre</a></li>
        </ul>
    </nav>

    <header>
        <h1>Bem-vindo ao Site de Filmes - Winx Club!</h1>
        <p>Assista aos filmes e vídeos incríveis do Winx Club e acompanhe suas aventuras mágicas!</p>
    </header>

    <!-- Seção de Filmes -->
    <div id="filmes" class="container">
        <div class="movie">
            <img src="https://via.placeholder.com/250x375" alt="Filme Winx">
            <div class="movie-info">
                <div class="movie-title">Winx Club: O Filme</div>
                <div class="movie-description">Aventura mágica das fadas Winx em um filme cheio de emoção e magia!</div>
            </div>
        </div>

        <div class="movie">
            <img src="https://via.placeholder.com/250x375" alt="Filme Winx 2">
            <div class="movie-info">
                <div class="movie-title">Winx Club: A Mágica das Fadas</div>
                <div class="movie-description">Mais uma aventura das fadas Winx, com magia e ação. Um filme cheio de emoção!</div>
            </div>
        </div>

        <div class="movie">
            <img src="https://via.placeholder.com/250x375" alt="Filme Winx 3">
            <div class="movie-info">
                <div class="movie-title">Winx Club: O Mistério das Sombras</div>
                <div class="movie-description">As Winx enfrentam o mistério de uma nova ameaça sombria em Alfea.</div>
            </div>
        </div>
    </div>

    <!-- Seção de Vídeos -->
    <div id="videos" class="video-container">
        <h2>Assista ao Vídeo de Winx - O Filme</h2>
        <iframe src="https://www.youtube.com/embed/JnHZszZz6kM" title="Winx Club: O Filme" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>

    <div class="video-container">
        <h2>Assista ao Vídeo - Winx Club: Transformações</h2>
        <iframe src="https://www.youtube.com/embed/3ndz5g6lcAo" title="Winx Club: Transformações" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>

    <!-- Rodapé -->
    <footer id="sobre">
        <p>&copy; 2024 Site de Filmes - Winx. Todos os direitos reservados.</p>
    </footer>

</body>
</html>

           
    
