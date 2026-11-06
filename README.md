# Slivia.in

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Discover elegant women's handbags, crossbody bags, sling bags and shoulder bags at SLIVIA.">
  <title>SLIVIA | Luxury Women's Handbags</title>
  <link rel="stylesheet" href="style.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Playfair+Display:wght@400;500;600;700&display=swap" rel="stylesheet">
</head>
<body>

  <div class="announcement">
    ✨ Welcome to SLIVIA – Elegance in Every Carry
  </div>

  <header class="header">
    <a href="#" class="logo">SLIVIA<span>.</span></a>

    <button class="menu-toggle" id="menuToggle" aria-label="Open menu">☰</button>

    <nav class="nav" id="nav">
      <a href="#home">Home</a>
      <a href="#shop">Shop</a>
      <a href="#categories">Collections</a>
      <a href="#about">Our Story</a>
      <a href="#contact">Contact</a>
    </nav>

    <button class="cart-button" id="cartButton">
      Bag <span id="cartCount">0</span>
    </button>
  </header>

  <main>
    <section class="hero" id="home">
      <div class="hero-content">
        <span class="eyebrow">THE NEW COLLECTION</span>
        <h1>Carry Your<br><em>Elegance.</em></h1>
        <p>Discover handbags that complement your style, celebrate your confidence and make every moment special.</p>
        <a href="#shop" class="primary-button">EXPLORE COLLECTION →</a>
      </div>
      <div class="hero-image">
        <img src="https://images.unsplash.com/photo-1584917865442-de89df76afd3?auto=format&fit=crop&w=1000&q=85" alt="Elegant women's handbag">
      </div>
    </section>

    <section class="benefits">
      <div>✦ Carefully Curated Styles</div>
      <div>✦ Everyday Elegance</div>
      <div>✦ Style That Speaks</div>
    </section>

    <section class="section categories" id="categories">
      <div class="section-heading">
        <span class="eyebrow">FIND YOUR STYLE</span>
        <h2>Shop by Collection</h2>
        <p>Something beautiful for every occasion.</p>
      </div>

      <div class="category-grid">
        <button class="category-card" data-category="Crossbody">
          <img src="https://images.unsplash.com/photo-1590874103328-eac38a683ce7?auto=format&fit=crop&w=600&q=80" alt="Crossbody bags">
          <span>Crossbody Bags</span>
        </button>
        <button class="category-card" data-category="Sling">
          <img src="https://images.unsplash.com/photo-1566150905458-1bf1fc113f0d?auto=format&fit=crop&w=600&q=80" alt="Sling bags">
          <span>Sling Bags</span>
        </button>
        <button class="category-card" data-category="Shoulder">
          <img src="https://images.unsplash.com/photo-1584917865442-de89df76afd3?auto=format&fit=crop&w=600&q=80" alt="Shoulder bags">
          <span>Shoulder Bags</span>
        </button>
        <button class="category-card" data-category="Tote">
          <img src="https://images.unsplash.com/photo-1591561954557-26941169b49e?auto=format&fit=crop&w=600&q=80" alt="Tote bags">
          <span>Tote Bags</span>
        </button>
      </div>
    </section>

    <section class="section shop" id="shop">
      <div class="section-heading">
        <span class="eyebrow">THE SLIVIA EDIT</span>
        <h2>Our Handbag Collection</h2>
        <p>Find the perfect companion for your everyday style.</p>
      </div>

      <div class="shop-controls">
        <input id="searchInput" type="search" placeholder="Search handbags..." aria-label="Search products">
        <select id="categoryFilter" aria-label="Filter by category">
          <option value="All">All Collections</option>
          <option value="Crossbody">Crossbody</option>
          <option value="Sling">Sling</option>
          <option value="Shoulder">Shoulder</option>
          <option value="Tote">Tote</option>
        </select>
      </div>

      <div class="product-grid" id="productGrid"></div>
    </section>

    <section class="promo">
      <div>
        <span class="eyebrow">MADE FOR YOUR MOMENTS</span>
        <h2>A Little Luxury,<br>Every Single Day.</h2>
        <p>Because your everyday style deserves something special.</p>
        <a href="#shop" class="light-button">SHOP THE COLLECTION →</a>
      </div>
      <img src="https://images.unsplash.com/photo-1548036328-c9fa89d128fa?auto=format&fit=crop&w=900&q=85" alt="Luxury handbag collection">
    </section>

    <section class="section about" id="about">
      <span class="eyebrow">OUR STORY</span>
      <h2>Style is personal.<br><em>Make it yours.</em></h2>
      <p>At SLIVIA, we believe a handbag is more than an accessory. It is a reflection of your personality, confidence and everyday journey. Our collection brings together versatile styles for women who love to express themselves.</p>
    </section>

    <section class="newsletter">
      <h2>Stay in Style</h2>
      <p>Follow SLIVIA for new arrivals, collections and fashion inspiration.</p>
      <a href="https://www.instagram.com/" target="_blank" rel="noopener" class="primary-button">FOLLOW ON INSTAGRAM</a>
    </section>
  </main>

  <footer id="contact">
    <a href="#" class="logo">SLIVIA<span>.</span></a>
    <p>Elegance in Every Carry.</p>
    <div class="footer-links">
      <a href="#shop">Shop</a>
      <a href="#about">About Us</a>
      <a href="https://www.instagram.com/" target="_blank" rel="noopener">Instagram</a>
    </div>
    <p>Contact: <a id="footerWhatsApp" href="#">WhatsApp Us</a></p>
    <small>© <span id="year"></span> SLIVIA. All rights reserved.</small>
  </footer>

  <!-- Shopping cart drawer -->
  <div class="cart-overlay" id="cartOverlay"></div>
  <aside class="cart-drawer" id="cartDrawer" aria-label="Shopping cart">
    <div class="cart-header">
      <h2>Your Shopping Bag</h2>
      <button id="closeCart" aria-label="Close cart">✕</button>
    </div>
    <div id="cartItems" class="cart-items"></div>
    <div class="cart-bottom">
      <div class="cart-total">
        <strong>Total</strong>
        <strong id="cartTotal">₹0</strong>
      </div>
      <button class="primary-button checkout-button" id="checkoutButton">ORDER ON WHATSAPP</button>
      <p class="cart-note">Final availability and delivery details will be confirmed on WhatsApp.</p>
    </div>
  </aside>

  <script src="script.js"></script>
