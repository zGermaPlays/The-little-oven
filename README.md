<!DOCTYPE html>
<html>
<head>
  <title>Event Menu</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: #111;
      color: #fff;
      font-family: Arial, sans-serif;
      text-align: center;
    }

    h1 {
      font-size: 70px;
      margin-top: 40px;
      margin-bottom: 20px;
      letter-spacing: 2px;
    }

    .menu-container {
      width: 90%;
      max-width: 1200px;
      margin: auto;
    }

    .menu-item {
      background: #222;
      padding: 30px;
      margin: 30px 0;
      border-radius: 20px;
    }

    .menu-item img {
      width: 400px;
      max-width: 90%;
      border-radius: 15px;
      margin-bottom: 20px;
    }

    .item-name {
      font-size: 50px;
      font-weight: bold;
      margin-bottom: 10px;
    }

    .item-desc {
      font-size: 32px;
      opacity: 0.8;
      margin-bottom: 15px;
    }

    .item-price {
      font-size: 45px;
      color: #ffd700;
      font-weight: bold;
    }
  </style>
</head>

<body>
  <h1>Tonight’s Menu</h1>

  <div class="menu-container">

    <!-- ITEM 1 -->
    <div class="menu-item">
      <img src="images/item1.png">
      <div class="item-name">Pulled Pork Sandwich</div>
      <div class="item-desc">Slow-smoked pork on a toasted bun</div>
      <div class="item-price">$10</div>
    </div>

    <!-- ITEM 2 -->
    <div class="menu-item">
      <img src="images/item2.png">
      <div class="item-name">Mac & Cheese</div>
      <div class="item-desc">Creamy 3‑cheese blend</div>
      <div class="item-price">$6</div>
    </div>

    <!-- ITEM 3 -->
    <div class="menu-item">
      <img src="images/item3.png">
      <div class="item-name">Lemon Bars</div>
      <div class="item-desc">Fresh, tangy, and sweet</div>
      <div class="item-price">$4</div>
    </div>

  </div>
</body>
</html>

