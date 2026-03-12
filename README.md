<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For Junaid ❤️</title>

<style>

body{
margin:0;
font-family:Arial;
text-align:center;
background:linear-gradient(135deg,#ff758c,#ff7eb3);
color:white;
}

.container{
padding:50px 20px;
}

h1{
font-size:42px;
}

#countdown{
font-size:28px;
margin:20px;
}

.letter{
background:rgba(255,255,255,0.15);
padding:25px;
border-radius:15px;
max-width:700px;
margin:auto;
line-height:1.7;
font-size:18px;
}

button{
margin-top:30px;
padding:12px 25px;
font-size:18px;
border:none;
border-radius:30px;
background:white;
color:#ff4b6e;
cursor:pointer;
}

button:hover{
background:#ffe3ea;
}

.heart{
font-size:35px;
animation:beat 1s infinite;
}

@keyframes beat{
0%{transform:scale(1)}
50%{transform:scale(1.2)}
100%{transform:scale(1)}
}

</style>
</head>

<body>

<div class="container">

<h1>Happy Birthday Junaid 🎂</h1>

<div id="countdown"></div>

<div class="letter">

<p>
My love, today is such a special day because it celebrates the day the most amazing person in my life was born.
Even though miles separate us, my heart has never felt closer to you. Every memory with you is precious to me, and every moment we share reminds me how lucky I am to have you in my life.
</p>

<p>
When you came into my life, you brought happiness, comfort, and a love that I never imagined I would experience. Your smile, your voice, and the way you care about me mean more than words could ever express.
</p>

<p>
I know distance is not always easy, but loving you makes every wait worth it. I believe in us, in our love, and in the beautiful future we are building together.
</p>

<p>
On your birthday, I just want you to know that you are deeply loved, appreciated, and cherished. No matter how far we are, you will always have my heart.
</p>

<p>
Happy Birthday, my love. May this year bring you endless happiness, success, and all the dreams you wish for.
</p>

</div>

<div class="heart">❤️</div>

<button onclick="surprise()">Click For Surprise</button>

<p id="msg"></p>

</div>

<script>

var birthday = new Date("March 13, 2026 00:00:00").getTime();

var x = setInterval(function(){

var now = new Date().getTime();
var distance = birthday - now;

var days = Math.floor(distance / (1000*60*60*24));
var hours = Math.floor((distance % (1000*60*60*24))/(1000*60*60));
var minutes = Math.floor((distance % (1000*60*60))/(1000*60));
var seconds = Math.floor((distance % (1000*60))/1000);

document.getElementById("countdown").innerHTML =
days + "d " + hours + "h " + minutes + "m " + seconds + "s";

if(distance < 0){
clearInterval(x);
document.getElementById("countdown").innerHTML = "It's Junaid's Birthday Today 🎉";
}

},1000);

function surprise(){
document.getElementById("msg").innerHTML =
"Junaid, you are my favorite person, my safe place, and my forever love ❤️";
}

</script>

</body>
</html> 