</body>
</html>
:root {
  --pink: #d98ca8;
  --pink-dark: #a95375;
  --blush: #f8e9ed;
  --cream: #fffaf6;
  --beige: #e9d9ce;
  --text: #352b2d;
  --muted: #827477;
  --white: #ffffff;
  --serif: "Playfair Display", Georgia, serif;
  --sans: "DM Sans", Arial, sans-serif;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
  scroll-padding-top: 90px;
}

body {
  font-family: var(--sans);
  color: var(--text);
  background: var(--cream);
  line-height: 1.6;
}

a {
  color: inherit;
  text-decoration: none;
}

button, input, select {
  font: inherit;
}

button {
  cursor: pointer;
}

.announcement {
  background: var(--pink-dark);
  color: white;
  text-align: center;
  padding: 9px;
  font-size: 12px;
  letter-spacing: 1px;
}

.header {
  height: 78px;
  padding: 0 7%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  background: white;
  position: sticky;
  top: 0;
  z-index: 20;
  box-shadow: 0 2px 15px #00000008;
}

.logo {
  font-family: var(--serif);
  font-size: 31px;
  font-weight: 700;
  letter-spacing: 3px;
}

.logo span {
  color: var(--pink);
}

.nav {
  display: flex;
  gap: 30px;
  align-items: center;
}

.nav a {
  font-size: 13px;
  transition: color .2s;
}

.nav a:hover {
  color: var(--pink-dark);
}

.cart-button {
  background: var(--blush);
  border: none;
  border-radius: 30px;
  padding: 11px 18px;
  font-size: 13px;
}

#cartCount {
  background: var(--pink-dark);
  color: white;
  border-radius: 50%;
  padding: 3px 7px;
  margin-left: 5px;
}

.menu-toggle {
  display: none;
  border: 0;
  background: none;
  font-size: 25px;
}

.hero {
  min-height: 590px;
  display: grid;
  grid-template-columns: 1fr 1fr;
  background: var(--blush);
  padding: 55px 8%;
  align-items: center;
  gap: 45px;
}

.hero-content {
  max-width: 520px;
}

.eyebrow {
  font-size: 11px;
  color: var(--pink-dark);
  font-weight: 700;
  letter-spacing: 3px;
}

h1, h2 {
  font-family: var(--serif);
  font-weight: 500;
  line-height: 1.15;
}

.hero h1 {
  font-size: clamp(48px, 6vw, 76px);
  margin: 18px 0;
}

.hero h1 em, .about h2 em {
  color: var(--pink-dark);
  font-weight: 400;
}

