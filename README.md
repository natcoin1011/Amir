<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Natcoin Click</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(to bottom, #000000, #1a1a1a);
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .container {
      text-align: center;
    }
    .coin-btn {
      background-color: gold;
      color: black;
      font-size: 24px;
      padding: 20px 40px;
      border: none;
      border-radius: 20px;
      cursor: pointer;
      box-shadow: 0 0 10px gold;
      transition: transform 0.2s ease;
    }
    .coin-btn:active {
      transform: scale(0.95);
    }
    .counter {
      font-size: 40px;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Natcoin Click</h1>
    <button class="coin-btn" onclick="increment()">Tap to Earn</button>
    <div class="counter" id="counter">0</div>
  </div>  <script>
    let count = 0;
    function increment() {
      count++;
      document.getElementById('counter').innerText = count;
    }
  </script></body>
</html>
