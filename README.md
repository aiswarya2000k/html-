<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Creative HTML List</title>
  <style>
    body {
      margin: 0;
      font-family: "Segoe UI", sans-serif;
      min-height: 100vh;
      background: linear-gradient(135deg, #667eea, #764ba2);
      display: flex;
      justify-content: center;
      align-items: center;
      color: #fff;
    }

    .container {
      width: 80%;
      max-width: 700px;
    }

    h1 {
      text-align: center;
      margin-bottom: 30px;
      letter-spacing: 1px;
    }

    .card {
      background: rgba(255, 255, 255, 0.15);
      backdrop-filter: blur(10px);
      border-radius: 15px;
      padding: 20px;
      margin-bottom: 25px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.3);
    }

    h2 {
      margin-top: 0;
      color: #ffd369;
      text-align: center;
    }

    ul, ol {
      padding-left: 25px;
    }

    li {
      margin: 8px 0;
      background: rgba(255, 255, 255, 0.2);
      padding: 8px 12px;
      border-radius: 8px;
    }

    dl dt {
      font-weight: bold;
      color: #ffd369;
      margin-top: 10px;
    }

    dl dd {
      margin-left: 0;
      margin-bottom: 10px;
      font-size: 0.9em;
      opacity: 0.9;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>🌈 My Favorite Beverages</h1>

    <div class="card">
      <h2>Unordered List</h2>
      <ul>
        <li>☕ Coffee</li>
        <li>🍵 Tea</li>
        <li>🥤 Coca-Cola</li>
      </ul>
    </div>

    <div class="card">
      <h2>Ordered List</h2>
      <ol>
        <li>Coffee</li>
        <li>Tea</li>
        <li>Coca-Cola</li>
      </ol>
    </div>

    <div class="card">
      <h2>Description List</h2>
      <dl>
        <dt>Coffee</dt>
        <dd>A strong brewed drink made from roasted coffee beans.</dd>

        <dt>Tea</dt>
        <dd>A calming beverage made from tea leaves, served hot or cold.</dd>

        <dt>Coca-Cola</dt>
        <dd>A fizzy soft drink with a sweet and refreshing taste.</dd>
      </dl>
    </div>
  </div>

</body>
</html>
