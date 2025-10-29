<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inspiración en Miniatura</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
            color: #361702;
        }
        header {
            background-color: #E58DB1;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }
        nav {
            background-color: #6FEDBD;
            text-align: center;
            padding: 10px 0;
        }
        nav a {
            color: #361702;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 40px;
            text-align: center;
        }
        .productos {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .producto {
            border: 2px solid #E58DB1;
            border-radius: 10px;
            width: 250px;
            padding: 15px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            background-color: #fff;
        }
        .producto img {
            width: 100%;
            border-radius: 10px;
        }
        footer {
            background-color: #E58DB1;
            color: #fff;
            text-align: center;
            padding: 20px;
        }
        html {
            scroll-behavior: smooth;
        }
    </style>
</head>
<body>
    <header>
        <h1>Inspiración en Miniatura</h1>
        <p>Cuadros en arcilla con mensajes motivacionales y personalizados</p>
    </header>

    <nav>
        <a href="#productos">Productos</a>
        <a href="#personalizados">Personalizados</a>
        <a href="#mockup">Mockup</a>
        <a href="#contacto">Contáctanos</a>
    </nav>

    <section id="productos">
        <h2>Productos</h2>
        <p>Cada mini cuadro tiene un valor de $12.000. Aquí puedes ver algunos de nuestros diseños:</p>
        <div class="productos">
            <div class="producto">
                <img src="imagen1.jpg" alt="Cuadro motivacional 1">
                <h3>Mensaje Positivo</h3>
                <p>$12.000</p>
            </div>
            <div class="producto">
                <img src="imagen2.jpg" alt="Cuadro motivacional 2">
                <h3>Felicidad en Pequeño</h3>
                <p>$12.000</p>
            </div>
            <div class="producto">
                <img src="imagen3.jpg" alt="Cuadro motivacional 3">
                <h3>Inspiración Diaria</h3>
                <p>$12.000</p>
            </div>
        </div>
    </section>

    <section id="personalizados">
        <h2>Cuadros Personalizados</h2>
        <p>Puedes personalizar tu cuadro con el mensaje o diseño que desees por el mismo valor de $12.000.</p>
    </section>

    <section id="mockup">
        <h2>Mockup del Emprendimiento</h2>
        <p>Aquí puedes ver algunos productos de la marca, como camisetas, pocillos y esferos.</p>
        <div class="productos">
            <div class="producto">
                <img src="camiseta.jpg" alt="Camiseta Inspiración en Miniatura">
                <h3>Camiseta</h3>
            </div>
            <div class="producto">
                <img src="posillo.jpg" alt="Posillo Inspiración en Miniatura">
                <h3>Posillo</h3>
            </div>
            <div class="producto">
                <img src="esfero.jpg" alt="Esfero Inspiración en Miniatura">
                <h3>Esfero</h3>
            </div>
        </div>
    </section>

    <section id="contacto">
        <h2>Contáctanos</h2>
        <p>Síguenos en nuestras redes sociales o escríbenos a nuestro correo electrónico.</p>
        <p><strong>Instagram:</strong> @inspiracionenminiatura</p>
        <p><strong>Correo:</strong> inspiracionenminiatura@gmail.com</p>
    </section>

    <footer>
        <p>&copy; 2025 Inspiración en Miniatura - Todos los derechos reservados</p>
    </footer>
</body>
</html>
