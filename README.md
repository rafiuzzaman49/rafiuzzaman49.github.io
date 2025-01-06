<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Website</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
            color: #333;
        }

        header {
            background: #f4f4f4;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin-bottom: 10px;
            color: #333;
        }

        header p {
            color: #555;
        }

        nav {
            margin-top: 20px;
        }

        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #007BFF;
            font-weight: bold;
        }

        nav a:hover {
            color: #0056b3;
        }

        section {
            padding: 20px;
            max-width: 800px;
            margin: 20px auto;
        }

        .section-title {
            font-size: 1.8em;
            margin-bottom: 10px;
            color: #333;
        }

        .project {
            margin-bottom: 20px;
        }

        .project-title {
            font-size: 1.4em;
            color: #007BFF;
        }

        .project-description {
            margin-top: 5px;
            color: #555;
        }

        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        footer p {
            margin: 0;
        }

        .contact {
            margin-top: 20px;
        }

        .contact a {
            color: #007BFF;
            text-decoration: none;
        }

        .contact a:hover {
            color: #0056b3;
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <p>Welcome to my portfolio website</p>
        <nav>
            <a href="#about">About</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="about">
        <h2 class="section-title">About Me</h2>
        <p>
            Hello! I am a passionate professional with experience in [your expertise]. I enjoy creating innovative solutions
            and sharing my work with the world.
        </p>
    </section>

    <section id="projects">
        <h2 class="section-title">Projects</h2>
        <div class="project">
            <h3 class="project-title">Project 1</h3>
            <p class="project-description">A brief description of the project goes here.</p>
        </div>
        <div class="project">
            <h3 class="project-title">Project 2</h3>
            <p class="project-description">A brief description of the project goes here.</p>
        </div>
    </section>

    <section id="contact">
        <h2 class="section-title">Contact</h2>
        <p>
            Feel free to reach out to me at
            <a href="mailto:your.email@example.com">your.email@example.com</a>
        </p>
        <div class="contact">
            <a href="https://www.linkedin.com" target="_blank">LinkedIn</a> |
            <a href="https://github.com" target="_blank">GitHub</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Your Name. All Rights Reserved.</p>
    </footer>
</body>
</html>
