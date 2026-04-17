<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Imaad Danish | Developer Portfolio</title>

<style>

body{
margin:0;
font-family:Arial, Helvetica, sans-serif;
background:#0f172a;
color:white;
line-height:1.6;
}

/* Navigation */

nav{
position:fixed;
top:0;
width:100%;
background:#020617;
padding:15px;
text-align:center;
z-index:1000;
}

nav a{
color:white;
margin:0 20px;
text-decoration:none;
font-weight:bold;
}

/* Hero Section */

header{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
background:linear-gradient(120deg,#2563eb,#9333ea);
}

header h1{
font-size:60px;
margin:0;
}

header p{
font-size:22px;
margin-top:10px;
}

/* Sections */

section{
padding:80px 10%;
}

h2{
font-size:34px;
margin-bottom:20px;
}

/* Skills */

.skills span{
background:#1e293b;
padding:10px 15px;
border-radius:6px;
margin:5px;
display:inline-block;
}

/* Projects */

.projects{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:#1e293b;
padding:20px;
border-radius:12px;
transition:0.3s;
}

.card:hover{
transform:translateY(-8px);
}

/* Contact Buttons */

.contact-buttons{
margin-top:20px;
}

.contact-buttons a{
text-decoration:none;
}

.contact-buttons button{
background:#3b82f6;
border:none;
padding:12px 20px;
margin:10px;
border-radius:8px;
color:white;
font-size:16px;
cursor:pointer;
transition:0.3s;
}

.contact-buttons button:hover{
background:#2563eb;
}

/* Footer */

footer{
background:#020617;
text-align:center;
padding:30px;
}

</style>
</head>

<body>

<nav>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</nav>

<header>
<h1>Imaad Danish</h1>
<p>Student • Robotics Enthusiast • Developer</p>
</header>

<section id="about">
<h2>About Me</h2>
<p>
I am passionate about technology, robotics, and building innovative software.
I enjoy experimenting with artificial intelligence, developing apps,
and learning how technology can solve real-world problems.
</p>
</section>

<section id="skills">
<h2>Skills</h2>

<div class="skills">
<span>Python</span>
<span>Flutter</span>
<span>Web Development</span>
<span>AI Experiments</span>
<span>Robotics</span>
</div>

</section>

<section id="projects">
<h2>Projects</h2>

<div class="projects">

<div class="card">
<h3>AI Chatbot</h3>
<p>A chatbot experiment using machine learning models.</p>
</div>

<div class="card">
<h3>Security Camera App</h3>
<p>A phone-to-phone monitoring camera system.</p>
</div>

<div class="card">
<h3>Automation Tools</h3>
<p>Scripts and tools that automate tasks.</p>
</div>

</div>

</section>

<section id="contact">

<h2>Contact Me</h2>

<p>You can reach me using the buttons below.</p>

<div class="contact-buttons">

<a href="mailto:khaleekahmand@gmail.com">
<button>Email Me</button>
</a>

<a href="https://github.com/imaaddanish-code178" target="_blank">
<button>GitHub</button>
</a>

<a href="https://wa.me/919997554431" target="_blank">
<button>WhatsApp</button>
</a>

</div>

</section>

<footer>
<p>© 2026 Imaad Danish. All Rights Reserved.</p>
</footer>

</body>
</html>
