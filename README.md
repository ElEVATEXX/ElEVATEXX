<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curso de Trading</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Curso de Trading</h1>
            <nav>
                <ul>
                    <li><a href="#inicio">Inicio</a></li>
                    <li><a href="#acerca">Acerca de</a></li>
                    <li><a href="#cursos">Cursos</a></li>
                    <li><a href="#contacto">Contacto</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="inicio" class="hero">
        <div class="container">
            <h2>Conviértete en un Trader Experto</h2>
            <p>Aprende estrategias probadas y domina el mercado financiero.</p>
            <a href="#cursos" class="btn">Ver Cursos</a>
        </div>
    </section>

    <section id="acerca">
        <div class="container">
            <h2>Acerca de mí</h2>
            <p>Hola, somos Cristian y Moha ], un trader con más de [4 años] de experiencia. Mi misión es ayudarte a lograr tus metas financieras a través del trading.</p>
        </div>
    </section>

    <section id="cursos">
        <div class="container">
            <h2>Nuestros Cursos</h2>
            <div class="course">
                <h3>Curso Básico de Trading</h3>
                <p>Aprende los fundamentos del trading. Precio: $99</p>
                <a href="#" class="btn">Inscribirme</a>
            </div>
            <div class="course">
                <h3>Curso Avanzado de Trading</h3>
                <p>Perfecciona tus habilidades y domina estrategias avanzadas. Precio: $199</p>
                <a href="#" class="btn">Inscribirme</a>
            </div>
        </div>
    </section>

    <section id="contacto">
        <div class="container">
            <h2>Contacto</h2>
            <form action="#" method="post">
                <label for="nombre">Nombre:</label>
                <input type="text" id="nombre" name="nombre" required>

                <label for="email">Correo Electrónico:</label>
                <input type="email" id="email" name="email" required>

                <label for="mensaje">Mensaje:</label>
                <textarea id="mensaje" name="mensaje" rows="4" required></textarea>

                <button type="submit">Enviar</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Curso de Trading. Todos los derechos reservados.</p>
            <ul>
                <li><a href="#">Facebook</a></li>
                <li><a href="#">Instagram</a></li>
                <li><a href="#">Twitter</a></li>
            </ul>
        </div>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

.container {
    width: 90%;
    margin: 0 auto;
    max-width: 1200px;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: space-around;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

.hero {
    background: #0074d9;
    color: #fff;
    text-align: center;
    padding: 2rem 0;
}

.hero .btn {
    background: #ff4136;
    color: #fff;
    padding: 0.5rem 1rem;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
}

section {
    padding: 2rem 0;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    margin-top: 2rem;
}

footer ul {
    list-style: none;
    display: flex;
    justify-content: center;
    padding: 0;
}

footer a {
    color: #fff;
    text-decoration: none;
    margin: 0 1rem;
}
