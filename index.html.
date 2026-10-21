<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NEXTWAVE SUPPLIES | Clothing Store</title>
<meta name="description" content="Discover your next look at NEXTWAVE SUPPLIES. Shop clothing and contact us to order.">

<style>
:root {
  --black: #101010;
  --charcoal: #252525;
  --white: #ffffff;
  --light: #f5f5f5;
  --gray: #777777;
  --border: #e5e5e5;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, Helvetica, sans-serif;
  background: var(--white);
  color: var(--black);
}

button, input, select {
  font: inherit;
}

button {
  cursor: pointer;
}

.topbar {
  background: var(--black);
  color: white;
  text-align: center;
  padding: 10px;
  font-size: 12px;
  letter-spacing: 1px;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 22px 5%;
  border-bottom: 1px solid var(--border);
  gap: 15px;
}

.logo {
  font-size: 21px;
  font-weight: 900;
  letter-spacing: -1px;
}

.logo span {
  color: var(--gray);
}

.header-actions {
  display: flex;
  gap: 10px;
  align-items: center;
}

.header-button {
  background: var(--black);
  color: white;
  border: none;
  padding: 12px 15px;
  font-size: 12px;
  font-weight: bold;
}

.hero {
  background: var(--black);
  color: white;
  padding: 75px 7%;
}

.hero p {
  color: #cccccc;
  letter-spacing: 3px;
  font-size: 11px;
  margin-bottom: 20px;
}

.hero h1 {
  font-size: clamp(36px, 7vw, 68px);
  max-width: 650px;
  line-height: 1.05;
  margin-bottom: 20px;
}

.hero .description {
  font-size: 15px;
  line-height: 1.8;
  letter-spacing: 0;
  max-width: 470px;
  margin-bottom: 25px;
}

.hero a {
  display: inline-block;
  background: white;
  color: black;
  padding: 15px 24px;
  text-decoration: none;
  font-size: 12px;
  font-weight: bold;
}

.section {
  padding: 55px 5%;
}

.section-heading {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 28px;
  gap: 15px;
}

.section-heading h2 {
  font-size: 27px;
}

.section-heading p {
  color: var(--gray);
  font-size: 12px;
}

.products {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 20px;
}

.product-card {
  border: 1px solid var(--border);
  background: white;
  overflow: hidden;
}

.product-image {
  width: 100%;
  height: 230px;
  object-fit: cover;
  display: block;
  background: var(--light);
}

.product-info {
  padding: 17px;
}

.product-info h3 {
  font-size: 16px;
  margin-bottom: 8px;
}

.product-description {
  color: var(--gray);
  font-size: 12px;
  margin-bottom: 12px;
  line-height: 1.5;
}

.price {
  font-size: 16px;
  font-weight: bold;
  margin-bottom: 15px;
}

.product-info label {
  display: block;
  font-size: 11px;
  font-weight: bold;
  margin: 12px 0 6px;
}

.product-info select,
.product-info input {
  width: 100%;
  border: 1px solid var(--border);
  padding: 11px;
  background: white;
}

.add-button {
  width: 100%;
  border: none;
  background: var(--black);
  color: white;
  padding: 13px;
  margin-top: 15px;
  font-weight: bold;
  font-size: 12px;
}

.add-button:hover,
.header-button:hover {
  background: var(--charcoal);
}

.empty {
  color: var(--gray);
  font-size: 14px;
  padding: 20px 0;
}

.cart-section {
  background: var(--light);
}

.cart-item {
  background: white;
  border: 1px solid var(--border);
  padding: 16px;
  margin-bottom: 12px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 12px;
}

.cart-item small {
  display: block;
  color: var(--gray);
  margin-top: 6px;
  line-height: 1.5;
}

.remove-button {
  background: none;
  border: 1px solid var(--border);
  padding: 8px 10px;
  font-size: 11px;
}

.cart-total {
  font-size: 22px;
  font-weight: bold;
  margin: 22px 0;
}

.checkout-button {
  width: 100%;
  max-width: 350px;
  padding: 16px;
  background: var(--black);
  color: white;
  border: none;
  font-weight: bold;
}

.payment-options {
  display: none;
  max-width: 500px;
  margin-top: 22px;
}

.payment-options h3 {
  margin-bottom: 10px;
}

.payment-options p {
  font-size: 13px;
  color: var(--gray);
  line-height: 1.6;
  margin-bottom: 15px;
}

.contact-button {
  display: block;
  text-align: center;
  text-decoration: none;
  padding: 15px;
  margin: 10px 0;
  background: white;
  border: 1px solid var(--black);
  color: var(--black);
  font-size: 13px;
  font-weight: bold;
}

.contact-button:hover {
  background: var(--black);
  color: white;
}

footer {
  background: var(--black);
  color: white;
  padding: 35px 5%;
}

footer p {
  color: #cccccc;
  font-size: 12px;
  margin-top: 12px;
  line-height: 1.8;
}

