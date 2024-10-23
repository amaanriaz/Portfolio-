# Portfolio-
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="intro">
            <h1>Hi, I'm Your Name</h1>
            <p>Frontend Developer</p>
            <button>Download CV</button>
        </div>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Brief description about yourself.</p>
    </section>

    <section id="skills">
        <h2>My Skills</h2>
        <div class="skill">
            <p>HTML</p>
            <div class="progress-bar" style="width: 90%;"></div>
        </div>
        <div class="skill">
            <p>CSS</p>
            <div class="progress-bar" style="width: 85%;"></div>
        </div>
        <!-- Add more skills here -->
    </section>

    <section id="experience">
        <h2>My Journey</h2>
        <!-- Add your education and experience -->
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form action="submit_form.php" method="POST">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message"></textarea>
            <button type="submit">Send</button>
        </form>
    </section>
</body>
</html>
