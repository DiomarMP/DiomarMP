<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Sitio Web</title>
    <style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

/* Encabezado */
header {
    background-color: #007bff;
    color: #fff;
    padding: 20px;
    text-align: center;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
}

nav a:hover {
    text-decoration: underline;
}

/* Sección Principal */
main {
    padding: 20px;
}

h2 {
    color: #007bff;
}

.card-container {
    display: flex;
    gap: 20px;
    justify-content: space-around;
    margin-top: 20px;
}

.card {
    background-color: #fff;
    padding: 20px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    width: 250px;
}

.card h3 {
    margin-bottom: 10px;
}

.card p {
    color: #666;
}

/* Pie de página */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    margin-top: 20px;
}

    </style>
</head>
<body>
    <!-- Encabezado -->
    <header>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Sobre Mí</a></li>
                <li><a href="#">Servicios</a></li>
                <li><a href="#">Contacto</a></li>
            </ul>
        </nav>
        <h1>Bienvenido a Mi Sitio Web</h1>
    </header>

    <!-- Sección Principal -->
    <main>
        <section>
            <h2>Sobre mi</h2>
            <p> Nombre: Diomar Jeyson Mamani Pacori</p>
            <p>Carrera: Administracion</p>
            <p>Edad: 22</p>
        </section>

        <section>
            <h2>Servicios</h2>
            <div class="card-container">
                <div class="card">
                    <h3>Desarrollo Web</h3>
                    <p>Ofrecemos servicios de desarrollo de sitios web adaptables y de alto rendimiento.</p>
                </div>
                <div class="card">
                    <h3>Marketing Digital</h3>
                    <p>Impulsa tu negocio con estrategias de marketing digital efectivas.</p>
                </div>
                <div class="card">
                    <h3>Consultoría IT</h3>
                    <p>Soluciones de consultoría IT para optimizar tus procesos empresariales.</p>
                </div>
            </div>
        </section>
    </main>

    <!-- Pie de página -->
    <footer>
        <p>&copy; 2024 Mi Sitio Web. Todos los derechos reservados.</p>
    </footer>

</body>
</html>

</body>
</html>
