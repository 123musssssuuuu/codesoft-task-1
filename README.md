<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
</head>
  style{
  ody {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    line-height: 1.6;
    background-color: #f9f9f9;
    color: #333;
    scroll-behavior: smooth;
}

a {
    text-decoration: none;
    color: inherit;
}

/* Header Styles */
header {
    background-color: #444;
    color: white;
    padding: 20px 30px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    position: sticky;
    top: 0;
    z-index: 1000;
}

header h1 {
    margin: 0;
    font-size: 1.8em;
    letter-spacing: 2px;
}
h2{
    text-align: center;
}
nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
}

nav ul li {
    margin-left: 25px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 1em;
    transition: color 0.3s, transform 0.2s;
}

nav ul li a:hover {
    color: #00bcd4;
    transform: scale(1.1);
}

/* Hero Section */
.hero {
    background: linear-gradient(to right, #00bcd4, #006064);
    color: white;
    padding: 100px 20px;
    text-align: center;
}

.hero h2 {
    margin: 0;
    font-size: 3em;
    font-weight: 700;
}

.hero p {
    margin-top: 15px;
    font-size: 1.3em;
}

/* Projects Section */
.projects {
    display: flex;
    flex-wrap: wrap;
    gap: 30px;
    justify-content: center;
    padding: 50px 20px;
}

.project {
    background: #fff;
    border: 1px solid #ddd;
    border-radius: 10px;
    padding: 25px;
    width: 300px;
    text-align: left;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s, box-shadow 0.3s;
}

.project:hover {
    transform: translateY(-10px);
    box-shadow: 0 8px 15px rgba(0, 0, 0, 0.2);
}

.project h3 {
    margin-top: 0;
    color: #333;
    font-size: 1.5em;
    margin-bottom: 10px;
}

.project p {
    font-size: 1em;
    color: #555;
    margin: 0;
}

/* Contact Section */
#contact {
    padding: 50px 20px;
    text-align: center;
}

#contact h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
}

#contact p {
    font-size: 1.1em;
}

/* Footer */
footer {
    background-color: #444;
    color: white;
    text-align: center;
    padding: 15px 0;
    margin-top: 50px;
}

footer p {
    margin: 0;
    font-size: 0.9em;
}

  }
<body>
  
    <header>
        <h1>My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero" id="about">
        <h2>Hello, I'm Muskan!</h2>
        <p>A passionate developer eager to learn and grow.</p>
    </section>

    <section id="projects">
        <h2>My Projects</h2>
        <div class="projects">
            <div class="project">
                <h3>Shopping Bill Project</h3>
                <p>A project that calculates shopping bills and provides discounts above Rs 1000.</p>
            </div>
            <div class="project">
                <h3>Netflix Clone</h3>
                <p>A clone of Netflix showcasing my front-end development skills.</p>
            </div>
            <div class="project">
                <h3>An image text translator website</h3>
                <p>A website that converts the text of any image into any language.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:muskanbansal0304@gmail.com">muskan@example.com</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Muskan Bansal. All rights reserved.</p>
    </footer>

    script{
    console.log("Welcome to my portfolio!");
    }
</body>
</html>
