<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Tango - Academia Estrella</title>
  <link rel="stylesheet" href="css/estilos.css">
</head>
<body>
  <header>
    <h1>Clase de Tango</h1>
    <nav>
      <a href="index.html">Inicio</a>
      <a href="clases.html">Clases</a>
      <a href="estilos.html">Estilos</a>
      <a href="contacto.html">Contacto</a>
      <a href="https://es.wikipedia.org/wiki/Tango" target="_blank">¿Qué es el Tango?</a>
    </nav>
  </header>

  <main>
    <section>
      <h2>¿Qué es el Tango?</h2>
      <p>El tango es una danza sensual y elegante originaria de Argentina y Uruguay. Se caracteriza por su fuerte conexión entre la pareja, pasos marcados, pausas dramáticas y una profunda expresión emocional.</p>
      <img src="media/tango.jpg" alt="Pareja bailando tango" width="400">
    </section>

    <section>
      <h2>Horarios y Precios</h2>
      <table>
        <tr>
          <th>Día</th>
          <th>Horario</th>
          <th>Nivel</th>
          <th>Precio mensual</th>
        </tr>
        <tr>
          <td>Miércoles y Viernes</td>
          <td>7:00 PM - 8:30 PM</td>
          <td>Todos los niveles</td>
          <td>$380</td>
        </tr>
      </table>
    </section>

    <section>
      <h2>Inscríbete a Tango</h2>
      <form>
        <label>Nombre completo: <input type="text" name="nombre"></label><br>
        <label>Edad: <input type="number" name="edad"></label><br>
        <label>Email: <input type="email" name="email"></label><br>
        <input type="submit" value="Inscribirme">
      </form>
    </section>

    <section>
      <h2>Video de clase</h2>
      <video src="media/tango-video.mp4" width="400" controls></video>
    </section>

    <section>
      <h2>Música típica del Tango</h2>
      <audio src="media/tango-musica.mp3" controls></audio>
    </section>
  </main>

  <footer>
    <marquee>¡Aprende a bailar el Tango con pasión y elegancia!</marquee>
    <p>&copy; 2025 Academia Estrella</p>
  </footer>
</body>
</html>
