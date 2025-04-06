<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Brian Mwalwala</title>
<link rel="stylesheet" href="styles.css" />
</head>
<body>

<header>
<nav class="navbar">
<div class="logo">Brian Mwalwala</div>
<ul class="nav-links">
<li><a href="#about">About</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>
</header>

<main class="main-container">
<section id="about" class="section about">
<h1>Hi, I'm Brian Mwalwala</h1>
<p>I'm a web developer and designer passionate about creating anew. Creating original designs that will make your jaw drop. Trust me, the best is yet to come.</p>
</section>

<section id="projects" class="section projects">
<h2>Projects</h2>
<div class="project-grid">
<div class="project-card">Project 1</div>
<div class="project-card">Project 2</div>
<div class="project-card">Project 3</div>
<div class="project-card">Project 4</div>
</div>
</section>

<section id="contact" class="section contact">
<h2>Contact Me</h2>
<p>Email: brian@cooldesigns.com</p>
</section>
</main>

<footer class="footer">
<p>&copy; 2025 Brian Mwalwala</p>
</footer>

</body>
</html>

/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Segoe UI", sans-serif;
  line-height: 1.6;
  background-color: #fdfdfd;
  color: #333;
}

/* Navbar */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 2rem;
  background-color: #1e1e1e;
  color: #fff;
}

.logo {
  font-size: 1.5rem;
  font-weight: bold;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 1.5rem;
}

.nav-links a {
  color: #fff;
  text-decoration: none;
  transition: color 0.3s;
}

.nav-links a:hover {
  color: #ffcc00;
}

/* Layout */
.main-container {
  padding: 2rem;
  display: flex;
  flex-direction: column;
  gap: 4rem;
}

.section {
  max-width: 1000px;
  margin: auto;
}

/* Projects Section */
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  margin-top: 1.5rem;
}

.project-card {
  background-color: #eee;
  padding: 1.5rem;
  border-radius: 8px;
  text-align: center;
}

/* Footer */
.footer {
  text-align: center;
  padding: 1rem;
  background-color: #1e1e1e;
  color: #fff;
}

/* Media Queries */
@media (max-width: 768px) {
  .navbar {
    flex-direction: column;
    align-items: flex-start;
  }

  .nav-links {
    flex-direction: column;
    gap: 1rem;
    margin-top: 1rem;
  }

  .main-container {
    padding: 1rem;
  }
}

@media (max-width: 480px) {
  .logo {
    font-size: 1.2rem;
  }

  .project-card {
    font-size: 0.9rem;
  }
}
