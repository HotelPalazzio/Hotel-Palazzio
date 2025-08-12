<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Hotel Palazzio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Helvetica Neue', sans-serif;
      background-color: #EDD8BF;
      color: #020E2B;
    }

    header {
      background-image: url('https://i.pinimg.com/736x/e4/3c/21/e43c2125a8b5d50d436966053d47bde4.jpg');
      background-size: cover;
      background-position: center;
      text-align: center;
      padding: 3em 1em;
      position: relative;
    }

    header img {
      max-width: 300px;
      height: auto;
      z-index: 1;
    }

    nav {
      background-color: #023965;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 1em;
      display: inline-block;
      padding: 1em;
    }

    nav a:hover {
      background-color: #4A4A72;
    }

    section {
      padding: 2em;
    }

    h2 {
      border-bottom: 2px solid #023965;
      padding-bottom: 0.3em;
    }

    .habitaciones {
      display: flex;
      flex-wrap: wrap;
      gap: 2em;
    }

    .habitacion {
      background-color: white;
      border: 1px solid #4A4A72;
      border-radius: 10px;
      padding: 1em;
      width: calc(33% - 2em);
    }

    .contacto form {
      display: flex;
      flex-direction: column;
      gap: 1em;
      max-width: 500px;
    }

    .contacto input, .contacto textarea {
      padding: 0.8em;
      border: 1px solid #4A4A72;
      border-radius: 5px;
    }

    .contacto button {
      background-color: #023965;
      color: white;
      padding: 1em;
      border: none;
      cursor: pointer;
    }

    .contacto button:hover {
      background-color: #020E2B;
    }

    footer {
      background-color: #020E2B;
      color: white;
      text-align: center;
      padding: 1.5em 1em;
    }

    @media (max-width: 768px) {
      .habitacion {
        width: 100%;
      }

      header img {
        max-width: 200px;
      }
    }
  </style>
</head>
<body>

  <header>
    <img src="Imagen2.png" alt="Logo Hotel Palazzio" />
  </header>

  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#quienes">Quiénes somos</a>
    <a href="#servicios">Habitaciones</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="inicio">
    <h2>Bienvenidos a Palazzio</h2>
    <p>Ubicado frente al mar en el norte de Pinamar, Hotel Palazzio fusiona el lujo mediterráneo con el estilo contemporáneo para ofrecer una experiencia inolvidable.</p>
  </section>

  <section id="quienes">
    <h2>Quiénes somos</h2>
    <p>Somos un hotel boutique inspirado en las costas italianas y griegas. Nuestro complejo está compuesto por casas de estilo griego con piscina privada, orientadas al mar. Ofrecemos restaurante buffet, restaurante griego e italiano.</p>

    <h3>Misión</h3>
    <p>Ser el destino costero más deseado de Sudamérica, inspirando con cada detalle, enamorando con cada estadía.</p>

    <h3>Visión</h3>
    <p>Crear experiencias memorables donde el lujo relajado del Mediterráneo se viva y se comparta.</p>

    <h3>Valores</h3>
    <ul>
      <li><strong>Lujo y privacidad:</strong> vacaciones en intimidad y grandiosidad.</li>
      <li><strong>Tranquilidad:</strong> disfrutar del sonido del mar en paz y armonía.</li>
      <li><strong>Estética como experiencia:</strong> cada detalle está diseñado para ser vivido y compartido.</li>
      <li><strong>Vibras que inspiran:</strong> atmósferas que generan creatividad y pasión.</li>
    </ul>
  </section>

  <section id="servicios">
    <h2>Habitaciones y Precios</h2>
    <div class="habitaciones">
      <div class="habitacion">
        <h3>Suite Mediterránea</h3>
        <p>Vista al mar, cama king, piscina privada.</p>
        <p><strong>USD 350 / noche</strong></p>
      </div>
      <div class="habitacion">
        <h3>Villa Griega</h3>
        <p>Estilo tradicional griego, ideal para parejas.</p>
        <p><strong>USD 280 / noche</strong></p>
      </div>
      <div class="habitacion">
        <h3>Casa del Mar</h3>
        <p>Amplia casa con 2 dormitorios y vista completa al océano.</p>
        <p><strong>USD 450 / noche</strong></p>
      </div>
    </div>
  </section>

  <section id="contacto" class="contacto">
    <h2>Contacto</h2>
    <p>¿Tenés alguna consulta? Escribinos:</p>
    <form>
      <input type="text" placeholder="Nombre" required>
      <input type="email" placeholder="Correo electrónico" required>
      <textarea rows="5" placeholder="Escribí tu mensaje..."></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Hotel Palazzio - Elegancia frente al mar</p>
  </footer>

</body>
</html>
