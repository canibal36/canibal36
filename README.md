<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Página de presentación de Leonel Arízaga Díaz, Programador Full Stack Web & App Developer">
  <title>Leonel Arízaga Díaz - Full Stack Developer</title>
  <style>
    /* Estilos generales */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Arial', sans-serif;
    }

    body {
      background-color: #f4f4f4;
      font-size: 16px;
      line-height: 1.6;
      color: #333;
      margin: 0;
    }

    /* Sección principal */
    .hero-section {
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      background: linear-gradient(135deg, #ff7e5f, #feb47b);
      padding: 20px;
    }

    /* Contenedor principal de la sección */
    .hero-container {
      display: flex;
      align-items: center;
      justify-content: space-between;
      width: 100%;
      max-width: 1200px;
      background-color: white;
      border-radius: 10px;
      padding: 30px;
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
    }

    /* Contenedor de la imagen */
    .image-container {
      flex: 1;
      text-align: center;
      padding: 20px;
    }

    .hero-image {
      width: 100%;
      max-width: 250px;
      border-radius: 50%;
      object-fit: cover;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
    }

    /* Contenedor de texto */
    .text-container {
      flex: 2;
      padding: 40px;
    }

    /* Estilo del nombre */
    .name {
      font-size: 2rem;
      font-weight: bold;
      color: #333;
      margin-bottom: 10px;
      text-align: center;
    }

    /* Estilo del título */
    .title {
      font-size: 1.5rem;
      font-weight: 500;
      color: #555;
      margin-bottom: 20px;
      text-align: center;
    }

    /* Estilo de la descripción */
    .description {
      font-size: 1rem;
      color: #666;
      line-height: 1.5;
      margin-bottom: 30px;
      text-align: center;
    }

    /* Contenedor de habilidades */
    .skills {
      display: flex;
      justify-content: center;
      gap: 15px;
    }

    /* Estilo de cada habilidad */
    .skill {
      font-size: 1rem;
      font-weight: 600;
      color: #fff;
      background-color: #333;
      padding: 8px 15px;
      border-radius: 30px;
      text-transform: capitalize;
      transition: background-color 0.3s ease;
    }

    /* Efecto hover para las habilidades */
    .skill:hover {
      background-color: #feb47b;
    }
  </style>
</head>
<body>

  <!-- Sección de presentación -->
  <section id="about" class="hero-section">
    <div class="hero-container">
      <!-- Imagen del perfil -->
      <div class="image-container">
        <img src="assets/imgs/people.png" alt="Leonel Arízaga" class="hero-image" />
      </div>
      
      <!-- Contenedor de texto -->
      <div class="text-container">
        <h1 class="name">Leonel Arízaga Díaz</h1>
        <h2 class="title">Programador Full Stack Web &amp; App Developer</h2>
        <p class="description">
          Soy un desarrollador con experiencia en tecnologías como NodeJS, React, Angular, y Laravel. Me apasiona crear soluciones web innovadoras y robustas.
        </p>
        
        <!-- Habilidades -->
        <div class="skills">
          <p class="skill">NodeJS</p>
          <p class="skill">React</p>
          <p class="skill">Angular</p>
          <p class="skill">Laravel</p>
          <p class="skill">Lee mas abajo para poder ver los lenguajes de programacion en los que trabajo.</p>
        </div>
      </div>
    </div>
  </section>

</body>
</html>
