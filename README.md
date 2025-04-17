# abc.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <div class="container">
            <h1>Soham Patel</h1>
            <p>Web Developer | Designer | Freelancer</p>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <img src="cv.jpg" alt="Profile Photo">
            <p>Hello! I'm a passionate web developer with expertise in HTML, CSS, JavaScript, and modern frameworks.</p>
        </div>
    </section>

    <section id="projects">
        <div class="container">
            <h2>My Projects</h2>
            <div class="projects-grid">
                <div class="project">
                    <img src="pr1.jpg" alt="Project 1">
                    <h3>Project 1</h3>
                    <p>A Water-Level Indicator.</p>
                </div>
                <div class="project">
                    <img src="pr2.png" alt="Project 2">
                    <h3>Project 2</h3>
                    <p> My CV.</p>
                </div>
                            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <p>Email: sohampatel@gmail.com</p>
            <p>Phone: +91 9346174822</p>
            <p>LinkedIn: linkedin.com/in/sohamp</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Soham Patel. All rights reserved.</p>
    </footer>

</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #0A2240;
    text-align: center;
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
    color: #39FF14 ;
}

header {
    background:#0A2240 ;
    color: white;
    padding: 20px 0;
}

nav {
    background: #0E5204;
    padding: 10px 0;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

section {
    padding: 50px 0;
    background: #003153;
    margin: 20px 0;
}

h2 {
    color: white;
}

img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
}

.projects-grid {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}

.project {
    background: #0065AB;
    padding: 20px;
    width: 250px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    text-align: center;
}

.project img {
    width: 100%;
    height: auto;
}

footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}
