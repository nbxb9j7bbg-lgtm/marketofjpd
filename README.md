# marketofjpd
purchase-sale
<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Market of JPD</title>
  <style>
    body {
      margin: 0;
      font-family: "Poppins", Arial, sans-serif;
      background-color: #1b1a17;
      color: #f5f5f5;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    header {
      width: 100%;
      background-color: #2b2a27;
      text-align: center;
      padding: 20px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.5);
    }
    header h1 {
      color: #d4b483;
      margin: 0;
      font-size: 2em;
    }
    header p {
      color: #aaa;
      margin-top: 5px;
    }
    main {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 20px;
      width: 90%;
      max-width: 1200px;
      margin: 40px 0;
    }
    .item {
      background-color: #2b2a27;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 3px 10px rgba(0,0,0,0.4);
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .item:hover {
      transform: translateY(-5px);
      box-shadow: 0 5px 15px rgba(0,0,0,0.6);
    }
    .item img {
      width: 100%;
      height: 220px;
      object-fit: cover;
    }
    .info {
      padding: 15px;
    }
    .info h2 {
      color: #d4b483;
      font-size: 1.2em;
      margin: 0;
    }
    .info p {
      color: #ccc;
      font-size: 0.95em;
      margin: 10px 0;
    }
    .price {
      color: #8fcf97;
      font-weight: bold;
      margin-bottom: 10px;
    }
    button {
      background-color: #d4b483;
      color: #1b1a17;
      font-weight: bold;
      border: none;
      padding: 10px 15px;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s;
    }
    button:hover {
      background-color: #c09a67;
    }
    footer {
      text-align: center;
      padding: 20px;
      color: #777;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Market of JPD</h1>
    <p>Ankauf & Verkauf – Einfach. Stilvoll. Persönlich.</p>
  </header>

  <main>
    <div class="item">
      <img src="laptop.jpg" alt="Laptop">
      <div class="info">
        <h2>HP Laptop</h2>
        <p>Gepflegter Laptop, ideal zum Arbeiten oder Surfen.</p>
        <p class="price">150 €</p>
        <button>Kontakt aufnehmen</button>
      </div>
    </div>

    <div class="item">
      <img src="jacket.jpg" alt="Jacke">
      <div class="info">
        <h2>Lederjacke</h2>
        <p>Kaum getragen, klassischer Schnitt.</p>
        <p class="price">60 €</p>
        <button>Kontakt aufnehmen</button>
      </div>
    </div>

    <div class="item">
      <img src="phone.jpg" alt="Smartphone">
      <div class="info">
        <h2>Smartphone</h2>
        <p>Funktioniert einwandfrei, Display ohne Kratzer.</p>
        <p class="price">100 €</p>
        <button>Kontakt aufnehmen</button>
      </div>
    </div>
  </main>

  <footer>
    &copy; 2024 Market of JPD – Dein Marktplatz für Lieblingsstücke.
  </footer>
</body>
</html>