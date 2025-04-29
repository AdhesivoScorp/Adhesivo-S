<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Adhesivo'S</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 40px;
      background-color: #ffffff; /* Fondo blanco */
      color: #333333; /* Texto gris oscuro */
    }

    header {
      background-color: #002F6C; /* Azul oscuro */
      color: white;
      padding: 10px;
      text-align: center;
    }

    header img {
      height: 200px;
      vertical-align: middle;
      margin-right: 130px;
    }

    header h1 {
      display: inline-block;
      vertical-align: middle;
      margin: 0;
    }

    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      margin-top: 20px;
    }

    .product {
      background-color: #f9f9f9;
      border: 2px solid #FF0000; /* Borde rojo */
      border-radius: 10px;
      padding: 20px;
      width: 250px;
      text-align: center;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .product:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
    }

    .product img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 8px;
      margin-bottom: 10px;
    }

    footer {
      margin-top: 50px;
      text-align: center;
      font-size: 14px;
      color: #666666;
    }

    .contact-info {
      margin-top: 30px;
      text-align: center;
    }

    .contact-info a {
      display: inline-block;
      margin: 5px;
      text-decoration: none;
      color: #002F6C; /* Azul fuerte */
      font-weight: bold;
      border: 1px solid #002F6C;
      padding: 8px 12px;
      border-radius: 5px;
      transition: background-color 0.3s, color 0.3s;
    }

    .contact-info a:hover {
      background-color: #002F6C;
      color: white;
    }
  </style>
</head>
<body>

<header>
  <img src="adhesivos.jpg" alt="Logo Adhesivo'S">
  <h1></h1>
</header>

<section class="products">
  <div class="product">
    <img src="kongtape.jpg" alt="Cinta de empaque transparente Kong tape">
    <h2>Cinta de empaque transparente Kong tape 48 mm X 150 m</h2>
    <p>Categoría: Uso convencional</p>
  </div>

  <div class="product">
    <img src="adhesivos.jpg" alt="Cinta de empaque PVC Tape Bear">
    <h2>Cinta de empaque PVC Tape Bear 48 mm X 150 m</h2>
    <p>Categoría: Uso industrial</p>
  </div>

  <div class="product">
    <img src="adhesivos.jpg" alt="Cinta kinesiológica">
    <h2>Cinta kinesiológica 48 mm X 5 m</h2>
    <p>Categoría: Uso deportivo</p>
  </div>

  <div class="product">
    <img src="adhesivos.jpg" alt="Cinta doble capa Nano tape">
    <h2>Cinta doble capa Nano tape 12 mm X 5 m</h2>
    <p>Categoría: Uso comercial</p>
  </div>

  <div class="product">
    <img src="adhesivos.jpg" alt="Cinta Ducto gris Adhes tape">
    <h2>Cinta Ducto gris Adhes tape Reforzada</h2>
    <p>Categoría: Uso industrial</p>
  </div>
</section>

<section class="contact-info">
  <h2>Contacto</h2>
  <a href="https://wa.me/5215619025655" target="_blank">WhatsApp</a>
  <a href="https://www.facebook.com/profile.php?id=100083484102582" target="_blank">Facebook</a>
  <a href="mailto:AdhesivoScorp@outlook.com">Correo Electrónico</a>
</section>

<footer>
  <p>&copy; 2025 Adhesivo'S. Todos los derechos reservados.</p>
</footer>

</body>
</html>
