
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GENIAL COMPANY® - SITE EM CONSTRUÇÃO</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #1E90FF;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #FFA500;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        .container {
            padding: 20px;
        }
        .section {
            margin-bottom: 40px;
        }
        .section h2 {
            border-bottom: 2px solid #1E90FF;
            padding-bottom: 10px;
            color: #1E90FF;
        }
        .about, .projects, .contact {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .vlog, .gallery {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            margin-top: 20px;
        }
        .gallery img {
            width: 100%;
            max-width: 300px;
            margin: 10px;
            border-radius: 8px;
        }
        .contact form {
            display: flex;
            flex-direction: column;
        }
        .contact label {
            margin-bottom: 5px;
            font-weight: bold;
        }
        .contact input, .contact textarea {
            margin-bottom: 10px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .contact button {
            background-color: #1E90FF;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        footer {
            background-color: #1E90FF;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Guilherme Paiva</h1>
    <p>CEO e Founder da Genial Global Company</p>
</header>

<nav>
    <a href="#about">Sobre Mim</a>
    <a href="#vlog">Dayli Vlog</a>
    <a href="#projects">Projetos</a>
    <a href="#gallery">Galeria</a>
    <a href="#contact">Contato</a>
</nav>

<div class="container">

    <section id="about" class="section about">
        <h2>Sobre Mim</h2>
        <p>Genial Company, sob a liderança de Guilherme Paiva, 32 anos, é sinônimo de resultados excepcionais em gestão de marketing e tráfego online. Com 10 anos de experiência, Genial nasceu da fusão inovadora entre serviços de motoboy e design de mídias sociais, observando a necessidade dos comerciantes locais e vendedores e-commerce de coletar clientes para atrair mais vendas, vimos ali a oportunidade de fazer esta revolução poderosa no mercado. Fazer a junção perfeita do seu produto ou serviço com a audiência correta! Combinando eficiência, logística e criatividade vamos impulsionar seus negócios rumo ao sucesso. 
</p>
    </section>

    <section id="vlog" class="section vlog">
        <h2>Dayli Vlog</h2>
        <p>Acompanhe o meu dia-a-dia no facebook e instagram GENIAL COMPANY</p>
        <!-- Embed de vídeos do YouTube ou outra plataforma -->
    </section>

    <section id="projects" class="section projects">
        <h2>Projetos</h2>
        <p>VEJA MAIS PROJETOS NO INSTAGRAM E FACEBOOK GENIAL COMPANY®</p>
        <!-- Lista de projetos -->
    </section>

    <section id="gallery" class="section gallery">
        <h2>Galeria</h2>
        <p>Confira algumas fotos dos projetos e do meu dia-a-dia NO FACEBOOK E INSTAGRAM.</p>
        <!-- Imagens da galeria -->
        <img src="foto1.jpg" alt="Foto 1">
        <img src="foto2.jpg" alt="Foto 2">
        <img src="foto3.jpg" alt="Foto 3">
    </section>

    <section id="contact" class="section contact">
        <h2>Contato</h2>
        <p>Entre em contato comigo (genialglobalcompany@gmail.com) para saber mais sobre como posso ajudar a impulsionar o seu negócio.</p>
        <form action="mailto:seu-email@exemplo.com" method="post" enctype="text/plain">
            <label for="name">Nome:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Mensagem:</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            
            <button type="submit">Enviar</button>
        </form>
    </section>

</div>

<footer>
    <p>&copy; 2024 GENIAL COMPANY® - Genial Global Company. Todos os direitos reservados.</p>
</footer>

</body>
</html>
