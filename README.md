<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Wedding Invitation | Ayan & Nabila</title>

<link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

/* ==============================
   GLOBAL STYLE
================================ */

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
}

body{
    font-family:'Poppins',sans-serif;
    background:#120b10;
    color:white;
    overflow-x:hidden;
}

/* ==============================
   FLOATING HEARTS
================================ */

.heart{
    position:fixed;
    color:#ff4f81;
    animation:float 8s linear infinite;
    opacity:.7;
    pointer-events:none;
    z-index:1;
}

@keyframes float{

    0%{
        transform:translateY(110vh) rotate(0deg);
        opacity:0;
    }

    20%{
        opacity:.8;
    }

    100%{
        transform:translateY(-10vh) rotate(360deg);
        opacity:0;
    }

}


/* ==============================
   HERO SECTION
================================ */

.hero{

    min-height:100vh;

    display:flex;
    align-items:center;
    justify-content:center;

    text-align:center;

    position:relative;

    background:
    linear-gradient(
        rgba(20,10,15,.65),
        rgba(20,10,15,.9)
    ),

    url("https://images.unsplash.com/photo-1519741497674-611481863552?auto=format&fit=crop&w=1600&q=80");

    background-size:cover;
    background-position:center;

}

.hero-content{

    max-width:900px;
    padding:40px;

    backdrop-filter:blur(10px);

    background:rgba(255,255,255,.08);

    border:1px solid rgba(255,255,255,.2);

    border-radius:30px;

    box-shadow:
    0 20px 60px rgba(0,0,0,.5);

    animation:fadeUp 1.5s ease;

}

@keyframes fadeUp{

    from{
        opacity:0;
        transform:translateY(50px);
    }

    to{
        opacity:1;
        transform:translateY(0);
    }

}

.hero h3{

    font-size:18px;
    letter-spacing:5px;

    color:#f8c8d8;

}

.names{

    font-family:'Great Vibes',cursive;

    font-size:100px;

    margin:20px 0;

    background:linear-gradient(
        90deg,
        #ffffff,
        #ffd1df,
        #f4b6c2
    );

    -webkit-background-clip:text;

    color:transparent;

}

.hero p{

    font-size:18px;

    color:#eee;

    margin-bottom:25px;

}

.date-box{

    display:inline-block;

    padding:15px 30px;

    border-radius:50px;

    background:#ffffff15;

    border:1px solid #ffffff30;

}


/* ==============================
   SECTION
================================ */

section{

    padding:100px 8%;

}

.section-title{

    text-align:center;

    font-family:'Great Vibes',cursive;

    font-size:65px;

    color:#ffd1dc;

    margin-bottom:60px;

}


/* ==============================
   LOVE STORY CARD
================================ */

.love-card{

    max-width:900px;

    margin:auto;

    background:linear-gradient(
        145deg,
        #24121c,
        #13090f
    );

    border-radius:30px;

    padding:50px;

    text-align:center;

    border:1px solid #ffffff10;

    box-shadow:
    0 20px 60px rgba(0,0,0,.4);

}

.love-card p{

    line-height:1.9;

    color:#ddd;

}


/* ==============================
   COUPLE SECTION
================================ */

.couple{

    display:grid;

    grid-template-columns:
    repeat(2,1fr);

    gap:40px;

    max-width:1100px;

    margin:auto;

}

.person{

    padding:40px;

    border-radius:30px;

    background:linear-gradient(
        145deg,
        #2c1622,
        #170b12
    );

    text-align:center;

    transition:.4s;

}

.person:hover{

    transform:translateY(-10px);

}

.person img{

    width:180px;
    height:180px;

    object-fit:cover;

    border-radius:50%;

    border:5px solid #f8bfd0;

    margin-bottom:20px;

}

.person h2{

    font-family:'Great Vibes',cursive;

    font-size:55px;

    color:#ffd1dc;

}

.person p{

    color:#ccc;

    margin-top:10px;

}


/* ==============================
   COUNTDOWN
================================ */

.countdown{

    display:flex;

    justify-content:center;

    gap:20px;

    flex-wrap:wrap;

}

.time-box{

    width:120px;

    padding:25px 10px;

    border-radius:20px;

    background:#ffffff10;

    border:1px solid #ffffff20;

    text-align:center;

}

.time-box h2{

    font-size:40px;

    color:#ffd1dc;

}

.time-box span{

    font-size:13px;

    color:#aaa;

}


/* ==============================
   VENUE
================================ */

.venue{

    max-width:1100px;

    margin:auto;

    border-radius:30px;

    overflow:hidden;

    background:#1b0d14;

    box-shadow:
    0 20px 60px rgba(0,0,0,.5);

}

.venue img{

    width:100%;

    height:400px;

    object-fit:cover;

}

.venue-content{

    padding:40px;

    text-align:center;

}

.venue-content h2{

    font-size:35px;

    color:#ffd1dc;

    margin-bottom:15px;

}

.venue-content p{

    color:#ccc;

    margin:10px;

}

.map-btn{

    display:inline-block;

    margin-top:25px;

    padding:15px 30px;

    background:#ff4f81;

    color:white;

    text-decoration:none;

    border-radius:50px;

    transition:.3s;

}

.map-btn:hover{

    transform:scale(1.08);

    background:#ff2f6d;

}


/* ==============================
   RSVP
================================ */

.rsvp{

    text-align:center;

}

