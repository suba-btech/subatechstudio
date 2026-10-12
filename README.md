<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Subathradevi R | Portfolio</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    font-family: 'Segoe UI', Arial, sans-serif;
    background: #080d1c;
    color: #f5f7ff;
    line-height: 1.6;
}

header {
    position: sticky;
    top: 0;
    z-index: 10;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 18px 8%;
    background: rgba(8, 13, 28, 0.95);
    border-bottom: 1px solid #252c45;
}

.logo {
    font-size: 23px;
    font-weight: bold;
    color: #72e5ff;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
    font-size: 14px;
}

nav a:hover {
    color: #72e5ff;
}

section {
    padding: 75px 8%;
}

.hero {
    min-height: 88vh;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 45px;
    flex-wrap: wrap;
    background:
        radial-gradient(circle at 85% 35%, #20265a 0, transparent 35%);
}

.hero-text {
    flex: 1;
    min-width: 260px;
}

.tag {
    color: #72e5ff;
    letter-spacing: 2px;
    font-size: 13px;
    font-weight: bold;
}

h1 {
    font-size: clamp(36px, 5vw, 58px);
    line-height: 1.2;
    margin: 18px 0;
}

h1 span {
    color: #72e5ff;
}

.hero p {
    color: #b8c1d9;
    max-width: 570px;
    margin-bottom: 25px;
}

.profile-photo {
    width: 280px;
    height: 340px;
    padding: 5px;
    border-radius: 150px 150px 35px 35px;
    background: linear-gradient(135deg, #72e5ff, #9865ff);
    box-shadow: 0 0 40px #343b7755;
    overflow: hidden;
    flex-shrink: 0;
}

.profile-photo img {
    width: 100%;
    height: 100%;
    display: block;
    object-fit: cover;
    object-position: center top;
    border-radius: inherit;
}

.btn {
    display: inline-block;
    padding: 11px 22px;
    border-radius: 8px;
    background: #72e5ff;
    color: #08101e;
    text-decoration: none;
    font-weight: bold;
    margin: 5px 8px 5px 0;
}

.btn-outline {
    background: transparent;
    border: 1px solid #72e5ff;
    color: #72e5ff;
}

.section-title {
    font-size: 32px;
    margin-bottom: 25px;
}

.section-title span {
    color: #72e5ff;
}

.about-text {
    color: #c2c9dc;
    max-width: 850px;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
}

.card {
    padding: 24px;
    border: 1px solid #29314e;
    background: #11182b;
    border-radius: 16px;
    transition: 0.25s;
}

.card:hover {
    transform: translateY(-5px);
    border-color: #72e5ff;
}

.card h3 {
    color: #72e5ff;
    margin-bottom: 10px;
}

.card p, .card li {
    color: #bdc6dc;
    font-size: 14px;
}

.skills {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
}

.skills span {
    padding: 10px 17px;
    background: #151e35;
    color: #72e5ff;
    border: 1px solid #343e60;
    border-radius: 30px;
}

ul {
    padding-left: 18px;
}

#contact a:not(.btn) {
    color: #72e5ff;
    overflow-wrap: anywhere;
}

footer {
    text-align: center;
    padding: 25px;
    color: #aeb8d0;
    border-top: 1px solid #252c45;
}

@media (max-width: 700px) {
    header {
        padding: 15px 5%;
        flex-direction: column;
        gap: 12px;
    }

    nav {
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        gap: 12px;
    }

    nav a {
        margin: 0;
    }

    section {
        padding: 55px 6%;
    }

    .hero {
        justify-content: center;
        text-align: center;
    }

    .hero-text {
        order: 2;
    }

    .profile-photo {
        order: 1;
        width: 230px;
        height: 280px;
    }

    .hero p {
        margin-left: auto;
        margin-right: auto;
    }
}
</style>
</head>

<body>

<header>
    <div class="logo">Suba.dev</div>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#certificates">Certificates</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero" id="home">
    <div class="hero-text">
        <div class="tag">WELCOME TO MY PORTFOLIO</div>

        <h1>Hi, I'm <span>Subathradevi R</span></h1>

        <h2>AI &amp; DS Student</h2>

        <p>
            I am an Artificial Intelligence and Data Science student
            passionate about programming, web development, and
            exploring new technologies. I enjoy learning new skills
            and building useful projects.
        </p>

        <a class="btn" href="#projects">Explore My Work</a>
        <a class="btn btn-outline" href="#contact">Contact Me</a>
    </div>

    <div class="profile-photo">
        <img src="profile.jpg" alt="Subathradevi R profile photo">
    </div>
</section>

<section id="about">
    <h2 class="section-title">About <span>Me</span></h2>

    <p class="about-text">
        I am Subathradevi R, an AI &amp; DS student at
        VSB Engineering College of Technical Campus.
        I am interested in programming, artificial intelligence,
        data science, and web development. I am continuously
        improving my technical knowledge through coding practice,
        certifications, and project development.
    </p>

    <br>

    <div class="grid">
        <div class="card">
            <h3>Education</h3>
            <p>Artificial Intelligence and Data Science (AI&amp;DS)</p>
            <p>VSB Engineering College of Technical Campus</p>
            <p>Expected Graduation: 2029</p>
        </div>

        <div class="card">
            <h3>Internship</h3>
            <p>Web Development Intern at Frenzo</p>
            <p>Learning and applying web development skills.</p>
        </div>
    </div>
</section>

<section id="skills">
    <h2 class="section-title">My <span>Skills</span></h2>

    <div class="skills">
        <span>Python</span>
        <span>Java</span>
        <span>HTML</span>
        <span>CSS</span>
    </div>
</section>

<section id="projects">
    <h2 class="section-title">My <span>Projects</span></h2>

    <div class="grid">
        <div class="card">
            <h3>Blood Donor Web Application</h3>
            <p>
                A web application designed to help users find
                blood donors and access donor information easily.
            </p>
            <p><strong>Technologies:</strong> HTML, CSS, PHP, MySQL</p>
        </div>

        <div class="card">
            <h3>Coding Practice Programs</h3>
            <p>
                A collection of programming exercises completed
                to improve problem-solving and coding skills.
            </p>
            <p><strong>Languages:</strong> Java, Python</p>
        </div>
    </div>
</section>

<section id="certificates">
    <h2 class="section-title">My <span>Certificates</span></h2>

    <div class="grid">
        <div class="card">
            <h3>NPTEL</h3>
            <p>Programming in Python</p>
        </div>

        <div class="card">
            <h3>HP</h3>
            <p>Data Analytics</p>
        </div>

        <div class="card">
            <h3>Infosys</h3>
            <p>Basics of Python</p>
        </div>

        <div class="card">
            <h3>CSC</h3>
            <p>Diploma</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2 class="section-title">Contact <span>Me</span></h2>

    <div class="card">
        <p><strong>Email:</strong>
            <a href="mailto:zuba8419@gmail.com">zuba8419@gmail.com</a>
        </p>

        <p><strong>LinkedIn:</strong>
            <a href="https://www.linkedin.com/in/subathradevi-r-389392420"
               target="_blank" rel="noopener noreferrer">
               Visit My LinkedIn
            </a>
        </p>

        <p><strong>GitHub:</strong>
            <a href="https://github.com/suba-btech"
               target="_blank" rel="noopener noreferrer">
               Visit My GitHub
            </a>
        </p>

        <p><strong>LeetCode:</strong>
            <a href="https://leetcode.com/u/subathradevi_R"
               target="_blank" rel="noopener noreferrer">
               Visit My LeetCode
            </a>
        </p>
    </div>
</section>

<footer>
    <p>© 2026 Subathradevi R | AI &amp; DS Student Portfolio</p>
</footer>

</body>
</html>
