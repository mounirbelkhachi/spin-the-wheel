<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Spin the Wheel</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <h1>Spin the Wheel & Win a Prize!</h1>
    <div class="wheel-container">
      <canvas id="wheel" width="500" height="500"></canvas>
      <button id="spinButton">Spin</button>
    </div>
    <div id="result">
      <p>Congrats! You've won <span id="prize"></span></p>
      <a id="claimButton" href="#" target="_blank">Claim your prize here!</a>
    </div>
  </div>
  <script src="script.js"></script>
</body>
</html>
