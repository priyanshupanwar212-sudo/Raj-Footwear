<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Raj Footwear</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f8f8f8;
      color: #333;
    }
    header {
      background: linear-gradient(45deg, #ff5f6d, #ffc371);
      color: white;
      padding: 2rem;
      text-align: center;
    }
    header h1 {
      font-size: 3rem;
      margin: 0;
      animation: slideIn 2s ease;
    }
    header p {
      font-size: 1.2rem;
      margin-top: 0.5rem;
    }
    nav {
      display: flex;
      justify-content: center;
      background: #222;
    }
    nav a {
      color: white;
      text-decoration: none;
      padding: 1rem;
      display: block;
    }
    nav a:hover {
      background: #444;
    }
    section {
      padding: 3rem 2rem;
      text-align: center;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .card {
      background: white;
      border-radius: 15px;
      padding: 1rem;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
    .card:hover {
      transform: scale(1.05);
    }
    .card img {
      max-width: 100%;
      border-radius: 10px;
    }
    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 2rem;
    }
    @keyframes slideIn {
      from { transform: translateY(-50px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
  </style>
</head>
<body>
  <header>
    <h1>Raj Footwear</h1>
    <p>Quality Footwear for Everyone</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Us</h2>
    <p>Welcome to <strong>Raj Footwear</strong>, owned by <strong>Mr. Chain Singh Panwar</strong>. We provide stylish and comfortable footwear for all age groups. Our mission is to deliver the best quality at affordable prices.</p>
  </section>

  <section id="products">
    <h2>Our Products</h2>
    <div class="products">
      <div class="card">
        <img src="https://via.placeholder.com/300x200.png?text=Shoes" alt="Shoes">
        <h3>Stylish Shoes</h3>
        <p>Trendy and comfortable shoes for daily wear.</p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/300x200.png?text=Sandals" alt="Sandals">
        <h3>Comfort Sandals</h3>
        <p>Perfect sandals for summer comfort.</p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/300x200.png?text=Slippers" alt="Slippers">
        <h3>Casual Slippers</h3>
        <p>Lightweight slippers for everyday use.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p><strong>Owner:</strong> Mr. Chain Singh Panwar</p>
    <p><strong>Mobile:</strong> 9897847105</p>
    <p><strong>Shop Address:</strong> [Add your shop address here]</p>
  </section>

  <footer>
    <p>&copy; 2025 Raj Footwear. All rights reserved.</p>
  </footer>
</body>
</html>
