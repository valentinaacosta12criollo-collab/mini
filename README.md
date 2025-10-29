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
        <img src="logotipo-removebg-preview.png" alt="Logo de Inspiración en Miniatura" style="width:100px; height:auto; display:block; margin:0 auto 10px auto;">
 <style>
  header img {
    width: 120px;
    height: 120px;
    display: block;
    margin: 0 auto 10px auto;
    border-radius: 20px;
     }
 </style>
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
                <img src="producto10.jpeg" alt="Cuadro motivacional 1">
                <h3>Mensaje Positivo</h3>
                <p>$12.000</p>
            </div>
            <div class="producto">
                <img src="producto0.jpeg" alt="Cuadro motivacional 2">
                <h3>Felicidad en Pequeño</h3>
                <p>$12.000</p>
            </div>
            <div class="producto">
                <img src="producto12.jpeg" alt="Cuadro motivacional 3">
                <h3>Inspiración Diaria</h3>
                <p>$12.000</p>
            </div>
        </div>
    </section>
    
  <section id="personalizados">
  <h2>Personaliza el tuyo</h2>
  <p>Si quieres un mensaje, una palabra o un diseño especial, rellena este formulario y nos pondremos en contacto contigo.</p>
  
  <div class="formulario-personalizado">
    <form onsubmit="event.preventDefault(); handleForm();">
      <label for="nombre">Nombre:</label>
      <input type="text" id="nombre" placeholder="Tu nombre" required />

      <label for="correo">Correo electrónico:</label>
      <input type="email" id="correo" placeholder="Tu correo electrónico" required />

      <label for="mensaje">Mensaje o indicaciones:</label>
      <input type="text" id="mensaje" placeholder="Ej: 'Para mamá', 'Ánimo'" required />

      <label for="referencia">Referencia o descripción de la idea:</label>
      <textarea id="referencia" rows="3" placeholder="Describe brevemente tu idea"></textarea>

      <button type="submit">Enviar solicitud — $12.000</button>
    </form>
  </div>
</section>

<style>
  #personalizados {
    text-align: center;
    padding: 40px;
  }

  .formulario-personalizado {
    max-width: 400px;
    margin: 30px auto;
    padding: 25px;
    background-color: #f9f9f9;
    border: 2px solid #E58DB1;
    border-radius: 12px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  }

  .formulario-personalizado form {
    display: flex;
    flex-direction: column;
    gap: 12px;
  }

  .formulario-personalizado label {
    text-align: left;
    font-weight: bold;
    color: #361702;
    font-size: 14px;
  }

  .formulario-personalizado input,
  .formulario-personalizado textarea {
    padding: 10px;
    border: 1.5px solid #E58DB1;
    border-radius: 8px;
    font-size: 14px;
    font-family: Arial, sans-serif;
    width: 100%;
    box-sizing: border-box;
  }

  .formulario-personalizado input:focus,
  .formulario-personalizado textarea:focus {
    outline: none;
    border-color: #6FEDBD;
    background-color: #fff;
  }

  .formulario-personalizado button {
    background-color: #E58DB1;
    color: #fff;
    border: none;
    padding: 12px;
    font-size: 15px;
    border-radius: 10px;
    cursor: pointer;
    transition: 0.3s;
  }

  .formulario-personalizado button:hover {
    background-color: #6FEDBD;
    color: #361702;
  }
</style>
<section id="mision-vision">
  <h2>Misión, Visión y Objetivos</h2>
  <div class="info-container">
    <div class="info-card">
      <h3>Misión</h3>
      <p>
        Inspiración en Miniatura transforma la arcilla en pequeñas obras con mensajes positivos, promoviendo la creatividad, la gratitud y el amor por la cultura artesanal.
      </p>
    </div>
    <div class="info-card">
      <h3>Visión</h3>
      <p>
        Ser un referente de emprendimiento artesanal en Ciudad Bolívar, inspirando a la comunidad educativa y local a través de mini cuadros en arcilla que conectan creatividad, emociones y patrimonio cultural de manera positiva y sostenible.
      </p>
    </div>
    <div class="info-card">
      <h3>Objetivos</h3>
      <p>
        • Diseñar y elaborar mini cuadros en arcilla que inspiren a través de frases positivas. <br>
        • Experimentar con diferentes estilos y temáticas para diversificar las creaciones. <br>
        • Promover el arte artesanal como medio de comunicación emocional y cultural.
      </p>
    </div>
  </div>
</section>

<style>
  #mision-vision {
    background-color: #fdf7f9;
    padding: 40px;
    text-align: center;
  }

  #mision-vision h2 {
    color: #361702;
    margin-bottom: 30px;
  }

  .info-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
  }

  .info-card {
    background-color: #ffffff;
    border: 2px solid #E58DB1;
    border-radius: 12px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    padding: 20px;
    width: 280px;
    text-align: center;
  }

  .info-card h3 {
    color: #E58DB1;
    margin-bottom: 10px;
  }

  .info-card p {
    color: #361702;
    font-size: 14px;
    line-height: 1.5;
  }
</style>
    <section id="mockup">
        <h2>Mockup del Emprendimiento</h2>
        <p>Aquí puedes ver algunos productos de la marca, como camisetas, Gorras y esferos.</p>
        <div class="productos">
            <div class="producto">
                <img src="camisa.png" alt="Camiseta Inspiración en Miniatura">
                <h3>Camiseta</h3>
            </div>
            <div class="producto">
                <img src="gorra2.png" alt="Gorra Inspiración en Miniatura">
                <h3>Gorra</h3>
            </div>
            <div class="producto">
                <img src="lapicero.png" alt="Esfero Inspiración en Miniatura">
                <h3>Esfero</h3>
            </div>
        </div>
    </section>

    <section id="contacto">
        <h2>Contáctanos</h2>
        <p>Síguenos en nuestras redes sociales o escríbenos a nuestro correo electrónico.</p>
        <p><strong>Instagram:</strong> <a class="enlace" href="https://www.instagram.com/inspiracionenminiatura" target="_blank">@inspiracionenminiatura</a></p>
        <p><strong>Correo:</strong> <a class="enlace" href="mailto:inspiracionenminiatura@gmail.com">inspiracionenminiatura@gmail.com</a></p>
    </section>

    <footer>
        <p>&copy; 2025 Inspiración en Miniatura - Todos los derechos reservados</p>
    </footer>
</body>
</html>
