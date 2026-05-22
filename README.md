<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday ❤️</title>

<style>
body{
    margin:0;
    padding:0;
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    background:linear-gradient(135deg,#ff4e8b,#ff85a2);
    overflow:hidden;
    font-family:Arial;
}

.container{
    text-align:center;
    color:white;
}

h1{
    font-size:40px;
}

p{
    font-size:18px;
    width:85%;
    margin:auto;
}

img{
    width:200px;
    height:200px;
    border-radius:50%;
    object-fit:cover;
    border:5px solid white;
}

button{
    margin-top:20px;
    padding:10px 20px;
    border:none;
    border-radius:20px;
    background:white;
    color:#ff4e8b;
    font-weight:bold;
}

.heart{
    position:absolute;
    animation:float 6s linear infinite;
}

@keyframes float{
    0%{transform:translateY(100vh);}
    100%{transform:translateY(-10vh);}
}
</style>
</head>

<body>

<div class="container">

<img src="https://i.imgur.com/4M34hi2.jpeg">

<h1>Happy Birthday My Love ❤️</h1>

<p>
Mein tenu pyar karda haan, tu meri zindagi da sab ton sohna hissa aayn 💖
</p>

<button onclick="showMessage()">Click Here 💌</button>

</div>

<script>
function showMessage(){
    alert("Happy Birthday MADINAHSAN ❤️🎂");
}
</script>

</body>
</html>
