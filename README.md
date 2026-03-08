<h1>Roblox account </h1>
<body><a href="https://www.roblox.com/users/profile?username=Yt_mohy" target="_blank">
  <button>Roblox account</button>
👈
</a>

  <h1>Tiktok account</h1>


  
<body>

  
  <button onclick="window.location.href='https://www.tiktok.com/@momo37moi'">
Voir mon TikTok
</button>👈

</body>

<h1> GAME (bêta)</h1>

<button onclick="startGame()">start Game bêta</button>
<p>Score : <span id="score">0</span></p>

<div id="gameArea">
  <div id="target"></div>
</div>

<script>
let score = 0;

function startGame() {
  score = 0;
  document.getElementById("score").textContent = score;
  moveTarget();
}

function moveTarget() {
  const target = document.getElementById("target");
  const area = document.getElementById("gameArea");

  const maxX = area.clientWidth - 40;
  const maxY = area.clientHeight - 40;

  const x = Math.random() * maxX;
  const y = Math.random() * maxY;

  target.style.left = x + "px";
  target.style.top = y + "px";
  target.style.display = "block";
}

document.getElementById("target").onclick = function() {
  score++;
  document.getElementById("score").textContent = score;
  moveTarget();
};
</script>

</body>

