index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>John Exodus D. Hernandez | Developer Portfolio</title>
  <link rel="stylesheet" href="style/main.css" />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet" />
</head>
<body>

  <header class="site-header">
    <nav class="nav-container">
      <a href="#about" class="nav-logo">ExodusWorks</a>
      <ul class="nav-links">
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#tools">Tools</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <header class="landing">
    <img
      src="https://wallpapers.com/images/featured/black-and-white-aesthetic-l4bjrhl8d4u3ddd7.jpg"
      alt="Cover Photo"
      class="cover-photo"
      loading="lazy"
    />
    <img
      src="https://scontent.fcrk3-2.fna.fbcdn.net/v/t39.30808-6/425409150_2665160770311543_7752999637957837098_n.jpg?stp=cp6_dst-jpg_tt6&_nc_cat=103&ccb=1-7&_nc_sid=6ee11a&_nc_ohc=PEPKH3PsVi0Q7kNvwGcc7A1&_nc_oc=Admd1raZRZ2cIveAaDA5jY88FfWEoRI3CDCpnYETW2p9TItqKbP6x3SDBKlr23Yr9K8&_nc_zt=23&_nc_ht=scontent.fcrk3-2.fna&_nc_gid=nq6w1ig5HAdvCuyBNW3g8w&oh=00_AfLLpPjmIk51AOHsnuxCxwFGJe6MwlTxv-8nx-e9YD4SvA&oe=6833846D"
      alt="Profile"
      class="profile-pic"
      loading="lazy"
    />
    <h1>ExodusWorks</h1>
    <p>"Code. Create. Conquer."</p>
  </header>

  <section class="about" id="about" aria-label="About Me">
    <h2>About Me</h2>
    <p>Hello! I am John Exodus D. Hernandez, a 19-year-old male residing in Candaba, Pampanga. I am a first-year student currently taking the Bachelor of Science in Information Technology (BSIT) course at the University of the Assumption. I was born on March 16, 2006. Growing up, I always had an interest in technology, such as computers. In the near future, I dream of becoming a web developer.</p>
  </section>

  <section class="projects" id="projects" aria-label="My Projects">
    <h2>My Project(s)</h2>
    <div class="project-cards">
      <div class="card">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQbOXibjcPmO5Lrv7WJUWl8BSGsmE4G8vAHFA&s" alt="Picture" loading="lazy" />
        <h3>Simple Portfolio Site</h3>
        <a href="https://www.figma.com/proto/058mEkrQ25SvlbmtHkGFKz/midterm-exam?node-id=3-4&starting-point-node-id=3%3A4" target="_blank" class="btn" rel="noopener noreferrer">View Project</a>
      </div>
    </div>
  </section>

  <section class="tools" id="tools" aria-label="Tools I Use">
  <h2>Tools I Use</h2>
  <div class="tool-icons">
    <div class="tool">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5" />
      <span>HTML</span>
    </div>
    <div class="tool">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3" />
      <span>CSS</span>
    </div>
    <div class="tool">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" />
      <span>Python</span>
    </div>
    <div class="tool">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" alt="VS Code" />
      <span>VS Code</span>
    </div>
    <div class="tool">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="C++" />
      <span>C++</span>
    </div>
  </div>
</section>


  <section class="contact" id="contact" aria-label="Contact Me">
  <h2>Contact Me</h2>
  <div class="socials">
    <a href="https://www.facebook.com/johnexodus.hernandez.94" target="_blank" rel="noopener noreferrer" aria-label="Facebook profile">
      <img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook Icon" class="social-icon" />
      Facebook
    </a>
    <a href="https://www.instagram.com/exoduszx16/" target="_blank" rel="noopener noreferrer" aria-label="Instagram profile">
      <img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram Icon" class="social-icon" />
      Instagram
    </a>
    <a href="https://x.com/Exodus134704" target="_blank" rel="noopener noreferrer" aria-label="Twitter profile">
      <img src="https://freepnglogo.com/images/all_img/1725374683twitter-x-logo.png" alt="X Icon" class="social-icon" />
      X
    </a>
    <a href="https://www.tiktok.com/@exoduszx16" target="_blank" rel="noopener noreferrer" aria-label="TikTok profile">
      <img src="https://cdn-icons-png.flaticon.com/512/3046/3046121.png" alt="TikTok Icon" class="social-icon" />
      TikTok
    </a>
  </div>
</section>


  <footer class="site-footer">
    <p>&copy; 2025 John Exodus D. Hernandez. All rights reserved.</p>
  </footer>

</body>
</html>











main.css
html, body {
  margin: 0;
  padding: 0;
  font-family: 'Inter', sans-serif;
  background-color: #fff;
  color: #111;
  height: 100%;
  padding-top: 65px;
}

.site-header {
  position: fixed;
  top: 0;
  width: 100%;
  background-color: #000;
  color: white;
  z-index: 1000;
  box-shadow: 0 2px 8px rgba(0,0,0,0.4);
}

.nav-container {
  max-width: 1000px;
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 1rem 1.5rem;
}

.nav-logo {
  font-weight: 700;
  font-size: 1.8rem;
  letter-spacing: 3px;
  color: white;
  text-decoration: none;
  user-select: none;
  text-transform: uppercase;
  transition: color 0.3s ease;
}

.nav-logo:hover {
  color: #888;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 2.5rem;
  margin: 0;
  padding: 0;
}

.nav-links li a {
  color: white;
  text-decoration: none;
  font-weight: 600;
  letter-spacing: 1.5px;
  text-transform: uppercase;
  position: relative;
  padding-bottom: 4px;
  transition: color 0.3s ease;
  user-select: none;
}

