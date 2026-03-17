<!DOCTYPE html>
<html lang="mn">
<head>
<meta charset="UTF-8">
<title>Аавдаа баярын мэнд</title>

<style>

body{
background: linear-gradient(135deg,#0f2027,#203a43,#2c5364);
height:100vh;
display:flex;
justify-content:center;
align-items:center;
font-family:Arial;
color:white;
text-align:center;
overflow:hidden;
}

.card{
animation: fadeIn 2s ease;
padding:40px;
border-radius:20px;
background: rgba(255,255,255,0.1);
backdrop-filter: blur(10px);
}

h1{
font-size:40px;
animation: slideDown 1.5s ease;
}

p{
font-size:20px;
margin-top:20px;
}

.heart{
font-size:40px;
animation: pulse 1.5s infinite;
}

@keyframes fadeIn{
from{opacity:0;}
to{opacity:1;}
}

@keyframes slideDown{
from{transform:translateY(-50px);opacity:0;}
to{transform:translateY(0);opacity:1;}
}

@keyframes pulse{
0%{transform:scale(1);}
50%{transform:scale(1.2);}
100%{transform:scale(1);}
}

</style>

</head>

<body>

<div class="card">

<h1>🎖️ Аавдаа баярын мэнд 🎖️</h1>

<p>
Эрхэм аавдаа  
Зэвсэгт хүчний баярын мэнд хүргэе.
</p>

<p>
Эрүүл энх, аз жаргал, урт удаан наслахыг хүсье.
</p>

<div class="heart">❤️</div>

<p>Таны хүү / охиноос</p>

</div>

</body>
</html>
