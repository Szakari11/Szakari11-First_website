<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>VibeThread - Home</title>
  <link rel="stylesheet" href="style.css">
  <script defer src="main.js"></script>
</head>
<body>
  <header>
    <h1>Welcome to VibeThread</h1>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="shop.html">Shop</a></li>
        <li><a href="customize.html">Customize</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section>
      <h2>Design Your Vibe</h2>
      <p>Customize your own shirt! Type your message below:</p>
      <input type="text" id="customText" placeholder="Enter your message">
      <button onclick="customizeShirt()">Create Shirt</button>
      <p id="shirtPreview"></p>
    </section>

    <section>
      <h2>Shop by Style</h2>
      <button onclick="showStyles()">See Styles</button>
      <ul id="styleList"></ul>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 VibeThread. All rights reserved.</p>
  </footer>
</body>
</html>

