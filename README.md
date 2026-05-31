<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Happy Birthday MAHHH BABBYY❤️</title>

<style>

:root{
 --bg1:#fff0f7;
 --bg2:#ffd6ea;
 --accent:#ff69b4;
 --text:#5c3a52;
}

*{
 margin:0;
 padding:0;
 box-sizing:border-box;
}

html{
 scroll-behavior:smooth;
}

body{
 font-family:'Segoe UI',sans-serif;
 color:var(--text);
 background:linear-gradient(135deg,var(--bg1),var(--bg2));
 overflow-x:hidden;
}

/* Floating Hearts */

.hearts{
 position:fixed;
 width:100%;
 height:100%;
 pointer-events:none;
 z-index:-1;
}

.heart{
 position:absolute;
 color:pink;
 animation:float 10s linear infinite;
 opacity:.6;
}

@keyframes float{
 from{
   transform:translateY(100vh);
 }
 to{
   transform:translateY(-120px);
 }
}

/* Hero */

.hero{
 min-height:100vh;
 display:flex;
 flex-direction:column;
 justify-content:center;
 align-items:center;
 text-align:center;
 padding:20px;
}

.hero h1{
 font-size:4rem;
 color:#ff4fa3;
 text-shadow:0 0 20px pink;
 animation:glow 2s infinite alternate;
}

@keyframes glow{
 from{
   transform:scale(1);
 }
 to{
   transform:scale(1.05);
 }
}

.hero p{
 margin-top:20px;
 font-size:1.3rem;
 max-width:700px;
}

.btn{
 margin-top:25px;
 padding:12px 24px;
 border:none;
 border-radius:30px;
 background:#ff69b4;
 color:white;
 cursor:pointer;
 font-size:1rem;
}

section{
 padding:80px 10%;
}

.card{
 background:white;
 padding:30px;
 border-radius:20px;
 box-shadow:0 10px 30px rgba(0,0,0,.08);
}

/* Gallery */

.gallery{
 display:grid;
 grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
 gap:20px;
}

.gallery img{
 width:100%;
 border-radius:20px;
 height:280px;
 object-fit:cover;
 transition:.4s;
}

.gallery img:hover{
 transform:scale(1.05);
}

/* Music */

.music-btn{
 position:fixed;
 bottom:20px;
 right:20px;
 z-index:999;
}

/* Surprise */

#surpriseBox{
 display:none;
 margin-top:20px;
 font-size:1.3rem;
 color:#ff4fa3;
 text-align:center;
}

footer{
 text-align:center;
 padding:40px;
}

.theme-switch{
 position:fixed;
 top:15px;
 right:15px;
 z-index:999;
}

.theme-switch select{
 padding:8px;
 border-radius:10px;
}

@media(max-width:768px){

.hero h1{
 font-size:2.5rem;
}

}

</style>
</head>
<body>

<!-- =========================
CUSTOMIZATION SECTION
========================= -->

<!-- Replace with her name -->
<script>
const friendName="TRINISHA(HG)";

const surpriseText=
"No matter how many years pass, you'll always be one of my favorite memories ❤️";
</script>

<div class="theme-switch">
<select onchange="changeTheme(this.value)">
<option value="pink">Pink</option>
<option value="lavender">Lavender</option>
<option value="blue">Blue</option>
  <option value="red">Red</option>
</select>
</div>

<div class="hearts" id="hearts"></div>

<section class="hero">

<h1>Happy Birthday to my BABBYY(HG)❤️</h1>

<p>
Happy Birthday to the most special person from my childhood.
  Growing up with you is one of the best part of my life From silly conversations to bestest teas and all the memories we made together Every moment still means a lot to me.
  No matter how much we grow up or how busy life gets You will always be my most important person i never forget.
  Thanks for being there for me and you are the one who supported me a lot, gave me emotional support when i need someone the most.
  Am really lucky to have the bestest friend like you.
  I just hope this year brings you success,happiness,peace and everything your heart wishes for cuz you truely deserve it all Enjoy your day
  fully,smile a lot(MY CUTTIE PIE)
  And Yeah.... Don't forget to send me snaps and fitchecks ❤️ And once again HAPPIEST BIRTHDAY TO YOU.❤️
</p>

<a href="#letter">
<button class="btn">
Read My Letter 💌
</button>
</a>

</section>

<section>

<div class="card">

<h2>💌 A Letter For You</h2>

<br>

<p>
Happy Birthday to the bestest friend I could ever ask for ❤️

It's hard to put into words how much your friendship means to me.
We've known each other for so many years that you've become a part of some of my happiest memories.
From our childhood days to where we are now, you've always been there for me.

Thank you for always supporting me, especially when I needed it the most.
Whether it was helping me with studies, encouraging me when I felt stressed, listening to my problems, or simply making me smile on a bad day, you've always been someone I could rely on.

I feel really lucky to have a friend like you. You're kind, caring, hardworking, and one of the few people who genuinely want the best for others.
Thank you for being yourself and for making life a little brighter for everyone around you.

I hope this year brings you happiness, success, good health, and all the things you've been wishing for. You deserve every bit of it.

No matter where life takes us in the future, our friendship and the memories we've made together will always be special to me.

Happy Birthday once again. Enjoy your day, keep smiling, and don't forget to send me chatpatte snaps and fitchecks. love you MAAHH BABBYY. 💖✨

</p>

</div>

</section>

<section>

<h2 style="text-align:center;margin-bottom:30px;">
📸 MAHH CUTTIEPIE
</h2>

<div class="gallery">

<!-- REPLACE THESE FILE NAMES -->

<img src=" HG photo 1.jpeg">
<img src="Photo5.jpeg">
<img src="Photo6.jpeg">

</div>

</section>

<section id="letter">

<div class="card">

<h2>✨ Things I Want To Say</h2>

<br>

<ul>

<li>Thank you for being part of my life.</li>
<li>Thank you for every childhood memory.</li>
<li>You deserve happiness and success.</li>
<li>May this year be your best one yet.</li>

</ul>

</div>

</section>

<section>

<div class="card">

Made with ❤️ for my BABBY(HG)

</footer>

<!-- MUSIC -->

<!-- Replace music.mp3 with your song -->

<audio id="music" loop>
<source src="Kali Uchis - All I Can Say(2).mp3" type="audio/mpeg">
</audio>

<button class="btn music-btn" onclick="toggleMusic()">
🎵 Music
</button>

<script>

/* Hearts */

const hearts=document.getElementById('hearts');

for(let i=0;i<40;i++){

const heart=document.createElement('div');

heart.className='heart';

heart.innerHTML='💖';

heart.style.left=Math.random()*100+'%';

heart.style.fontSize=
(Math.random()*25+15)+'px';

heart.style.animationDuration=
(Math.random()*8+8)+'s';

hearts.appendChild(heart);

}

/* Music */

const music=document.getElementById('music');

let playing=false;

function toggleMusic(){

if(!playing){

music.play();
playing=true;

}else{

music.pause();
playing=false;

}

}


/* Themes */

function changeTheme(theme){

if(theme==="pink"){

document.documentElement.style.setProperty('--bg1','#fff0f7');
document.documentElement.style.setProperty('--bg2','#ffd6ea');

}

if(theme==="lavender"){

document.documentElement.style.setProperty('--bg1','#f6f0ff');
document.documentElement.style.setProperty('--bg2','#e9dcff');

}

if(theme==="blue"){

document.documentElement.style.setProperty('--bg1','#eef7ff');
document.documentElement.style.setProperty('--bg2','#d7edff');

}

}

</script>

</body>
</html># index.html
