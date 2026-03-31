<!DOCTYPE html>
<html>
<head>
  <title>Ludo Game</title>
</head>
<body style="text-align:center; font-family:sans-serif; background:white;">

<h1>🎲 Ludo Game</h1>
<p>Game chal raha hai!</p>

<button onclick="rollDice()">Roll Dice</button>
<h2 id="dice">🎲</h2>

<script>
function rollDice() {
  var num = Math.floor(Math.random() * 6) + 1;
  document.getElementById("dice").innerHTML = "🎲 " + num;
}
</script>

</body>
</html>