.hero-content p {
  max-width: 430px;
  color: var(--muted);
  margin-bottom: 30px;
}

.hero-image {
  height: 480px;
  overflow: hidden;
  border-radius: 180px 180px 8px 8px;
}

.hero-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.primary-button, .light-button {
  display: inline-block;
  background: var(--pink-dark);
  color: white;
  padding: 15px 25px;
  border: 0;
  font-size: 11px;
  letter-spacing: 1.4px;
  font-weight: 700;
  transition: .25s;
}

.primary-button:hover {
  background: var(--text);
  transform: translateY(-2px);
}

.benefits {
  display: flex;
  justify-content: space-around;
  gap: 15px;
  flex-wrap: wrap;
  padding: 24px 5%;
  background: white;
  font-size: 12px;
  color: var(--pink-dark);
  letter-spacing: .5px;
}

.section {
  padding: 90px 8%;
}

.section-heading {
  text-align: center;
  margin-bottom: 42px;
}

.section-heading h2 {
  font-size: 38px;
  margin: 12px 0;
}

.section-heading p {
  color: var(--muted);
  font-size: 14px;
}

.category-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 20px;
}

.category-card {
  background: white;
  border: 0;
  text-align: center;
  padding-bottom: 18px;
  overflow: hidden;
  color: var(--text);
  font-family: var(--serif);
  font-size: 19px;
}

.category-card img {
  width: 100%;
  aspect-ratio: 4/5;
  object-fit: cover;
  display: block;
  margin-bottom: 15px;
  transition: transform .4s;
}

.category-card:hover img {
  transform: scale(1.04);
}

.shop {
  background: #fff3f5;
}

.shop-controls {
  display: flex;
  justify-content: center;
  gap: 12px;
  margin-bottom: 35px;
}

.shop-controls input,
.shop-controls select {
  background: white;
  border: 1px solid #ead7dd;
  padding: 13px 16px;
  border-radius: 4px;
  outline: none;
  min-width: 220px;
}

.shop-controls input:focus,
.shop-controls select:focus {
  border-color: var(--pink-dark);
}

.product-grid {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 25px 18px;
}

.product-card {
  background: white;
  overflow: hidden;
  border-radius: 5px;
}

.product-image {
  width: 100%;
  aspect-ratio: 4/4.5;
  object-fit: cover;
  display: block;
  background: var(--blush);
}

.product-info {
  padding: 15px;
}

.product-category {
  color: var(--pink-dark);
  text-transform: uppercase;
  font-size: 10px;
  letter-spacing: 1.5px;
}

.product-info h3 {
  font-family: var(--serif);
  font-size: 18px;
  font-weight: 500;
  margin: 5px 0;
}

.product-price {
  font-weight: 700;
  font-size: 14px;
  margin: 8px 0 14px;
}

.old-price {
  color: #999;
  font-weight: 400;
  text-decoration: line-through;
  margin-left: 7px;
  font-size: 12px;
}

.add-button {
  background: transparent;
  color: var(--pink-dark);
  border: 1px solid var(--pink);
  padding: 10px;
  width: 100%;
  font-size: 11px;
  letter-spacing: 1px;
  transition: .2s;
}

.add-button:hover {
  background: var(--pink-dark);
  color: white;
}

.promo {
  background: #e8d8cf;
  padding: 75px 9%;
  display: grid;
  grid-template-columns: 1fr 1fr;
  align-items: center;
  gap: 50px;
}

.promo h2 {
  font-size: 44px;
  margin: 15px 0;
}

.promo p {
  color: #655b57;
  margin-bottom: 25px;
}

.promo img {
  width: 100%;
  max-height: 430px;
  object-fit: cover;
}

.light-button {
  background: var(--text);
}

.about {
  text-align: center;
  max-width: 900px;
  margin: auto;
}

.about h2 {
  font-size: 44px;
  margin: 15px 0;
}

.about p {
  max-width: 650px;
  margin: auto;
  color: var(--muted);
}

.newsletter {
  background: var(--blush);
  padding: 70px 20px;
  text-align: center;
}

.newsletter h2 {
  font-size: 38px;
  margin-bottom: 10px;
}

.newsletter p {
  color: var(--muted);
  margin-bottom: 25px;
}

footer {
  background: #302629;
  color: white;
  text-align: center;
  padding: 55px 20px;
}

footer .logo {
  display: inline-block;
}

footer .logo span {
  color: var(--pink);
}

footer p {
  color: #d7c6cb;
  font-size: 13px;
  margin: 12px 0;
}

