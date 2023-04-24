# electricity
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="home">
        <div class="container">
            <h1>Welcome to my Portfolio</h1>
            <p>I'm a web developer based in XYZ</p>
        </div>
    </section>
    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>I'm a passionate web developer with experience in HTML, CSS, and JavaScript. I love creating user-friendly and responsive websites that deliver great user experiences.</p>
        </div>
    </section>
    <section id="portfolio">
        <div class="container">
            <h2>My Portfolio</h2>
            <div class="portfolio-items">
                <div class="portfolio-item">
                    <img src="project1.jpg" alt="Project 1">
                    <h3>Project 1</h3>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut posuere fringilla ipsum, ac hendrerit elit malesuada nec.</p>
                </div>
                <div class="portfolio-item">
                    <img src="project2.jpg" alt="Project 2">
                    <h3>Project 2</h3>
                    <p>Nulla dignissim augue libero, at dignissim erat tincidunt eget. Aenean euismod dignissim ligula, a semper odio consequat in.</p>
                </div>
                <div class="portfolio-item">
                    <img src="project3.jpg" alt="Project 3">
                    <h3>Project 3</h3>
                    <p>Vestibulum ac nisl ut mauris fermentum volutpat. In eget enim ut mauris tristique maximus eget ut ante.</p>
                </div>
            </div>
        </div>
    </section>
    <section id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <form action="contact_form.php" method="post">
                <input type="text" name="name" placeholder="Name">
                <input type="email" name="email" placeholder="Email">
                <textarea name="message" placeholder="Message"></textarea>
                <input type="submit" value="Submit">
            </form>
        </div>
    </section>
    <footer>
        <div class="container">
            <p>&copy; 2023 My Portfolio. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>



