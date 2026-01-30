index.html
<!DOCTYPE html>
<html>
<head>
  <title>My Game Store</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: white;
      margin: 0;
    }
    .top {
      padding: 15px;
      font-size: 22px;
      color: #1a73e8;
      border-bottom: 1px solid #ddd;
    }
    .games {
      display: grid;
      grid-template-columns: repeat(auto-fit, 150px);
      gap: 20px;
      padding: 20px;
    }
    .game {
      border: 1px solid #eee;
      border-radius: 12px;
      padding: 10px;
      text-align: center;
    }
    img {
      width: 100%;
      border-radius: 10px;
    }
  </style>
</head>

<body>
  <div class="top">My Game Store</div>

  <div class="games">
    <div class="game">
      <img src="https://via.placeholder.com/300">
      <div>My First Game</div>
    </div>
  </div>
</body>
</html>
