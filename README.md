gh repo clone FloreReyes/Driver-Kings<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Driver Kings - Transporte Seguro</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #fff8dc;
      color: #333;
    }
    header {
      background-color: #ffcc00;
      padding: 20px;
      text-align: center;
      color: black;
    }
    nav {
      background-color: #f2b800;
      padding: 10px;
      text-align: center;
    }
    nav a {
      display: inline-block;
      margin: 5px 10px;
      color: black;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 20px;
      max-width: 800px;
      margin: auto;
    }
    footer {
      background-color: #ffcc00;
      text-align: center;
      padding: 20px;
    }
    form {
      display: flex;
      flex-direction: column;
    }
    input, textarea {
      padding: 10px;
      margin: 10px 0;
      font-size: 16px;
      width: 100%;
      box-sizing: border-box;
    }
    button {
      background-color: #f2b800;
      border: none;
      padding: 10px;
      font-size: 16px;
      cursor: pointer;
    }
    .whatsapp {
      display: inline-block;
      background-color: #25d366;
      color: white;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 5px;
      margin-top: 10px;
    }
    @media (max-width: 600px) {
      nav a {
        display: block;
        margin: 10px 0;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Driver Kings</h1>
    <p>Tu servicio confiable de transporte</p>
  </header>

  <nav>
    <a href="#servicios">Servicios</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="servicios">
    <h2>Nuestros Servicios</h2>
    <ul>
      <li>Transporte privado 24/7</li>
      <li>Viajes programados</li>
      <li>Servicio ejecutivo</li>
      <li>Traslados al aeropuerto</li>
    </ul>
  </section>

  <section id="contacto">
    <h2>Contáctanos</h2>
    <form action="https://formspree.io/f/{tu-codigo}" method="POST">
      <label>Nombre:</label>
      <input type="text" name="nombre" required>

      <label>Email:</label>
      <input type="email" name="email" required>

      <label>Mensaje:</label>
      <textarea name="mensaje" rows="5" required></textarea>

      <button type="submit">Enviar</button>
    </form>

    <p>O escríbenos por WhatsApp:</p>
    <a class="whatsapp" href="https://wa.me/525633162891" target="_blank">
      Chatea por WhatsApp
    </a>
  </section>

  <footer>
    <p>&copy; 2025 Driver Kings. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