footer a {
  color: white;
}

@media (max-width: 700px) {
  .products {
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 10px;
  }

  .product-image {
    height: 170px;
  }

  .product-info {
    padding: 12px;
  }

  .section {
    padding: 38px 4%;
  }

  .hero {
    padding: 55px 6%;
  }

  header {
    padding: 18px 4%;
  }

  .logo {
    font-size: 17px;
  }

  .header-button {
    padding: 10px;
    font-size: 10px;
  }
}

@media (max-width: 360px) {
  .products {
    grid-template-columns: 1fr;
  }

  .product-image {
    height: 240px;
  }
}
</style>
</head>

<body>

<div class="topbar">
  NEXTWAVE SUPPLIES — YOUR NEXT LOOK STARTS HERE
</div>

<header>
  <div class="logo">NEXTWAVE <span>SUPPLIES</span></div>

  <div class="header-actions">
    <button class="header-button"
      onclick="document.getElementById('shop').scrollIntoView({behavior:'smooth'})">
      SHOP
    </button>

    <button class="header-button"
      onclick="document.getElementById('cart').scrollIntoView({behavior:'smooth'})">
      CART (<span id="cartCount">0</span>)
    </button>
  </div>
</header>

<section class="hero">
  <p>STYLE. QUALITY. CONFIDENCE.</p>

  <h1>MAKE YOUR NEXT MOVE IN STYLE.</h1>

  <div class="description">
    Explore clothing made for your everyday style.
    Choose your items, add them to your cart, and contact us to place your order.
  </div>

  <a href="#shop">EXPLORE COLLECTION</a>
</section>

<section class="section" id="shop">
  <div class="section-heading">
    <h2>Our Collection</h2>
    <p>Find your next favourite.</p>
  </div>

  <div class="products" id="products"></div>
</section>

<section class="section cart-section" id="cart">
  <div class="section-heading">
    <h2>Your Shopping Cart</h2>
  </div>

  <div id="cartItems">
    <p class="empty">Your cart is empty. Add something you love.</p>
  </div>

  <div class="cart-total">
    Total: <span id="cartTotal">₦0</span>
  </div>

  <button class="checkout-button" onclick="showPaymentOptions()">
    PAY NOW / PLACE ORDER
  </button>

  <div class="payment-options" id="paymentOptions">
    <h3>Choose how to contact us</h3>

    <p>
      Select an option below to send your order details.
      We will confirm your order and provide payment instructions.
      No payment is processed directly on this website.
    </p>

    <a class="contact-button" id="whatsappLink"
       href="#" target="_blank" rel="noopener">
      ORDER THROUGH WHATSAPP
    </a>

    <a class="contact-button" id="telegramLink"
       href="#" target="_blank" rel="noopener">
      CONTACT THROUGH TELEGRAM
    </a>

    <a class="contact-button" id="emailLink"
       href="#">
      ORDER THROUGH EMAIL
    </a>
  </div>
</section>

<footer>
  <div class="logo">NEXTWAVE <span>SUPPLIES</span></div>

  <p>
    Clothing for your next move.<br>
    Questions or orders? Contact our team using the options above.
  </p>

  <p>©️ <span id="year"></span> NEXTWAVE SUPPLIES. All rights reserved.</p>
</footer>

<script>
/*
  STARTER PRODUCT CATALOG

  Replace the sample products with your actual products.
  Prices are examples. Update them before publishing.

  Product information is currently stored in this HTML file.
*/

const products = [
  {
    id: 1,
    name: "Essential T-Shirt",
    description: "A simple everyday wardrobe essential.",
    price: 12000,
    image: "https://placehold.co/600x700/eeeeee/111111?text=Essential+T-Shirt",
    sizes: ["S", "M", "L", "XL"],
    colors: ["Black", "White", "Grey"]
  },
  {
    id: 2,
    name: "Classic Hoodie",
    description: "A versatile layer for everyday wear.",
    price: 25000,
    image: "https://placehold.co/600x700/e5e5e5/111111?text=Classic+Hoodie",
    sizes: ["S", "M", "L", "XL"],
    colors: ["Black", "Grey", "White"]
  },
  {
    id: 3,
    name: "Casual Sweatshirt",
    description: "Comfortable style for everyday use.",
    price: 20000,
    image: "https://placehold.co/600x700/dcdcdc/111111?text=Sweatshirt",
    sizes: ["S", "M", "L", "XL"],
    colors: ["Black", "Grey", "White"]
  }
];

let cart = [];

function formatMoney(amount) {
  return "₦" + amount.toLocaleString("en-NG");
}