.footer-links {
  display: flex;
  justify-content: center;
  gap: 25px;
  margin: 20px;
  font-size: 13px;
}

footer small {
  color: #c9b7bc;
  font-size: 11px;
}

.cart-overlay {
  position: fixed;
  inset: 0;
  background: #0008;
  z-index: 40;
  display: none;
}

.cart-overlay.open {
  display: block;
}

.cart-drawer {
  position: fixed;
  z-index: 41;
  right: -440px;
  top: 0;
  width: min(420px, 100%);
  height: 100%;
  background: white;
  padding: 24px;
  display: flex;
  flex-direction: column;
  transition: right .3s;
}

.cart-drawer.open {
  right: 0;
}

.cart-header, .cart-total {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.cart-header h2 {
  font-size: 23px;
}

.cart-header button {
  background: none;
  border: 0;
  font-size: 22px;
}

.cart-items {
  flex: 1;
  overflow-y: auto;
  margin-top: 25px;
}

.cart-item {
  display: flex;
  gap: 12px;
  align-items: center;
  border-bottom: 1px solid #eee;
  padding: 13px 0;
}

.cart-item img {
  width: 65px;
  height: 75px;
  object-fit: cover;
}

.cart-item-info {
  flex: 1;
}

.cart-item-info h4 {
  font-family: var(--serif);
}

.cart-item-info p {
  color: var(--pink-dark);
  font-size: 13px;
}

.remove-item {
  background: none;
  border: 0;
  color: #9a777f;
}

.cart-bottom {
  padding-top: 20px;
  border-top: 1px solid #eee;
}

.cart-total {
  margin-bottom: 20px;
}

.checkout-button {
  width: 100%;
}

.cart-note {
  font-size: 11px;
  color: var(--muted);
  text-align: center;
  margin-top: 12px;
}

.empty-cart {
  color: var(--muted);
  text-align: center;
  padding: 35px 0;
}

@media(max-width: 900px) {
  .product-grid {
    grid-template-columns: repeat(3, 1fr);
  }
  .category-grid {
    grid-template-columns: repeat(2, 1fr);
  }
  .hero {
    padding: 45px 5%;
  }
}

@media(max-width: 600px) {
  .header {
    height: 65px;
    padding: 0 5%;
  }

  .logo {
    font-size: 25px;
  }

  .menu-toggle {
    display: block;
    order: 3;
  }

  .cart-button {
    order: 2;
    padding: 9px 12px;
  }

  .nav {
    display: none;
    position: absolute;
    top: 65px;
    left: 0;
    right: 0;
    background: white;
    padding: 20px;
    flex-direction: column;
    gap: 18px;
    box-shadow: 0 8px 15px #0001;
  }

  .nav.show {
    display: flex;
  }

  .hero {
    grid-template-columns: 1fr;
    padding: 45px 7%;
    gap: 30px;
  }

  .hero h1 {
    font-size: 53px;
  }

  .hero-image {
    height: 340px;
    border-radius: 130px 130px 5px 5px;
  }

  .benefits {
    flex-direction: column;
    text-align: center;
    gap: 9px;
  }

  .section {
    padding: 65px 5%;
  }

  .section-heading h2 {
    font-size: 30px;
  }

  .category-grid {
    gap: 12px;
  }

  .category-card {
    font-size: 16px;
  }

  .shop-controls {
    flex-direction: column;
  }

  .shop-controls input,
  .shop-controls select {
    width: 100%;
  }

  .product-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 14px 10px;
  }

  .product-info {
    padding: 10px;
  }

  .product-info h3 {
    font-size: 15px;
  }

  .promo {
    grid-template-columns: 1fr;
    padding: 55px 7%;
    gap: 25px;
  }

  .promo h2, .about h2 {
    font-size: 36px;
  }

  .footer-links {
    gap: 15px;
    flex-wrap: wrap;
  }
}
// ===================================
// SLIVIA - PRODUCT SETTINGS
// ===================================

// Replace with your WhatsApp number.
// Use country code, without + or spaces.
const WHATSAPP_NUMBER = "91XXXXXXXXXX";

