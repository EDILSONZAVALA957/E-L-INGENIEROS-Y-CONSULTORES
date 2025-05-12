<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>E&L Ingenieros y Consultores</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <script src="https://kit.fontawesome.com/a2e0b8e2e4.js" crossorigin="anonymous"></script>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Poppins', sans-serif;
      color: #333;
      background-color: #fff;
      scroll-behavior: smooth;
    }

    header {
      background: linear-gradient(to right, #003366, #005599);
      color: white;
      text-align: center;
      padding: 80px 20px;
      animation: fadeIn 1s ease-in;
    }
    header h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }
    header p {
      font-size: 1.2em;
      opacity: 0.9;
    }

    nav {
      background-color: #002244;
      padding: 10px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 10;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: #00aaff;
    }

    section {
      padding: 60px 20px;
      max-width: 1200px;
      margin: auto;
    }

    h2 {
      text-align: center;
      margin-bottom: 40px;
      font-size: 2em;
    }

    .services, .projects {
      display: flex;
      flex-wrap: wrap;
      gap: 30px;
      justify-content: center;
    }

    .card {
      background: #f9f9f9;
      border-radius: 10px;
      padding: 30px;
      flex: 1 1 300px;
      text-align: center;
      box-shadow: 0 4px 12px rgba(0,0,0,0.05);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 18px rgba(0,0,0,0.1);
    }

    .card i {
      font-size: 40px;
      margin-bottom: 15px;
      color: #005599;
    }

    form {
      max-width: 600px;
      margin: auto;
    }
    input, textarea {
      width: 100%;
      padding: 12px;
      margin-top: 15px;
      border: 1px solid #ccc;
      border-radius: 6px;
    }
    button {
      background-color: #005599;
      color: white;
      border: none;
      padding: 12px 25px;
      margin-top: 20px;
      border-radius: 6px;
      cursor: pointer;
      transition: background 0.3s;
    }
    button:hover {
      background-color: #003366;
    }

    footer {
      background-color: #002244;
      color: white;
      text-align: center;
      padding: 30px;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 1.8em;
      }
      .card {
        flex: 1 1 100%;
      }
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

<header>
  <h1>E&L Ingenieros y Consultores</h1>
  <p>Soluciones técnicas para un mundo más eficiente</p>
</header>

<nav>
  <a href="#nosotros">Nosotros</a>
  <a href="#servicios">Servicios</a>
  <a href="#proyectos">Proyectos</a>
  <a href="#contacto">Contacto</a>
</nav>

<section id="nosotros">
  <h2>¿Quiénes somos?</h2>
  <p style="text-align: center; max-width: 800px; margin: auto;">Somos una empresa dedicada a la ingeniería y consultoría técnica, comprometida con la innovación, la sostenibilidad y la excelencia en cada uno de nuestros proyectos. Nuestro equipo está formado por profesionales altamente capacitados en distintas ramas de la ingeniería.</p>
</section>

<section id="servicios">
  <h2>Servicios</h2>
  <div class="services">
    <div class="card">
      <i class="fas fa-hard-hat"></i>
      <h3>Consultoría de Ingeniería</h3>
      <p>Evaluación, planificación y soluciones integrales para proyectos civiles, eléctricos y ambientales.</p>
    </div>
    <div class="card">
      <i class="fas fa-project-diagram"></i>
      <h3>Gestión de Proyectos</h3>
      <p>Implementamos metodologías eficientes para la ejecución y control de proyectos en tiempo y forma.</p>
    </div>
    <div class="card">
      <i class="fas fa-drafting-compass"></i>
      <h3>Estudios Técnicos</h3>
      <p>Realizamos estudios especializados en geotecnia, estructuras, hidrología, y más.</p>
    </div>
  </div>
</section>

<section id="proyectos">
  <h2>Proyectos Destacados</h2>
  <div class="projects">
    <div class="card">
      <h4>Autopista Central</h4>
      <p>Supervisión y control de calidad de 50 km de infraestructura vial de alto tráfico.</p>
    </div>
    <div class="card">
      <h4>Parque Solar El Sol</h4>
      <p>Diseño estructural y asesoría técnica para una planta solar de 100 MW.</p>
    </div>
  </div>
</section>

<section id="contacto">
  <h2>Contáctanos</h2>
  <form>
    <input type="text" placeholder="Nombre completo" required>
    <input type="email" placeholder="Correo electrónico" required>
    <textarea placeholder="Escribe tu mensaje..." rows="5" required></textarea>
    <button type="submit">Enviar</button>
  </form>
</section>

<footer>
  <p>&copy; 2025 E&L Ingenieros y Consultores. Todos los derechos reservados.</p>
</footer>

</body>
</html>
