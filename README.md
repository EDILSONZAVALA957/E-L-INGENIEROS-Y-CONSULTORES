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
  <h1>E&L Ingenieros