.nav-links li a::after {
  content: "";
  position: absolute;
  width: 0%;
  height: 2px;
  bottom: 0;
  left: 0;
  background-color: white;
  transition: width 0.3s ease;
}

.nav-links li a:hover,
.nav-links li a:focus {
  color: #ddd;
}

.nav-links li a:hover::after,
.nav-links li a:focus::after {
  width: 100%;
}

header.landing {
  position: relative;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-end;
  height: 75vh;
  width: 100vw;
  background-color: #000;
  color: #fff;
  overflow: hidden;
  text-align: center;
  padding-bottom: 3rem;
}

.cover-photo {
  position: absolute;
  top: 0; left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  filter: brightness(0.7);
  z-index: 1;
  user-select: none;
}

.profile-pic {
  position: relative;
  width: 250px;
  height: 250px;
  border-radius: 50%;
  border: 5px solid #fff;
  background-color: #fff;
  margin-bottom: 1.5rem;
  z-index: 2;
  box-shadow: 0 0 12px rgba(255 255 255 / 0.6);
}

header.landing h1,
header.landing p {
  position: relative;
  z-index: 2;
  margin: 0;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 2px;
}

header.landing h1 {
  font-size: 3rem;
  margin-top: 0.8rem;
}

header.landing p {
  font-size: 1.5rem;
  margin-top: 0.5rem;
  font-weight: 400;
  letter-spacing: 1px;
  opacity: 0.8;
}

section {
  padding: 3rem 2rem;
  max-width: 600px;
  margin: 3rem auto;
  text-align: center;
  background-color: #f0f0f5;
  border-radius: 15px;
  box-shadow: 0 8px 20px rgba(0,0,0,0.1);
}

h2 {
  color: #111;
  margin-bottom: 2rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 2px;
  font-size: 2.5rem;
}

.about p {
  font-size: 1.2rem;
  line-height: 1.6;
  color: #222;
  font-weight: 500;
  user-select: text;
}

.projects {
  max-width: 600px;
  margin: 3rem auto;
  padding: 3rem 2rem;
  background-color: #f0f0f5;
  border-radius: 15px;
  box-shadow: 0 8px 20px rgba(0,0,0,0.1);
  text-align: center;
}

.projects h2 {
  font-size: 2.5rem;
  font-weight: 700;
  letter-spacing: 2px;
  text-transform: uppercase;
  margin-bottom: 2rem;
  color: #111;
}

.project-cards {
  display: flex;
  flex-direction: column;
  gap: 2rem;
  align-items: center;
  width: 100%;
}

.card {
  background-color: #fff;
  border: 2px solid #ccc;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
  width: 100%;
  max-width: 400px;
  padding-bottom: 1.5rem;
  text-align: center;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  cursor: default;
}

.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 25px rgba(0,0,0,0.15);
}

.card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-bottom: 3px solid #000;
  border-radius: 12px 12px 0 0;
}

.card h3 {
  margin: 1rem 0 0.8rem;
  font-weight: 700;
  color: #111;
  font-size: 1.5rem;
}

.btn {
  background-color: #000;
  color: #fff;
  padding: 0.6rem 1.4rem;
  text-decoration: none;
  border-radius: 8px;
  display: inline-block;
  font-weight: 700;
  transition: background-color 0.3s ease;
  letter-spacing: 0.7px;
}

.btn:hover {
  background-color: #222;
}

.socials {
  display: flex;
  justify-content: center;
  gap: 4rem;
  margin-top: 1rem;
  flex-wrap: wrap;
}

.socials a {
  display: flex;
  align-items: center;
  gap: 1.2rem;
  text-decoration: none;
  color: #111;
  font-weight: 700;
  font-size: 2rem; /* increased */
  transition: color 0.3s ease;
  user-select: none;
}

.socials a:hover {
  color: #0073e6;
  text-decoration: underline;
}

.social-icon {
  width: 64px;  /* increased */
  height: 64px; /* increased */
  filter: none;
}

@media (max-width: 600px) {
  .project-cards {
    flex-direction: column;
    align-items: center;
  }

  header.landing h1 {
    font-size: 2.3rem;
  }

  header.landing p {
    font-size: 1.2rem;
  }

  .profile-pic {
    width: 140px;
    height: 140px;
  }

  .nav-container {
    padding: 1rem;
  }

  .nav-links {
    gap: 1rem;
  }

  .nav-logo {
    font-size: 1.5rem;
  }

  section {
    max-width: 90%;
    padding: 2rem 1rem;
  }

  .card {
    width: 90%;
    max-width: 350px;
  }
}

.site-footer {
  background-color: #000;
  color: #fff;
  text-align: center;
  padding: 2rem 1rem;
  margin-top: 3rem;
  font-size: 1rem;
  border-top: 1px solid #333;
}

.site-footer p {
  margin: 0 0 1rem;
  font-weight: 500;
  letter-spacing: 1px;
}

.footer-socials {
  display: flex;
  justify-content: center;
  gap: 2rem;
  flex-wrap: wrap;
}

.footer-socials span {
  color: #ccc;
  font-weight: 600;
}

.tools {
  background-color: #f0f0f5;
  border-radius: 15px;
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
  padding: 3rem 2rem;
  max-width: 700px;
  margin: 3rem auto;
  text-align: center;
}

.tool-icons {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 3rem;
  margin-top: 2rem;
}

.tool {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 110px; /* increased */
  gap: 0.6rem;
}

.tool img {
  width: 80px;  /* increased */
  height: 80px; /* increased */
  object-fit: contain;
  transition: transform 0.3s ease;
}

.tool span {
  margin-top: 0.6rem;
  font-weight: 700;
  font-size: 1.2rem; /* increased */
  color: #333;
}