.rsvp-card{

    max-width:600px;

    margin:auto;

    padding:50px;

    border-radius:30px;

    background:linear-gradient(
        145deg,
        #2b1420,
        #12080d
    );

}

.rsvp-card h2{

    font-family:'Great Vibes',cursive;

    font-size:55px;

    color:#ffd1dc;

}

.rsvp-card p{

    margin:20px 0;

    color:#ccc;

}

.rsvp-btn{

    display:inline-block;

    padding:16px 35px;

    border-radius:50px;

    background:#ff4f81;

    color:white;

    text-decoration:none;

}


/* ==============================
   FOOTER
================================ */

footer{

    text-align:center;

    padding:30px;

    color:#888;

    background:#0b0508;

}


/* ==============================
   RESPONSIVE
================================ */

@media(max-width:768px){

    .names{
        font-size:65px;
    }

    .couple{
        grid-template-columns:1fr;
    }

    .section-title{
        font-size:50px;
    }

}

</style>

</head>


<body>


<!-- HERO -->

<section class="hero">

<div class="hero-content">

<h3>WE ARE GETTING MARRIED</h3>

<div class="names">
Ayan & Nabila
</div>

<p>
Two hearts. One beautiful journey.
</p>

<div class="date-box">
💍 Friday, 25 December 2026
</div>

</div>

</section>



<!-- LOVE STORY -->

<section>

<h1 class="section-title">
Our Story
</h1>

<div class="love-card">

<p>

Every beautiful story begins with a simple moment.
Two strangers, two different journeys,
and somehow destiny brought them together.

Today, we invite you to celebrate
the beginning of our forever. ❤️

</p>

</div>

</section>



<!-- COUPLE -->

<section>

<h1 class="section-title">
The Couple
</h1>

<div class="couple">


<!-- GROOM -->

<div class="person">

<img src="https://images.unsplash.com/photo-1500648767791-00dcc994a43e?auto=format&fit=crop&w=500&q=80">

<h2>Ayan Ahmed</h2>

<p>
Son of Mr. & Mrs. Ahmed
</p>

<p>
Chattogram, Bangladesh
</p>

</div>



<!-- BRIDE -->

<div class="person">

<img src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?auto=format&fit=crop&w=500&q=80">

<h2>Nabila Islam</h2>

<p>
Daughter of Mr. & Mrs. Islam
</p>

<p>
Dhaka, Bangladesh
</p>

</div>


</div>

</section>



<!-- COUNTDOWN -->

<section>

<h1 class="section-title">
Counting Down
</h1>

<div class="countdown">

<div class="time-box">

<h2 id="days">00</h2>

<span>DAYS</span>

</div>


<div class="time-box">

<h2 id="hours">00</h2>

<span>HOURS</span>

</div>


<div class="time-box">

<h2 id="minutes">00</h2>

<span>MINUTES</span>

</div>


<div class="time-box">

<h2 id="seconds">00</h2>

<span>SECONDS</span>

</div>

</div>

</section>



<!-- VENUE -->

<section>

<h1 class="section-title">
Wedding Venue
</h1>

<div class="venue">

<img src="https://images.unsplash.com/photo-1464366400600-7168b8af9bc3?auto=format&fit=crop&w=1400&q=80">


<div class="venue-content">

<h2>Royal Grand Convention Hall</h2>

<p>
📍 123 Wedding Avenue,
Chattogram, Bangladesh
</p>

<p>
🕕 Reception starts at 6:00 PM
</p>


<a
href="https://maps.google.com"
target="_blank"
class="map-btn"
>

View Location 📍

</a>

</div>

</div>

</section>



<!-- RSVP -->

<section class="rsvp">

<div class="rsvp-card">

<h2>
Save The Date
</h2>

<p>

Your presence will make our
special day even more beautiful.

</p>

<a href="#" class="rsvp-btn">

RSVP Now 💌

</a>

</div>

</section>



<!-- FOOTER -->

<footer>

Made with ❤️ for Ayan & Nabila

</footer>



<script>


/* ==============================
   COUNTDOWN
================================ */

const weddingDate =
new Date("December 25, 2026 18:00:00").getTime();


setInterval(function(){

    const now =
    new Date().getTime();


    const distance =
    weddingDate - now;


    const days =
    Math.floor(
        distance /
        (1000*60*60*24)
    );


    const hours =
    Math.floor(
        (distance %
        (1000*60*60*24))
        /
        (1000*60*60)
    );


    const minutes =
    Math.floor(
        (distance %
        (1000*60*60))
        /
        (1000*60)
    );


    const seconds =
    Math.floor(
        (distance %
        (1000*60))
        /
        1000
    );


    document.getElementById("days")
    .innerHTML = days;


    document.getElementById("hours")
    .innerHTML = hours;


    document.getElementById("minutes")
    .innerHTML = minutes;


    document.getElementById("seconds")
    .innerHTML = seconds;


},1000);



/* ==============================
   FLOATING HEARTS
================================ */

function createHeart(){

    const heart =
    document.createElement("div");


    heart.classList.add("heart");


    heart.innerHTML = "❤";


    heart.style.left =
    Math.random()*100 + "vw";


    heart.style.fontSize =
    Math.random()*25 + 15 + "px";


    heart.style.animationDuration =
    Math.random()*5 + 5 + "s";


    document.body.appendChild(heart);


    setTimeout(function(){

        heart.remove();

    },10000);

}


setInterval(createHeart,700);


</script>


</body>

</html>
