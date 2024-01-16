<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>README</title>
    <style>
        body {
            background-color: #E6F1F1;
            font-family: Arial, sans-serif;
        }
        h1 {
            color: #2C5282;
            text-align: center;
        }
        h2 {
            color: #2C5282;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        .highlight {
            color: #2C5282;
            font-weight: bold;
        }
        .list {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }
        .list li {
            margin-bottom: 10px;
        }
        .list li:before {
            content: "• ";
            color: #2C5282;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>¡Hola! Soy [Tu Nombre]</h1>
        <p>Esta es mi página de GitHub. Aquí encontrarás información sobre mí y mis proyectos.</p>
        <h2>Tabla de contenido</h2>
        <ul class="list">
            <li><a href="#about-me">Sobre mí</a></li>
            <li><a href="#projects">Proyectos</a></li>
            <li><a href="#contact">Contacto</a></li>
        </ul>
        <h2 id="about-me">Sobre mí</h2>
        <p>Soy un desarrollador de software con experiencia en los siguientes lenguajes de programación:</p>
        <ul class="list">
            <li>HTML</li>
            <li>CSS</li>
            <li>MySQL</li>
            <li>PHP</li>
            <li><span class="highlight">Laravel</span></li>
            <li>Git</li>
            <li>Tailwind</li>
            <li>JavaScript</li>
            <li>TDD</li>
            <li>API RESTful</li>
        </ul>
        <p>Si tienes alguna pregunta sobre alguno de estos lenguajes de programación, no dudes en preguntar.</p>
        <h2 id="projects">Proyectos</h2>
        <p>Estos son algunos de mis proyectos:</p>
        <ul class="list">
            <li><a href="#">Proyecto 1</a></li>
            <li><a href="#">Proyecto 2</a></li>
            <li><a href="#">Proyecto 3</a></li>
        </ul>
        <h2 id="contact">Contacto</h2>
        <p>Puedes contactarme a través de los siguientes medios:</p>
        <ul class="list">
            <li><a href="#">Sitio web</a></li>
            <li><a href="#">Twitter</a></li>
            <li><a href="#">LinkedIn</a></li>
        </ul>
    </div>
</body>
</html>