// Add or edit your handbag products here.
const products = [
  {
    id: 1,
    name: "Classic Black Handbag",
    category: "Shoulder",
    price: 1299,
    mrp: 1799,
    image: "https://images.unsplash.com/photo-1584917865442-de89df76afd3?w=600"
  },
  {
    id: 2,
    name: "Elegant Beige Sling",
    category: "Sling",
    price: 999,
    mrp: 1499,
    image: "https://images.unsplash.com/photo-1590874103328-eac38a683ce7?w=600"
  },
  {
    id: 3,
    name: "Premium Brown Crossbody",
    category: "Crossbody",
    price: 1199,
    mrp: 1599,
    image: "https://images.unsplash.com/photo-1566150905458-1bf1fc113f0d?w=600"
  },
  {
    id: 4,
    name: "Luxury Pink Tote",
    category: "Tote",
    price: 1499,
    mrp: 1999,
    image: "https://images.unsplash.com/photo-1591561954557-26941169b49e?w=600"
  },
  {
    id: 5,
    name: "Everyday Mini Sling",
    category: "Sling",
    price: 799,
    mrp: 1199,
    image: "https://images.unsplash.com/photo-1548036328-c9fa89d128fa?w=600"
  },
  {
    id: 6,
    name: "Chic White Shoulder Bag",
    category: "Shoulder",
    price: 1399,
    mrp: 1899,
    image: "https://images.unsplash.com/photo-1584917865442-de89df76afd3?w=600"
  },
  {
    id: 7,
    name: "Everyday Crossbody",
    category: "Crossbody",
    price: 1099,
    mrp: 1499,
    image: "https://images.unsplash.com/photo-1590874103328-eac38a683ce7?w=600"
  },
  {
    id: 8,
    name: "Modern Office Tote",
    category: "Tote",
    price: 1699,
    mrp: 2199,
    image: "https://images.unsplash.com/photo-1591561954557-26941169b49e?w=600"
  },
  {
    id: 9,
    name: "Golden Chain Sling",
    category: "Sling",
    price: 1199,
    mrp: 1599,
    image: "https://images.unsplash.com/photo-1548036328-c9fa89d128fa?w=600"
  },
  {
    id: 10,
    name: "Elegant Daily Shoulder",
    category: "Shoulder",
    price: 999,
    mrp: 1399,
    image: "https://images.unsplash.com/photo-1566150905458-1bf1fc113f0d?w=600"
  },
  {
    id: 11,
    name: "Minimal Crossbody Bag",
    category: "Crossbody",
    price: 899,
    mrp: 1299,
    image: "https://images.unsplash.com/photo-1590874103328-eac38a683ce7?w=600"
  },
  {
    id: 12,
    name: "Signature Tote Bag",
    category: "Tote",
    price: 1899,
    mrp: 2499,
    image: "https://images.unsplash.com/photo-1584917865442-de89df76afd3?w=600"
  }
];

let cart = [];

// ===================================
// PRODUCT DISPLAY
// ===================================

const productGrid = document.getElementById("productGrid");

function renderProducts(list) {
  productGrid.innerHTML = "";

  if (list.length === 0) {
    productGrid.innerHTML =
      '<p class="empty-cart">No products found.</p>';
    return;
  }

  list.forEach(product => {
    const card = document.createElement("article");
    card.className = "product-card";

    const image = document.createElement("img");
    image.className = "product-image";
    image.src = product.image;
    image.alt = product.name;
    image.loading = "lazy";

    const info = document.createElement("div");
    info.className = "product-info";

    const category = document.createElement("span");
    category.className = "product-category";
    category.textContent = product.category;

    const title = document.createElement("h3");
    title.textContent = product.name;

    const price = document.createElement("p");
    price.className = "product-price";
    price.append(
      document.createTextNode(
        "₹" + product.price.toLocaleString("en-IN")
      )
    );

    const oldPrice = document.createElement("span");
    oldPrice.className = "old-price";
    oldPrice.textContent =
      "₹" + product.mrp.toLocaleString("en-IN");

    price.append(oldPrice);

    const button = document.createElement("button");
    button.className = "add-button";
    button.textContent = "ADD TO BAG";
    button.addEventListener("click", () => addToCart(product.id));

    info.append(category, title, price, button);
    card.append(image, info);
    productGrid.appendChild(card);
  });
}

// ===================================
// SEARCH AND FILTER
// ===================================

const searchInput = document.getElementById("searchInput");
const categoryFilter = document.getElementById("categoryFilter");

function filterProducts() {
  const search = searchInput.value.toLowerCase().trim();
  const category = categoryFilter.value;

  const filtered = products.filter(product => {
    const matchesSearch =
      product.name.toLowerCase().includes(search) ||
      product.category.toLowerCase().includes(search);

    const matchesCategory =
      category === "All" || product.category === category;

    return matchesSearch && matchesCategory;
  });

  renderProducts(filtered);
}

