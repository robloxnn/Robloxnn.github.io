<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Bouton Start</title>

<style>
body{
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
    background:#111;
    font-family:Arial, sans-serif;
}

button{
    padding:15px 40px;
    font-size:20px;
    color:white;
    background:#00aaff;
    border:none;
    border-radius:10px;
    cursor:pointer;
    transition:0.3s;
}

button:hover{
    background:#0088cc;
    transform:scale(1.05);
}
</style>

</head>
<body>

<button onclick="start()">Start by Mohy naomy <3</button>

<script>
function start(){
    alert("Le bouton Start by Mohy a été cliqué !");
}
</script>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: skyblue;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

img {
  max-width: 80%;
}
</style>
</head>

<body>

<img src="image.jpg" alt="Mon image">

</body>
</html>
