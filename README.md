# figma.1
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>M_in_X.Tech - Digital Store</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #0e1525;
      color: #fff;
    }
    header {
      background: #121a2e;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .logo {
      font-size: 1.5em;
      color: #00d8ff;
      font-weight: bold;
    }
    nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #00d8ff;
      font-weight: bold;
    }
    .hero {
      text-align: center;
      padding: 60px 20px 30px;
    }
    .hero h1 {
      font-size: 2.5em;
    }
    #current-time {
      font-size: 1.1em;
      color: #f0c674;
      margin-top: 10px;
    }
    .products {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 30px;
[7/28, 4:13 PM] AI: padding: 40px 20px;
    }
    .product {
      background: #1a233a;
      padding: 20px;
      border-radius: 10px;
      width: 260px;
      text-align: center;
      box-shadow: 0 0 10px #00000050;
    }
    .product h3 {
      color: #00d8ff;
    }
    .product p {
      color: #ccc;
      font-size: 0.9em;
    }
    .price {
      color: #f0c674;
      margin: 10px 0;
      font-size: 1.1em;
    }
    .btn {
      padding: 10px 20px;
      background: #00d8ff;
      color: #000;
      font-weight: bold;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .btn:hover {
      background: #f0c674;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #121a2e;
      font-size: 0.8em;
      color: #999;
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">M_in_X.Tech</div>
    <nav>
      <a href="#">Home</a>
      <a href="#">Products</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Smarter Digital Solutions</h1>
    <div id="current-time"></div>
  </section>

  <section class="products">
    <div class="product">
      <h3>AI Logo Pack</h3>
      <p>High-res logos for your brand, instantly downloadable.</p>
      <div class="price">$9.99</div>
[7/28, 4:13 PM] AI: <button class="btn">Pay Now</button>
    </div>
    <div class="product">
      <h3>Cybersecurity eBook</h3>
      <p>Learn ethical hacking with our beginner-to-pro PDF guide.</p>
      <div class="price">14.99</div>
      <button class="btn">Pay Now</button>
    </div>
    <div class="product">
      <h3>React Starter Kit</h3>
      <p>Launch apps fast with a pre-built, customizable React boilerplate.</p>
      <div class="price">$19.99</div>
      <button class="btn">Pay Now</button>
    </div>
  </section>

  <footer>
    &copy; 2025 M_in_X.Tech | All rights reserved.
  </footer>

  <script>
    function updateTime() {
      const now = new Date();
      const options = { 
        hour: '2-digit', minute: '2-digit', second: '2-digit',
        hour12: true,
        timeZoneName: 'short'
      };
      const timeString = now.toLocaleTimeString('en-US', options);
      document.getElementById('current-time').textContent = "Current Time: " + timeString;
    }
    updateTime();
    setInterval(updateTime, 1000);
  </script>

</body>
</html>
```
