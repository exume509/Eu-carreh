<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>EU CARREH - Accueil</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="logo">EU CARREH</div>
    <nav>
      <ul>
        <li><a href="index.html">Accueil</a></li>
        <li><a href="about.html">À propos</a></li>
        <li><a href="services.html">Services</a></li>
  
        <li><a href="contact.html">Contact</a></li>
        <li><a href="cart.html">Panier</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h1>Bienvenue chez EU CARREH</h1>
    <p>Votre boutique en ligne de confiance</p>
  </section>

  <section class="products">
    <h2>Produits en vedette</h2>
    <div class="product-grid">
      <div class="product">
        <img src="img/produit1.jpg" alt="Produit 1">
        <h3>Produit 1</h3>
        <p>€29.99</p>
        <button onclick="addToCart('Produit 1', 29.99)">Ajouter au panier</button>
      </div>
      <div class="product">
        <img src="img/produit2.jpg" alt="Produit 2">
        <h3>Produit 2</h3>
        <p>€49.99</p>
        <button onclick="addToCart('Produit 2', 49.99)">Ajouter au panier</button>
      </div>
      <!-- Ajoutez plus de produits ici -->
    </div>
  </section>

  <footer>
    <p>&copy; 2025 EU CARREH. Tous droits réservés.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