function renderProducts() {
  const container = document.getElementById("products");

  container.innerHTML = products.map(product => `
    <article class="product-card">
      <img
        class="product-image"
        src="${escapeHTML(product.image)}"
        alt="${escapeHTML(product.name)}"
        loading="lazy"
        onerror="this.src='https://placehold.co/600x700/eeeeee/111111?text=Product'">

      <div class="product-info">
        <h3>${escapeHTML(product.name)}</h3>

        <p class="product-description">
          ${escapeHTML(product.description)}
        </p>

        <div class="price">${formatMoney(product.price)}</div>

        <label for="size-${product.id}">SIZE</label>

        <select id="size-${product.id}">
          ${product.sizes.map(size =>
            `<option value="${escapeHTML(size)}">${escapeHTML(size)}</option>`
          ).join("")}
        </select>

        <label for="color-${product.id}">COLOUR</label>

        <select id="color-${product.id}">
          ${product.colors.map(color =>
            `<option value="${escapeHTML(color)}">${escapeHTML(color)}</option>`
          ).join("")}
        </select>

        <label for="quantity-${product.id}">QUANTITY</label>

        <input
          type="number"
          id="quantity-${product.id}"
          min="1"
          max="99"
          value="1">

        <button class="add-button" onclick="addToCart(${product.id})">
          ADD TO CART
        </button>
      </div>
    </article>
  `).join("");
}

function escapeHTML(value) {
  return String(value).replace(/[&<>"']/g, character => ({
    "&": "&amp;",
    "<": "&lt;",
    ">": "&gt;",
    '"': "&quot;",
    "'": "&#039;"
  })[character]);
}

function addToCart(id) {
  const product = products.find(item => item.id === id);

  const size = document.getElementById(`size-${id}`).value;
  const color = document.getElementById(`color-${id}`).value;

  const quantityInput = document.getElementById(`quantity-${id}`);
  const quantity = Number(quantityInput.value);

  if (!Number.isInteger(quantity) || quantity < 1 || quantity > 99) {
    alert("Please enter a quantity between 1 and 99.");
    return;
  }

  const existing = cart.find(item =>
    item.id === id &&
    item.size === size &&
    item.color === color
  );

  if (existing) {
    existing.quantity += quantity;
  } else {
    cart.push({
      id: product.id,
      name: product.name,
      price: product.price,
      size: size,
      color: color,
      quantity: quantity
    });
  }

  renderCart();

  quantityInput.value = 1;

  alert("Product added to your cart.");
}

function renderCart() {
  const container = document.getElementById("cartItems");

  const count = cart.reduce((sum, item) => sum + item.quantity, 0);

  const total = cart.reduce(
    (sum, item) => sum + item.price * item.quantity,
    0
  );

  document.getElementById("cartCount").textContent = count;
  document.getElementById("cartTotal").textContent = formatMoney(total);

  if (cart.length === 0) {
    container.innerHTML =
      '<p class="empty">Your cart is empty. Add something you love.</p>';

    document.getElementById("paymentOptions").style.display = "none";
    return;
  }

  container.innerHTML = cart.map((item, index) => `
    <div class="cart-item">
      <div>
        <strong>${escapeHTML(item.name)}</strong>

        <small>
          Size: ${escapeHTML(item.size)} |
          Colour: ${escapeHTML(item.color)} |
          Quantity: ${item.quantity}<br>
          ${formatMoney(item.price)} each<br>
          Subtotal: ${formatMoney(item.price * item.quantity)}
        </small>
      </div>

      <button class="remove-button" onclick="removeItem(${index})">
        REMOVE
      </button>
    </div>
  `).join("");

  updateContactLinks();
}

function removeItem(index) {
  cart.splice(index, 1);
  renderCart();
}

function createOrderMessage() {
  const lines = cart.map(item =>
    `${item.name} | Size: ${item.size} | Colour: ${item.color} | Quantity: ${item.quantity} | Subtotal: ${formatMoney(item.price * item.quantity)}`
  );

  const total = cart.reduce(
    (sum, item) => sum + item.price * item.quantity,
    0
  );

  return [
    "Hello NEXTWAVE SUPPLIES, I would like to place an order.",
    "",
    ...lines,
    "",
    `Order total: ${formatMoney(total)}`,
    "",
    "Please confirm availability and send me payment instructions."
  ].join("\n");
}

function updateContactLinks() {
  const message = createOrderMessage();

  document.getElementById("whatsappLink").href =
    "https://wa.me/18706517285?text=" + encodeURIComponent(message);

  document.getElementById("telegramLink").href =
    "https://t.me/rebandmovz";

  document.getElementById("emailLink").href =
    "mailto:dealshub@icloud.com?subject=" +
    encodeURIComponent("NEXTWAVE SUPPLIES Order") +
    "&body=" + encodeURIComponent(message);
}

function showPaymentOptions() {
  if (cart.length === 0) {
    alert("Your cart is empty. Please add a product first.");
    return;
  }

  updateContactLinks();

  const options = document.getElementById("paymentOptions");

  options.style.display = "block";

  options.scrollIntoView({ behavior: "smooth", block: "nearest" });
}

document.getElementById("year").textContent = new Date().getFullYear();

renderProducts();
renderCart();
</script>

</body>
</html>
