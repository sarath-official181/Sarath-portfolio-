<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>G. Sarath Raj | Professional Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
    scroll-behavior:smooth;
}

body{
    background:linear-gradient(135deg,#1a0f0f,#3d0c11,#111111);
    color:#f8f5f0;
}

/* Navigation */

nav{
    position:fixed;
    top:0;
    width:100%;
    background:rgba(20,20,20,0.95);
    backdrop-filter:blur(10px);
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:18px 8%;
    z-index:1000;
}

.logo{
    color:#d4af37;
    font-size:24px;
    font-weight:700;
}

nav ul{
    display:flex;
    list-style:none;
}

nav ul li{
    margin-left:25px;
}

nav ul li a{
    text-decoration:none;
    color:white;
    transition:0.3s;
}

nav ul li a:hover{
    color:#d4af37;
}

/* Hero */

.hero{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:100px 10%;
    background:
    linear-gradient(rgba(0,0,0,.75),rgba(0,0,0,.75)),
    url('https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?auto=format&fit=crop&w=1400&q=80');
    background-size:cover;
    background-position:center;
}

.hero-content{
    animation:fadeUp 1.2s ease;
}

.profile{
    width:180px;
    height:180px;
    border-radius:50%;
    border:4px solid #d4af37;
    margin:auto;
    display:flex;
    justify-content:center;
    align-items:center;
    font-size:60px;
    font-weight:bold;
    background:rgba(255,255,255,.08);
}

.hero h1{
    font-size:60px;
    margin-top:20px;
    color:#d4af37;
}

.hero h3{
    margin:15px 0;
    color:#f5deb3;
}

.hero p{
    max-width:750px;
    margin:auto;
    line-height:1.8;
    color:#ddd;
}

.btn{
    display:inline-block;
    margin-top:25px;
    padding:14px 35px;
    background:#d4af37;
    color:#111;
    text-decoration:none;
    border-radius:30px;
    font-weight:600;
    transition:.3s;
}

.btn:hover{
    transform:translateY(-5px);
}

/* Sections */

section{
    padding:90px 10%;
}

.section-title{
    text-align:center;
    color:#d4af37;
    font-size:40px;
    margin-bottom:40px;
}

.card{
    background:rgba(255,255,255,.05);
    backdrop-filter:blur(12px);
    border:1px solid rgba(255,255,255,.1);
    border-radius:20px;
    padding:30px;
    margin-bottom:25px;
    transition:.4s;
}

.card:hover{
    transform:translateY(-8px);
    box-shadow:0 10px 25px rgba(212,175,55,.2);
}

/* Statistics */

.stats{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
}

.stat{
    text-align:center;
}

.stat h2{
    color:#d4af37;
    font-size:40px;
}

/* Skills */

.skills{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:20px;
}

.skills ul{
    padding-left:20px;
    line-height:2;
}

/* Timeline */

.timeline{
    border-left:3px solid #d4af37;
    padding-left:25px;
}

.timeline-item{
    margin-bottom:30px;
}

.timeline-item h3{
    color:#d4af37;
}

/* Achievement Tags */

.badges{
    text-align:center;
}

.badge{
    display:inline-block;
    background:#5a3e09;
    padding:12px 20px;
    margin:10px;
    border-radius:25px;
}

/* Footer */

footer{
    text-align:center;
    padding:25px;
    background:#0a0a0a;
    color:#ccc;
}

/* Animation */

@keyframes fadeUp{
    from{
        opacity:0;
        transform:translateY(40px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}

</style>
</head>

<body>

<nav>
    <div class="logo">GSR</div>

    <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#education">Education</a></li>
        <li><a href="#experience">Experience</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#achievements">Achievements</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<section class="hero">

<div class="hero-content">

<div class="profile">SR</div>

<h1>G. Sarath Raj</h1>

<h3>MBA Finance & Marketing Student | Supervisor</h3>

<p>
Aspiring management professional with experience in supervision,
team coordination and business operations. Passionate about
finance, marketing, leadership and organizational excellence.
</p>

<a href="#about" class="btn">View Portfolio</a>

</div>

</section>

<section id="about">

<h2 class="section-title">Professional Profile</h2>

<div class="card">

<p>
Currently pursuing MBA in Finance and Marketing at
Hindustan Institute of Technology and Science.
Completed Bachelor of Commerce (B.Com – General) at 
Hindustan arts and science.

Experienced as a Supervisor at Softel Company,
developing leadership, communication, team management
and operational coordination skills.
</p>

</div>

</section>

<section>

<div class="stats">

<div class="card stat">
<h2>MBA</h2>
<p>Finance & Marketing</p>
</div>

<div class="card stat">
<h2>1+</h2>
<p>Years Leadership Experience</p>
</div>

<div class="card stat">
<h2>100%</h2>
<p>Professional Commitment</p>
</div>

<div class="card stat">
<h2>★</h2>
<p>Team Supervisor</p>
</div>

</div>

</section>

<section id="education">

<h2 class="section-title">Education</h2>

<div class="timeline">

<div class="timeline-item">
<h3>MBA – Finance & Marketing</h3>
<p>Hindustan Institute of Technology and Science</p>
</div>

<div class="timeline-item">
<h3>Bachelor of Commerce (B.Com – General)</h3>
<p>Undergraduate Degree</p>
</div>

</div>

</section>

<section id="experience">

<h2 class="section-title">Work Experience</h2>

<div class="card">

<h3>Supervisor – Softel Company</h3>

<p>
• Supervised daily operations and workforce activities.<br>
• Coordinated workflow and ensured productivity targets.<br>
• Managed communication between employees and management.<br>
• Assisted in operational planning and process improvement.<br>
• Maintained quality standards and team performance.
</p>

</div>

</section>

<section id="skills">

<h2 class="section-title">Core Competencies</h2>

<div class="skills">

<div class="card">
<h3>Finance</h3>
<ul>
<li>Financial Analysis</li>
<li>Budget Planning</li>
<li>Business Finance</li>
<li>Cost Management</li>
</ul>
</div>

<div class="card">
<h3>Marketing</h3>
<ul>
<li>Marketing Strategy</li>
<li>Market Research</li>
<li>Customer Relationship Management</li>
<li>Consumer Behaviour</li>
</ul>
</div>

<div class="card">
<h3>Leadership</h3>
<ul>
<li>Team Supervision</li>
<li>Decision Making</li>
<li>Problem Solving</li>
<li>Communication Skills</li>
</ul>
</div>

</div>

</section>

<section id="achievements">

<h2 class="section-title">Achievements</h2>

<div class="badges">

<span class="badge">🏆 Supervisor Experience</span>
<span class="badge">📈 MBA Finance & Marketing</span>
<span class="badge">🤝 Team Management</span>
<span class="badge">🎯 Leadership Skills</span>

</div>

</section>

<section id="contact">

<h2 class="section-title">Contact</h2>

<div class="card">

<p>📧 sarathraj181@gmail.com</p>
<p>📱 8754566728</p>
<p>📍 India</p>

</div>

</section>

<footer>
© 2026 G. Sarath Raj | Professional Corporate Portfolio
</footer>

</body>
</html>
