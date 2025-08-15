# Acuario-Nacional
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Acuario Nacional de la República Dominicana</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Acuario Nacional</h1>
        <nav>
            <a href="#inicio">Inicio</a>
            <a href="#historia">Historia</a>
            <a href="#atracciones">Atracciones</a>
            <a href="#visita">Información de Visita</a>
            <a href="#contacto">Contacto</a>
        </nav>
    </header>

    <section id="inicio">
        <h2>Bienvenidos</h2>
        <p>El Acuario Nacional de la República Dominicana es uno de los centros marinos más importantes del Caribe, dedicado a la educación, conservación y exhibición de especies marinas.</p>
    </section>

    <section id="historia">
        <h2>Historia</h2>
        <p>Fundado en 1990, el Acuario Nacional ha sido un espacio dedicado a la preservación de la vida marina, la investigación científica y la educación ambiental. Alberga cientos de especies que representan la biodiversidad de nuestras aguas.</p>
    </section>

    <section id="atracciones">
        <h2>Atracciones</h2>
        <ul>
            <li>Túnel Submarino</li>
            <li>Exhibición de corales y peces tropicales</li>
            <li>Muestra de especies en peligro de extinción</li>
            <li>Áreas educativas para niños</li>
        </ul>
    </section>

    <section id="visita">
        <h2>Información de Visita</h2>
        <p><strong>Horario:</strong> Martes a Domingo, 9:00 AM - 5:00 PM</p>
        <p><strong>Dirección:</strong> Av. España, Santo Domingo Este, R.D.</p>
        <p><strong>Entrada:</strong> Adultos RD$100 | Niños RD$50</p>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <p>Email: info@acuariord.com</p>
        <p>Teléfono: +1 (809) 592-6666</p>
    </section>

    <footer>
        <p>© 2025 Acuario Nacional - Página creada para fines educativos.</p>
    </footer>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f0f8ff;
    color: #333;
}

header {
    background-color: #0077b6;
    color: white;
    padding: 1rem;
    text-align: center;
}

nav a {
    color: white;
    margin: 0 10px;
    text-decoration: none;
    font-weight: bold;
}

nav a:hover {
    text-decoration: underline;
}

section {
    padding: 20px;
    max-width: 900px;
    margin: auto;
}

h2 {
    color: #0077b6;
    margin-bottom: 10px;
}

ul {
    list-style-type: square;
    margin-left: 20px;
}

footer {
    background-color: #023e8a;
    color: white;
    text-align: center;
    padding: 10px;
    margin-top: 20px;
}

@media (max-width: 600px) {
    nav {
        display: flex;
        flex-direction: column;
    }
    nav a {
        margin: 5px 0;
    }
}
