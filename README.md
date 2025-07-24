# catalogo-izzi.html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Catálogo de Productos - Izzi</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
    }

    header {
      background-color: #800080;
      color: white;
      padding: 1em;
      text-align: center;
    }

    .container {
      padding: 2em;
    }

    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5em;
    }

    .product-card {
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: transform 0.2s;
    }

    .product-card:hover {
      transform: scale(1.02);
    }

    .product-image img {
      width: 100%;
      height: 160px;
      object-fit: cover;
    }

    .product-info {
      padding: 1em;
    }

    .product-info h3 {
      margin: 0.5em 0;
      color: #333;
    }

    .product-info p {
      font-size: 0.9em;
      color: #555;
    }

    .product-price {
      color: #800080;
      font-weight: bold;
      margin-top: 0.5em;
    }
  </style>
</head>
<body>

  <header>
    <h1>Catálogo de Productos Izzi</h1>
    <p>Internet, Telefonía, Televisión y más</p>
  </header>

  <div class="container">
    <div class="product-grid">

      <div class="product-card">
        <div class="product-image">
          <img src="https://via.placeholder.com/400x200?text=Paquete+Internet+100Mbps" alt="Internet 100Mbps">
        </div>
        <div class="product-info">
          <h3>Internet 100 Mbps</h3>
          <p>Velocidad ideal para streaming y navegación en casa.</p>
          <div class="product-price">$400/mes</div>
        </div>
      </div>

      <div class="product-card">
        <div class="product-image">
          <img src="https://via.placeholder.com/400x200?text=Paquete+Tripleplay" alt="Tripleplay">
        </div>
        <div class="product-info">
          <h3>Paquete Tripleplay</h3>
          <p>Incluye Internet, TV y Telefonía ilimitada.</p>
          <div class="product-price">$690/mes</div>
        </div>
      </div>

      <div class="product-card">
        <div class="product-image">
          <img src="https://via.placeholder.com/400x200?text=TV+HD+Izzi" alt="Televisión HD">
        </div>
        <div class="product-info">
          <h3>TV HD Izzi</h3>
          <p>Más de 60 canales en alta definición.</p>
          <div class="product-price">$250/mes</div>
        </div>
      </div>

    </div>
  </div>

</body>
</html>
5518856466