searchInput.addEventListener("input", filterProducts);
categoryFilter.addEventListener("change", filterProducts);

// Category collection buttons
document.querySelectorAll(".category-card").forEach(button => {
  button.addEventListener("click", () => {
    categoryFilter.value = button.dataset.category;
    filterProducts();
    document.getElementById("shop").scrollIntoView({
      behavior: "smooth"
    });
  });
});

// ===================================
// SHOPPING CART
// ===================================

const cartDrawer = document.getElementById("cartDrawer");
const cartOverlay = document.getElementById("cartOverlay");

function addToCart(id) {
  const existing = cart.find(item => item.id === id);

  if (existing) {
    existing.quantity++;
  } else {
    cart.push({ id, quantity: 1 });
  }

  updateCart();
  openCart();
}

function updateCart() {
  const cartItems = document.getElementById("cartItems");
  const cartCount = document.getElementById("cartCount");
  const cartTotal = document.getElementById("cartTotal");

  cartItems.innerHTML = "";

  const totalItems = cart.reduce(
    (sum, item) => sum + item.quantity, 0
  );

  const totalPrice = cart.reduce((sum, item) => {
    const product = products.find(p => p.id === item.id);
    return sum + product.price * item.quantity;
  }, 0);

  cartCount.textContent = totalItems;
  cartTotal.textContent = "₹" + totalPrice.toLocaleString("en-IN");

  if (cart.length === 0) {
    cartItems.innerHTML =
      '<p class="empty-cart">Your shopping bag is empty.</p>';
    return;
  }

  cart.forEach(item => {
    const product = products.find(p => p.id === item.id);

    const row = document.createElement("div");
    row.className = "cart-item";

    const img = document.createElement("img");
    img.src = product.image;
    img.alt = product.name;

    const info = document.createElement("div");
    info.className = "cart-item-info";

    const name = document.createElement("h4");
    name.textContent = product.name;

    const details = document.createElement("p");
    details.textContent =
      "₹" + product.price.toLocaleString("en-IN") +
      " × " + item.quantity;

    info.append(name, details);

    const remove = document.createElement("button");
    remove.className = "remove-item";
    remove.textContent = "Remove";
    remove.addEventListener("click", () => removeFromCart(item.id));

    row.append(img, info, remove);
    cartItems.appendChild(row);
  });
}

function removeFromCart(id) {
  cart = cart.filter(item => item.id !== id);
  updateCart();
}

function openCart() {
  cartDrawer.classList.add("open");
  cartOverlay.classList.add("open");
}

function closeCart() {
  cartDrawer.classList.remove("open");
  cartOverlay.classList.remove("open");
}

document.getElementById("cartButton")
  .addEventListener("click", openCart);

document.getElementById("closeCart")
  .addEventListener("click", closeCart);

cartOverlay.addEventListener("click", closeCart);

// ===================================
// WHATSAPP CHECKOUT
// ===================================

document.getElementById("checkoutButton")
  .addEventListener("click", () => {

    if (cart.length === 0) {
      alert("Your shopping bag is empty!");
      return;
    }

    if (!/^91\d{10}$/.test(WHATSAPP_NUMBER)) {
      alert("Please add your correct WhatsApp number in script.js first.");
      return;
    }

    let message = "Hello SLIVIA! I want to place an order:\n\n";
    let total = 0;

    cart.forEach(item => {
      const product = products.find(p => p.id === item.id);
      const subtotal = product.price * item.quantity;

      message +=
        product.name +
        " × " + item.quantity +
        " = ₹" + subtotal + "\n";

      total += subtotal;
    });

    message +=
      "\nTotal: ₹" + total +
      "\n\nPlease share the order and delivery details.";

    const url =
      "https://wa.me/" + WHATSAPP_NUMBER +
      "?text=" + encodeURIComponent(message);

    window.open(url, "_blank");
  });

// ===================================
// MOBILE MENU
// ===================================

document.getElementById("menuToggle")
  .addEventListener("click", () => {
    document.getElementById("nav").classList.toggle("show");
  });

document.querySelectorAll(".nav a").forEach(link => {
  link.addEventListener("click", () => {
    document.getElementById("nav").classList.remove("show");
  });
});

// ===================================
// FOOTER AND INITIALIZE
// ===================================

document.getElementById("year").textContent =
  new Date().getFullYear();

document.getElementById("footerWhatsApp").href =
  "https://wa.me/" + WHATSAPP_NUMBER;

renderProducts(products);
updateCart();
