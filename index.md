<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Koewetzelblog | Official Fan Community</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:#0a0a0a;
color:#fff;
}

header{
height:100vh;
background:
linear-gradient(rgba(0,0,0,.65),rgba(0,0,0,.75)),
url('https://images.unsplash.com/photo-1501386761578-eac5c94b800a');
background-size:cover;
background-position:center;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
padding:20px;
}

.hero h1{
font-size:4rem;
font-weight:800;
margin-bottom:15px;
}

.hero p{
font-size:1.2rem;
max-width:700px;
margin:auto;
margin-bottom:30px;
}

.btn{
display:inline-block;
padding:14px 30px;
background:#d4a548;
color:#000;
font-weight:700;
border-radius:40px;
text-decoration:none;
margin:10px;
transition:.3s;
}

.btn:hover{
transform:translateY(-3px);
}

section{
padding:80px 10%;
}

.section-title{
text-align:center;
font-size:2.5rem;
margin-bottom:40px;
color:#d4a548;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;
}

.card{
background:#111;
padding:30px;
border-radius:20px;
border:1px solid #222;
transition:.3s;
}

.card:hover{
transform:translateY(-5px);
}

.card h3{
margin-bottom:10px;
}

.card a{
color:#d4a548;
text-decoration:none;
}

.contact{
text-align:center;
}

.contact a{
display:block;
margin:15px 0;
color:#fff;
font-size:1.1rem;
text-decoration:none;
}

footer{
padding:30px;
text-align:center;
background:#050505;
border-top:1px solid #222;
}

@media(max-width:768px){
.hero h1{
font-size:2.5rem;
}
}
</style>
</head>

<body>

<header>
<div class="hero">
<h1>KOEWETZELBLOG</h1>
<p>The Official Fan Community. Stay connected with the latest music, tour updates, exclusive content and more.</p>

<a href="#" class="btn">Buy Tickets</a>
<a href="#" class="btn">Become a Member</a>
</div>
</header>

<section>
<h2 class="section-title">Listen Now</h2>

<div class="cards">
<div class="card">
<h3>Spotify</h3>
<p>Listen to the latest tracks and playlists.</p>
<a href="#">Open Spotify →</a>
</div>

<div class="card">
<h3>YouTube Music</h3>
<p>Watch videos and stream music.</p>
<a href="#">Open YouTube Music →</a>
</div>
</div>
</section>

<section>
<h2 class="section-title">Upcoming Shows</h2>

<div class="cards">
<div class="card">
<h3>Tour Dates</h3>
<p>Get tickets for upcoming concerts and events.</p>
<a href="#">Buy Tickets →</a>
</div>
</div>
</section>

<section>
<h2 class="section-title">Fan Membership</h2>

<div class="card">
<h3>Exclusive Access</h3>
<p>Join the fan club for exclusive content, updates and special announcements.</p>
<br>
<a href="#" class="btn">Become a Member</a>
</div>
</section>

<section class="contact">
<h2 class="section-title">Stay Connected</h2>

<a href="mailto:koewetzelblog@gmail.com">
📧 koewetzelblog@gmail.com
</a>

<a href="https://x.com/koewetzelblog" target="_blank">
𝕏 @koewetzelblog
</a>

</section>

<section>
<h2 class="section-title">Latest News</h2>

<div class="cards">
<div class="card">
<h3>New Tour Dates</h3>
<p>Check back soon for new announcements.</p>
</div>

<div class="card">
<h3>New Music</h3>
<p>Stay tuned for upcoming releases.</p>
</div>

<div class="card">
<h3>Behind The Scenes</h3>
<p>Exclusive fan content coming soon.</p>
</div>
</div>
</section>

<footer>
<p>© 2026 Koewetzelblog. All Rights Reserved.</p>
</footer>

</body>
</html>
