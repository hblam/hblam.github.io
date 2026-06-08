<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
}

body{
    font-family:'Montserrat',sans-serif;
    color:#222;
    background:#f5f5f5;
}

/* HERO */

.hero{
    height:100vh;
    background:
        linear-gradient(
            rgba(255,255,255,.45),
            rgba(255,255,255,.45)
        ),
        url("https://images.unsplash.com/photo-1507525428034-b723cf961d3e?w=2000");
    background-size:cover;
    background-position:center;
    position:relative;
}

.hero-content{
    position:absolute;
    top:35%;
    left:12%;
    transform:translateY(-50%);
}

.hero h1{
    font-size:90px;
    font-weight:300;
    letter-spacing:2px;
    text-transform:uppercase;
}

.divider{
    width:1200px;
    max-width:100%;
    height:10px;
    background:#6b8798;
    margin:20px 0 35px;
}

.chinese{
    font-size:55px;
    margin-bottom:25px;
}

.subtitle{
    font-size:22px;
    line-height:1.5;
}

.links{
    margin-top:20px;
}

.links a{
    color:#222;
    text-decoration:none;
    font-weight:600;
}

.links a:hover{
    text-decoration:underline;
}

.scroll{
    position:absolute;
    bottom:40px;
    left:50%;
    transform:translateX(-50%);
    font-size:50px;
    color:#666;
    animation:bounce 2s infinite;
}

@keyframes bounce{
    0%,100%{transform:translateX(-50%) translateY(0);}
    50%{transform:translateX(-50%) translateY(10px);}
}

/* ABOUT */

.about{
    background:#f4f4f4;
    padding:10px;
}

.about-container{
    max-width:1300px;
    margin:auto;
    display:grid;
    grid-template-columns:450px 1fr;
    gap:80px;
    align-items:center;
}

.profile{
    width:450px;
    height:450px;
    border-radius:50%;
    overflow:hidden;
    border:8px solid #5fa7e8;
    box-shadow:0 0 0 6px white;
}

.profile img{
    width:100%;
    height:100%;
    object-fit:cover;
}

.bio{
    font-size:20px;
    line-height:1.8;
}

.bio p{
    margin-bottom:25px;
}

.bio a{
    color:#222;
}

/* MOBILE */

@media(max-width:900px){

.hero h1{
    font-size:48px;
}

.divider{
    width:90%;
}

.chinese{
    font-size:35px;
}

.subtitle{
    font-size:18px;
}

.about-container{
    grid-template-columns:1fr;
    text-align:center;
}

.profile{
    width:300px;
    height:300px;
    margin:auto;
}

.bio{
    font-size:18px;
}
}

</style>
</head>
<body>

<section class="hero">

    <div class="hero-content">

        <h1>HANNAH BOU-LAI LAM</h1>

        <div class="divider"></div>

        <div class="chinese">林寶麗</div>

        <div class="subtitle">
           PhD Candidate (UAlberta)<br>
           MPhil (CUHK), A.B. (Harvard)
        </div>

        <div class="links">
            ▪ <a href="mailto:hblam@ualberta.ca">EMAIL</a>
            ▪ <a href="https://orcid.org/0000-0002-8526-3795">ORCID</a>
            ▪ <a href="https://docs.google.com/document/d/1vMRHykCBCrKMlwXysDEIk-SCK1UXIUdFdrKHcKQ017Y/edit?tab=t.0">CURRICULUM VITÆ</a>
        </div>

    </div>

    <a href="#about" class="scroll">⌄</a>

</section>

<section id="about" class="about">

    <div class="about-container">

        <div class="profile">
            <img src="https://lh3.googleusercontent.com/sitesv/AA5AbUBhOIFB9Sg4GMyIOce7s6wDlzMuvvyAr6auN_Jx0aKbqXYq8aG3cc9w0VtIiv3Z-LCf4ebJFHUubDPgskNormJO6ZjwmsFHsHMpImGI_pphSZKIXvTpgKgrZjt8QL5NmBw2v_c1sX4dIEzYrLtJmb1NfTUnyxk9kmYBDUGgxmFlH5KxyzU7oKte74eqB0nVePHuacsqQ2_pSeA=w1280" alt="">
        </div>

        <div class="bio">

            <p>
               <a href="https://www.visitguam.com/chamorro-culture/simple-chamorro-greetings/">Hafa Adai /hafa deɪ/</a> and welcome to my tiny corner of the worldwide web!
            </p>

            <p>
               I hail from the island of <a href="https://www.guampedia.com/about-guam/">Guåhan</a>, and am currently a PhD candidate in the Department of Linguistics at the <a href="https://www.ualberta.ca/index.html">University of Alberta</a>, 
               where I work with <a href="https://apps.ualberta.ca/directory/person/jparadis">Johanne Paradis</a>. 
               I received my Bachelor's in Linguistics at <a href="https://www.harvard.edu/">Harvard University</a>, 
               where I worked with <a href="https://psychology.fas.harvard.edu/people/jesse-snedeker">Jesse Snedeker</a>, 
               and my MPhil in Linguistics from the <a href="https://www.cuhk.edu.hk">Chinese University of Hong Kong</a>, 
               where I worked with <a href="https://ling.cuhk.edu.hk/people/faculty-linguistics/yip-virginia/">Virginia Yip</a>. 
            </p>

            <p>
               My research interests are in language acquisition, linguistic processing, metalinguistic judgments, and sources of individual differences for child and adult bilinguals. 
            </p>

        </div>

    </div>

</section>

</body>
</html>
