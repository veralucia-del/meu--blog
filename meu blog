<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Simples</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .carousel {
            width: 100%;
            overflow: hidden;
            position: relative;
            margin-bottom: 20px;
        }
        .carousel img {
            width: 100%;
            display: none;
        }
        .carousel img.active {
            display: block;
        }
        .search-bar {
            text-align: center;
            margin: 20px 0;
        }
        .search-bar input[type="text"] {
            width: 50%;
            padding: 10px;
            border: 1px solid #ccc;
        }
        .search-bar button {
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }
        .search-bar button:hover {
            background-color: #45a049;
        }
        .container {
            display: flex;
            width: 80%;
            margin: auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .content {
            flex: 3;
            margin-right: 20px;
        }
        .sidebar {
            flex: 1;
        }
        .sidebar h3 {
            color: #4CAF50;
            border-bottom: 2px solid #4CAF50;
            padding-bottom: 5px;
        }
        .sidebar ul {
            list-style: none;
            padding: 0;
        }
        .sidebar ul li {
            margin: 10px 0;
        }
        .sidebar ul li a {
            text-decoration: none;
            color: #333;
        }
        .sidebar ul li a:hover {
            color: #4CAF50;
        }
        .featured-posts {
            margin-bottom: 20px;
        }
        .featured-posts h2 {
            color: #4CAF50;
        }
        .featured-posts .post {
            border: 1px solid #ccc;
            padding: 10px;
            margin-bottom: 10px;
        }
        .post {
            margin-bottom: 20px;
        }
        .post h2 {
            color: #4CAF50;
        }
        .post p {
            line-height: 1.6;
        }
        .post img {
            max-width: 100%;
            height: auto;
            margin: 10px 0;
        }
        .comments {
            margin-top: 20px;
        }
        .comments h3 {
            color: #4CAF50;
        }
        .comments textarea {
            width: 100%;
            height: 100px;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
        }
        .comments button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
        }
        .comments button:hover {
            background-color: #45a049;
        }
        .contact-form {
            margin-top: 40px;
        }
        .contact-form h2 {
            color: #4CAF50;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0 10px 0;
            border: 1px solid #ccc;
        }
        .contact-form button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #45a049;
        }
        .testimonials {
            background-color: #f9f9f9;
            padding: 20px;
            margin: 20px 0;
            text-align: center;
        }
        .testimonials h2 {
            color: #4CAF50;
        }
        .testimonial {
            margin-bottom: 15px;
        }
        .testimonial p {
            font-style: italic;
        }
        .testimonial strong {
            display: block;
            margin-top: 5px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
        .social-icons a {
            margin: 0 10px;
            color: white;
            text-decoration: none;
            font-size: 1.2rem;
        }
    </style>
    <script>
        let currentSlide = 0;
        function showSlide(index) {
            const slides = document.querySelectorAll('.carousel img');
            slides.forEach((slide, i) => {
                slide.classList.remove('active');
                if (i === index) {
                    slide.classList.add('active');
                }
            });
        }
        function nextSlide() {
            const slides = document.querySelectorAll('.carousel img');
            currentSlide = (currentSlide + 1) % slides.length;
            showSlide(currentSlide);
        }
        window.onload = function() {
            showSlide(currentSlide);
            setInterval(nextSlide, 3000);
        }
    </script>
</head>
<body>
    <header>
        <h1>Meu Blog Simples</h1>
    </header>

    <nav>
        <a href="#">Início</a>
        <a href="#contato">Contato</a>
    </nav>

    <div class="carousel">
        <img src="https://via.placeholder.com/1200x400?text=Imagem+1" class="active" alt="Slide 1">
        <img src="https://via.placeholder.com/1200x400?text=Imagem+2" alt="Slide 2">
        <img src="https://via.placeholder.com/1200x400?text=Imagem+3" alt="Slide 3">
    </div>

    <div class="search-bar">
        <input type="text" placeholder="Buscar no blog...">
        <button>Buscar</button>
    </div>

    <div class="container">
        <div class="content">
            <div class="featured-posts">
                <h2>Posts em Destaque</h2>
                <div class="post">
                    <h3>Post em Destaque 1</h3>
                    <p>Uma prévia do conteúdo do post em destaque.</p>
                </div>
                <div class="post">
                    <h3>Post em Destaque 2</h3>
                    <p>Outra prévia do conteúdo do post em destaque.</p>
                </div>
            </div>
            <div class="post">
                <h2>Primeiro Post do Blog</h2>
                <p>Publicado em 23 de fevereiro de 2025</p>
                <img src="https://via.placeholder.com/800x400" alt="Imagem do primeiro post">
                <p>Bem-vindo ao meu novo blog! Aqui você encontrará artigos, dicas e novidades sobre diversos temas.</p>
                <div class="comments">
                    <h3>Deixe seu comentário</h3>
                    <textarea placeholder="Escreva seu comentário aqui..."></textarea>
                    <button>Enviar Comentário</button>
                </div>
            </div>
            <div class="post">
                <h2>Segundo Post do Blog</h2>
                <p>Publicado em 20 de fevereiro de 2025</p>
                <img src="https://via.placeholder.com/800x400" alt="Imagem do segundo post">
                <p>Este é o meu segundo post. Fique à vontade para comentar e compartilhar com seus amigos!</p>
                <div class="comments">
                    <h3>Deixe seu comentário</h3>
                    <textarea placeholder="Escreva seu comentário aqui..."></textarea>
                    <button>Enviar Comentário</button>
                </div>
            </div>
            <div class="contact-form" id="contato">
                <h2>Entre em Contato</h2>
                <input type="text" placeholder="Seu Nome">
                <input type="email" placeholder="Seu Email">
                <textarea placeholder="Sua Mensagem"></textarea>
                <button>Enviar Mensagem</button>
            </div>
            <div class="testimonials">
                <h2>Depoimentos</h2>
                <div class="testimonial">
                    <p>"Este blog mudou minha perspectiva sobre muitos assuntos!"</p>
                    <strong>- Maria Silva</strong>
                </div>
                <div class="testimonial">
                    <p>"Adoro os posts e as dicas compartilhadas aqui. Sempre aprendo algo novo!"</p>
                    <strong>- João Pereira</strong>
                </div>
            </div>
        </div>
        <aside class="sidebar">
            <h3>Categorias</h3>
            <ul>
                <li><a href="#">Bem-estar</a></li>
                <li><a href="#">Espiritualidade</a></li>
                <li><a href="#">Autoestima</a></li>
                <li><a href="#">Saúde</a></li>
                <li><a href="#">Neurociência</a></li>
            </ul>
        </aside>
    </div>

    <footer>
        <p>&copy; 2025 Meu Blog Simples. Todos os direitos reservados.</p>
        <div class="social-icons">
            <a href="https://www.facebook.com" target="_blank">Facebook</a>
            <a href="https://www.instagram.com" target="_blank">Instagram</a>
            <a href="https://www.linkedin.com" target="_blank">LinkedIn</a>
        </div>
    </footer>
</body>
</html>
