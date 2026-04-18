<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mohd. Imaad Danish | Robotics Portfolio</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif}
body{
  background:linear-gradient(270deg,#020617,#0f172a,#020617);
  background-size:600% 600%;
  animation:bgMove 12s ease infinite;
  color:#e5e7eb;
  scroll-behavior:smooth;
}
@keyframes bgMove{0%{background-position:0%}50%{background-position:100%}100%{background-position:0%}}

header{position:fixed;width:100%;top:0;background:rgba(0,0,0,0.5);backdrop-filter:blur(12px);padding:15px 0;z-index:1000}
nav{display:flex;justify-content:center;gap:30px}
nav a{color:#38bdf8;text-decoration:none;font-weight:500;position:relative}
nav a::after{content:'';position:absolute;width:0;height:2px;background:#38bdf8;left:0;bottom:-4px;transition:.3s}
nav a:hover::after{width:100%}

section{padding:100px 20px;max-width:1100px;margin:auto}

.hero{height:100vh;display:flex;flex-direction:column;justify-content:center;align-items:center;text-align:center}
.hero h1{font-size:3.8rem;background:linear-gradient(90deg,#38bdf8,#22c55e);-webkit-background-clip:text;color:transparent}
.hero p{margin-top:10px;color:#94a3b8;font-size:1.3rem}

.typing{border-right:2px solid #38bdf8;white-space:normal;max-width:90%}

.btn{
  margin-top:20px;
  padding:12px 30px;
  border-radius:30px;
  text-decoration:none;
  display:inline-block;
  transition:.3s;
}
.btn:hover{transform:translateY(-3px) scale(1.05);box-shadow:0 0 20px rgba(56,189,248,0.6)}

h2{margin-bottom:25px;color:#38bdf8;font-size:2rem;text-align:center}

.card{
  background:rgba(255,255,255,0.05);
  backdrop-filter:blur(12px);
  padding:25px;
  border-radius:20px;
  margin-bottom:20px;
  transition:.4s;
  border:1px solid rgba(255,255,255,0.08);
}
.card:hover{
  transform:translateY(-10px) scale(1.02);
  box-shadow:0 10px 40px rgba(56,189,248,0.25);
}

.skills{display:flex;flex-wrap:wrap;justify-content:center}
.skills span{
  background:#1f2937;
  padding:10px 18px;
  margin:6px;
  border-radius:25px;
  transition:.3s;
}
.skills span:hover{background:#38bdf8;color:#020617}

footer{text-align:center;padding:25px;background:#020617;color:#94a3b8}

.fade{opacity:0;transform:translateY(50px);transition:1s}
.show{opacity:1;transform:translateY(0)}

</style>
</head>
<body>

<header>
<nav>
<a href="#">Home</a>
<a href="#about">About</a>
<a href="#projects">Projects</a>
<a href="#skills">Skills</a>
<a href="#contact">Contact</a>
</nav>
</header>

<section class="hero">
<h1>Mohd. Imaad Danish</h1>
<p class="typing" id="typing"></p>
<a href="#projects" class="btn" style="background:#38bdf8;color:#020617;">View Projects</a>
</section>

<section id="about" class="fade">
<h2>About Me</h2>
<div class="card">
<p>I am a robotics enthusiast passionate about building intelligent systems using Arduino, IoT, and embedded technologies. I create real-world solutions through automation and constantly explore new innovations in AI and robotics.</p>
</div>
</section>

<section id="projects" class="fade">
<h2>Projects</h2>
<div class="card"><h3>Line Following Robot</h3><p>Autonomous robot using IR sensors with real-time path correction.</p></div>
<div class="card"><h3>Obstacle Avoiding Robot</h3><p>Smart navigation system using ultrasonic sensors.</p></div>
<div class="card"><h3>Smart Home Automation</h3><p>IoT-based control system for smart living.</p></div>
<div class="card"><h3>Bluetooth/WiFi Controlled Car</h3><p>Wireless controlled robotic car with mobile interface.</p></div>
</section>

<section id="skills" class="fade">
<h2>Skills</h2>
<div class="skills">
<span>Arduino</span><span>C++</span><span>Python</span><span>IoT</span><span>Embedded Systems</span><span>Sensors</span>
</div>
</section>

<section id="contact" class="fade">
<h2>Contact</h2>
<div style="background:rgba(255,255,255,0.05);padding:30px;border-radius:20px;max-width:500px;margin:auto;text-align:center;backdrop-filter:blur(12px);">
<div style="display:flex;flex-direction:column;gap:14px;align-items:center;">
<a href="mailto:khaleekahmand@gmail.com" class="btn" style="background:#22c55e;color:#022c22;">📧 Email</a>
<a href="https://github.com/imaaddanish-code178" target="_blank" class="btn" style="background:#111827;color:#e5e7eb;">💻 GitHub</a>
<a href="https://youtube.com/@cryonixvfxofficial?si=AfWvN7qXdPMegrHl" target="_blank" class="btn" style="background:#ef4444;color:white;">▶️ YouTube</a>
</div>
</div>
</section>

<footer>
<p>© 2026 Mohd. Imaad Danish | Next Level Portfolio</p>
</footer>

<script>
// (Your JS remains unchanged)
</script>

</body>
</html>
