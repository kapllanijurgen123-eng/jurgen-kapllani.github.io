Pillbox Hill Bean Machine	
A place for you to enjoy your remaining of the day.
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Showcase</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
    <nav>
        <h1 class="logo">MyPortfolio</h1>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<section id="home" class="hero">
    <h2>Welcome to My Showcase</h2>
    <p>I build websites and creative projects.</p>
    <button>View My Work</button>
</section>

<section id="projects" class="projects">
    <h2>Projects</h2>

    <div class="project-grid">
        <div class="card">
            <h3>Project 1</h3>
            <p>Website design project.</p>
        </div>

        <div class="card">
            <h3>Project 2</h3>
            <p>Web application UI.</p>
        </div>

        <div class="card">
            <h3>Project 3</h3>
            <p>Landing page design.</p>
        </div>
    </div>
</section>

<section id="about" class="about">
    <h2>About Me</h2>
    <p>I am a web developer learning HTML, CSS and JavaScript.</p>
</section>

<section id="contact" class="contact">
    <h2>Contact</h2>
    <p>Email: example@email.com</p>
</section>

<footer>
    <p>© 2026 MyPortfolio</p>
</footer>

</body>
</html>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial;
}

body{
background:#111;
color:white;
}

/* NAVBAR */

nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
background:#000;
}

nav ul{
display:flex;
list-style:none;
gap:20px;
}

nav a{
text-decoration:none;
color:white;
}

/* HERO */

.hero{
height:80vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
}

.hero h2{
font-size:48px;
margin-bottom:10px;
}

.hero button{
margin-top:20px;
padding:10px 20px;
border:none;
background:#ff4c4c;
color:white;
cursor:pointer;
}

/* PROJECTS */

.projects{
padding:80px 10%;
text-align:center;
}

.project-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
margin-top:40px;
}

.card{
background:#1e1e1e;
padding:30px;
border-radius:10px;
transition:0.3s;
}

.card:hover{
transform:translateY(-5px);
}

/* ABOUT */

.about{
padding:80px 10%;
text-align:center;
background:#181818;
}

/* CONTACT */

.contact{
padding:80px 10%;
text-align:center;
}

/* FOOTER */

footer{
text-align:center;
padding:20px;
background:#000;
}