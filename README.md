<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Kickback Store</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
    }
    header {
      background: #111;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    nav {
      background: #222;
      display: flex;
      justify-content: center;
      padding: 10px;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 40px;
      text-align: center;
    }
    h2 {
      margin-bottom: 20px;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .product {
      background: #fff;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .product img {
      max-width: 100%;
      border-radius: 8px;
    }
    .btn {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 15px;
      background: #111;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
      transition: 0.3s;
    }
    .btn:hover {
      background: #444;
    }
    footer {
      background: #111;
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
    footer a {
      color: #ffcc00;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Kickback Store</h1>
    <p>Kapde 👕 | Jute 👟</p>
  </header>  <nav>
    