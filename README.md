
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Bruce Wayne's Portfolio - The Batman</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #222;
            color: white;
        }

        h1, h2, h3 {
            color: #f1c40f;
        }

        a {
            text-decoration: none;
            color: #3498db;
        }

        a:hover {
            text-decoration: underline;
        }

        header {
            background-color: #1a1a1a;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        nav {
            background-color: #333;
            overflow: hidden;
        }

        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }

        nav a:hover {
            background-color: #555;
        }

        .container {
            width: 80%;
            margin: 20px auto;
            overflow: hidden;
        }

        .intro, .projects, .contact {
            padding: 20px;
            background-color: #333;
            margin-bottom: 20px;
            border-radius: 8px;
        }

        .intro img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            border: 4px solid #f1c40f;
        }

        .project-item {
            display: flex;
            justify-content: space-between;
            margin-bottom: 15px;
        }

        .project-item h3 {
            margin: 0;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #1a1a1a;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>

<body>

    <!-- Header Section -->
    <header>
        <h1>Bruce Wayne's Portfolio</h1>
        <p>The Dark Knight, the protector of Gotham City</p>
    </header>

    <!-- Navigation Bar -->
    <nav>
        <a href="#intro">About Me</a>
        <a href="#projects">Skills & Achievements</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Main Content Section -->
    <div class="container">
        
        <!-- About Me Section -->
        <section id="intro" class="intro">
            <h2>About Bruce Wayne</h2>
            <!-- Image of Bruce Wayne -->
            <img src="https://www.zbrushcentral.com/uploads/default/original/4X/1/6/d/16de8e3e4757967ef6c6bdd795147d15cfd831e0.jpeg" alt="Bruce Wayne Photo">
            <p>I'm Bruce Wayne, the CEO of Wayne Enterprises by day and Gotham City's protector by night. I am the man behind the mask of the <strong>Batman</strong>, a vigilante dedicated to fighting crime, corruption, and injustice in Gotham City. Armed with wealth, intellect, and advanced technology, I use my skills and resources to safeguard the city I love.</p>
            <p>Learn more about Batman: <a href="https://en.wikipedia.org/wiki/Batman" target="_blank">Batman on Wikipedia</a></p>
        </section>

        <!-- Skills & Achievements Section -->
        <section id="projects" class="projects">
            <h2>Skills & Achievements</h2>

            <!-- Achievement 1 -->
            <div class="project-item">
                <div>
                    <h3>Master Detective</h3>
                    <p>Trained in investigative techniques and crime-solving. Known for unparalleled detective work, often solving complex cases in Gotham.</p>
                </div>
                <a href="#">View Case Studies</a>
            </div>

            <!-- Achievement 2 -->
            <div class="project-item">
                <div>
                    <h3>Combat Mastery</h3>
                    <p>Extensive training in hand-to-hand combat, martial arts, and various weaponry. My combat skills are considered some of the best in the world.</p>
                </div>
                <a href="#">View Training</a>
            </div>

            <!-- Achievement 3 -->
            <div class="project-item">
                <div>
                    <h3>Advanced Technology & Gadgets</h3>
                    <p>Created and utilized cutting-edge technology like the Batmobile, Batarangs, and the Bat-Signal. My resources are vital in combating crime effectively.</p>
                </div>
                <a href="#">See Gadgets</a>
            </div>

            <!-- Achievement 4 -->
            <div class="project-item">
                <div>
                    <h3>Leadership & Strategy</h3>
                    <p>Led the Justice League and other teams in the fight against global threats. Known for my strategic mind and ability to lead in the toughest situations.</p>
                </div>
                <a href="#">View Strategy Insights</a>
            </div>

        </section>

        <!-- Contact Section -->
        <section id="contact" class="contact">
            <h2>Contact Me</h2>
            <p>While I may not be reachable in the traditional sense, you can reach me through my trusted allies and channels.</p>
            <ul>
                <li>Email: <a href="mailto:bruce@wayneenterprises.com">bruce@wayneenterprises.com</a></li>
                <li>LinkedIn: <a href="https://www.linkedin.com/in/brucewayne">linkedin.com/in/brucewayne</a></li>
                <li>Twitter: <a href="https://twitter.com/Batman">twitter.com/Batman</a></li>
            </ul>
        </section>

    </div>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Bruce Wayne | Gotham City Protector | All rights reserved</p>
    </footer>

</body>

</html>


