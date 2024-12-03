<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Portafolio - Desarrollador Web</title>
    <style>
        /* Estilos generales */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav {
            background-color: #444;
            padding: 10px;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        section {
            padding: 40px 20px;
            max-width: 900px;
            margin: 0 auto;
        }

        section h2 {
            border-bottom: 2px solid #ddd;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }

        #skills ul {
            list-style: none;
            padding: 0;
        }

        #skills ul li {
            background: #eaeaea;
            margin: 5px 0;
            padding: 10px;
            border-radius: 5px;
        }

        #projects .project {
            background: #fff;
            padding: 15px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        #contact p {
            margin: 5px 0;
        }

        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #333;
            color: #fff;
            margin-top: 20px;
        }
    </style>
</head>

<body>

    <header>
        <h1>Estefania Guanoluisa</h1>
        <p>Desarrollador Web | Frontend & Backend</p>
    </header>

    <nav>
        <ul>
            <li><a href="#about">Sobre mí</a></li>
            <li><a href="#skills">Habilidades</a></li>
            <li><a href="#projects">Proyectos</a></li>
            <li><a href="#contact">Contacto</a></li>
        </ul>
    </nav>

    <section id="about">
        <h2>Sobre mí</h2>
        <p>Soy un desarrollador web apasionado por crear aplicaciones modernas y funcionales. Tengo experiencia en
            desarrollo frontend y backend, utilizando tecnologías como HTML, CSS, JavaScript, y frameworks como React y
            Node.js.</p>
    </section>

    <section id="skills">
        <h2>Habilidades</h2>
        <ul>
            <li>HTML, CSS, JavaScript</li>
            <li>React, Angular</li>
            <li>Node.js, Express.js</li>
            <li>MySQL, MongoDB</li>
            <li>Git y control de versiones</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Proyectos</h2>
        <div class="project">
            <h3>Sitio Web Portafolio</h3>
            <p>Un sitio web personal que muestra mis proyectos y habilidades. <a href="#">Ver proyecto</a></p>
        </div>
        <div class="project">
            <h3>Aplicación de Tareas</h3>
            <p>Una aplicación para organizar tareas diarias usando React y Firebase. <a href="#">Ver proyecto</a></p>
        </div>
    </section>

    <section id="contact">
        <h2>Contacto</h2>
        <p>Email: <a href="mailto:tuemail@correo.com">tuemail@correo.com</a></p>
        <p>LinkedIn: <a href="https://linkedin.com/in/tuusuario" target="_blank">linkedin.com/in/tuusuario</a></p>
        <p>GitHub: <a href="https://github.com/tuusuario" target="_blank">github.com/tuusuario</a></p>
    </section>

    <footer>
        <p>© 2024 Tu Nombre. Todos los derechos reservados.</p>
    </footer>

</body>

</html>
