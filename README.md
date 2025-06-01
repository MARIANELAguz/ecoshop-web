<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>EcoShop - Cuidado Personal Ecológico</title>
  <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@600&family=Quicksand:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --verde-principal: #2ecc71;
      --verde-oscuro: #27ae60;
      --coral: #ff7f50;
      --blanco: #ffffff;
      --gris-suave: #f9f9f9;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: 'Quicksand', sans-serif;
      background-color: var(--gris-suave);
      color: #333;
      animation: fadeIn 1s ease-in;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    header {
      background: linear-gradient(90deg, var(--verde-principal), var(--coral));
      color: var(--blanco);
      padding: 30px 20px;
      text-align: center;
    }

    header h1 {
      font-family: 'Dancing Script', cursive;
      font-size: 3.5em;
      margin: 0;
      animation: bounceIn 1s ease-in-out;
    }

    @keyframes bounceIn {
      0%   { transform: scale(0.9); opacity: 0; }
      60%  { transform: scale(1.05); opacity: 1; }
      100% { transform: scale(1); }
    }

    header p {
      margin-top: 10px;
      font-size: 1.2em;
      font-weight: 400;
      animation: fadeIn 1.5s ease-in;
    }

    nav {
      margin-top: 20px;
      animation: fadeIn 2s ease-in;
    }

    nav a {
      background-color: var(--blanco);
      color: var(--verde-oscuro);
      padding: 10px 20px;
      margin: 5px;
      text-decoration: none;
      border-radius: 30px;
      font-weight: bold;
      display: inline-block;
      transition: all 0.3s ease;
    }

    nav a:hover {
      background-color: var(--verde-oscuro);
      color: var(--blanco);
    }

    main {
      padding: 50px 20px;
      text-align: center;
      animation: fadeIn 2s ease-in;
    }

    main h2 {
      color: var(--verde-oscuro);
      font-size: 2.2em;
      margin-bottom: 20px;
      font-family: 'Dancing Script', cursive;
    }

    main p {
      font-size: 1.1em;
      max-width: 700px;
      margin: 0 auto;
      color: #555;
      line-height: 1.6;
    }

    footer {
      background-color: var(--verde-principal);
      color: var(--blanco);
      text-align: center;
      padding: 20px;
      margin-top: 50px;
      font-size: 0.9em;
      animation: fadeIn 3s ease-in;
    }
  </style>
</head>
<body>
  <header>
    <h1>EcoShop 🌿</h1>
    <p>Tu tienda de cuidado personal ecológico y lleno de vida</p>
    <nav>
      <a href="index.html">Inicio</a>
      <a href="productos.html">Productos</a>
      <a href="acerca.html">Nosotros</a>
      <a href="contacto.html">Contacto</a>
    </nav>
  </header>

  <main>
    <h2>Bienvenid@ a EcoShop</h2>
    <p>
      Aquí encuentras productos naturales, amigables con el medio ambiente y llenos de energía positiva. 
      Transforma tu cuidado personal en una experiencia ecológica con estilo.
    </p>
  </main>

  <footer>
    <p>&copy; 2025 EcoShop - Todos los derechos reservados 🌱</p>
  </footer>
</body>
</html>
