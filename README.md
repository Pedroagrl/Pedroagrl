<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Overboard GitHub</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: #0f111a;
            color: #fff;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: flex-start;
            min-height: 100vh;
            margin: 0;
            padding: 20px;
        }

        .typing-title {
            font-family: 'Righteous', cursive;
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        .profile-image {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 3px solid #fff;
            object-fit: cover;
            margin-bottom: 20px;
        }

        .skills, .socials {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            justify-content: center;
            margin-bottom: 30px;
        }

        .skill, .social {
            display: flex;
            flex-direction: column;
            align-items: center;
            cursor: pointer;
            transition: transform 0.2s;
        }

        .skill:hover, .social:hover {
            transform: scale(1.1);
        }

        .skill i, .social i {
            font-size: 2.5rem;
            margin-bottom: 5px;
            color: #00bfff;
        }

        .social i {
            color: #f0f0f0;
        }

        .social span {
            margin-top: 5px;
            font-size: 0.9rem;
        }

        hr {
            width: 80%;
            border: 0;
            height: 1px;
            background: #555;
            margin-bottom: 30px;
        }

        .about {
            max-width: 600px;
            text-align: center;
            line-height: 1.6;
            margin-bottom: 40px;
        }

        a {
            text-decoration: none;
            color: inherit;
        }
    </style>
</head>
<body>
    <h1 class="typing-title">Olá, eu sou Pedro!</h1>
    <img src="https://avatars.githubusercontent.com/u/12345678?v=4" alt="Foto de Perfil" class="profile-image">

    <div class="skills">
        <div class="skill"><i class="fab fa-python"></i>Python</div>
        <div class="skill"><i class="fab fa-js-square"></i>JavaScript</div>
        <div class="skill"><i class="fab fa-react"></i>React</div>
        <div class="skill"><i class="fas fa-database"></i>SQL</div>
        <div class="skill"><i class="fab fa-github"></i>GitHub</div>
    </div>

    <hr>

    <div class="socials">
        <a href="mailto:seuemail@gmail.com" class="social" target="_blank">
            <i class="fas fa-envelope"></i>
            <span>Email</span>
        </a>
        <a href="https://www.linkedin.com/in/seulinkedin" class="social" target="_blank">
            <i class="fab fa-linkedin"></i>
            <span>LinkedIn</span>
        </a>
        <a href="https://github.com/seugithub" class="social" target="_blank">
            <i class="fab fa-github"></i>
            <span>GitHub</span>
        </a>
    </div>

    <div class="about">
        <p>Sou estudante de Ciência da Computação com experiência em Back-end Python e desenvolvimento de projetos inovadores. Busco aprender continuamente e contribuir para projetos desafiadores.</p>
    </div>
</body>
</html>
