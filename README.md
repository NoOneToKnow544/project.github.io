<html>
<head>
    <title>Portfolio</title>
    <style>
        
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            background-color: #f4f4f4;
            color: #333;
        }

        body {
            background-image: url('bg.jpg');
            background-size: cover;
            background-position: center;
            color: #333;
            padding: 20px;
            padding-top: 100px;
        }

        /* Header Styles */
        header {
            background-image: url('ict wallpaper.jpg');
            background-size: cover;
            background-position: center;
            color: #fff;
            padding: 40px;
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
        }

        nav {
            display: flex;
            justify-content: center;
            align-items: initial;
            position: relative;
        }

        .logo a {
            color: #fff;
            text-decoration: none;
            font-size: 50px;
            font-weight: bold;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            position: absolute;
            right: 20px;
        }

        nav li {
            margin-left: 20px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
        }

        /* Main Content Styles */
        main {
            display: flex;
            justify-content: center;
            padding: 40px;
        }

        .portfolio {
            background-color: #fff;
            padding: 60px;
            box-shadow: 0 2px 4px #160404;
            max-width: 800px;
            width: 100%;
            text-align: left;
        }

        /* About Me Section */
        .about-me {
            display: flex;
            align-items: center;
            margin-bottom: 40px;
            justify-content: flex-start;
        }

        .profile-picture {
            flex-basis: 80%;
            margin-right: 20px;
        }

        .profile-picture img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
        }

        .about-content h2 {
            font-size: 28px;
            margin-bottom: 20px;
        }

        .about-content p {
            font-size: 16px;
            line-height: 1.5;
        }

        /* Button Styling */
        .cv-button {
            background-color: #333;
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            font-size: 18px;
            border-radius: 4px;
            margin-left: 20px;
            align-self: center;
        }

        .cv-button:hover {
            background-color: #555;
        }

        /* Skills Section */
        .skills h2 {
            font-size: 28px;
            margin-bottom: 20px;
        }

        .skill-item {
            font-size: 20px;
            margin-bottom: 20px;
        }

        /* Projects Section */
        .projects {
            margin-bottom: 40px;
        }

        .projects h2 {
            font-size: 28px;
            margin-bottom: 20px;
        }

        .project-item {
            background-color: #fff;
            padding: 20px;
            margin-bottom: 20px;
        }

        .project-item h3 {
            font-size: 20px;
            margin-bottom: 10px;
        }

        .project-item p {
            font-size: 16px;
            line-height: 1.5;
            margin-bottom: 10px;
        }

        .project-item a {
            color: #333;
            text-decoration: none;
        }

        /* Contact Section */
        .contact-me {
            background-color: #333;
            color: #fff;
            padding: 50px;
            text-align: center;
        }

        .contact-form {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-bottom: 20px;
        }

        .contact-form input,
        .contact-form textarea {
            width: 100%;
            max-width: 400px;
            padding: 10px;
            margin-bottom: 10px;
            border: none;
            border-radius: 4px;
        }

        .contact-form button {
            background-color: #fff;
            color: #333;
            padding: 10px 20px;
            border: none;
            border-radius: 20px;
            cursor: pointer;
        }

        .social-links a {
            text-decoration: none;
        }

        .social-links button {
            background-color: #0077b5;
            color: white;
            border: none;
            padding: 10px 15px;
            font-size: 16px;
            border-radius: 4px;
            cursor: pointer;
        }

        .social-links button:hover {
            background-color: #005f8d;
        }
    </style>
    
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <a href="#">Portfolio</a>
            </div>
        </nav>
    </header>

    <main>
        <div class="portfolio">
            <!-- About Me Section -->
            <div class="about-me">
                <div class="profile-picture">
                    <img src="profile.jpg" alt="Profile Picture">
                </div>
                <div class="about-content">
                    <h2>About Me</h2>
                    <p>Hi, I'm Sharjeel Khan, a passionate Software Engineer. I'm a new Engineer who is stepping into the world of computing and has a will to create new things.</p>
                </div>
                <a href="cv.html" class="cv-button">View CV</a>
            </div>

            <!-- Skills Section -->
            <div class="skills">
                <h2>Skills</h2>
                <div class="skill-item">
                    1. HTML
                </div>
                <div class="skill-item">
                    2. C++
                </div>
                <div class="skill-item">
                    3. Visual Studio
                </div>
            </div>

            <!-- Projects Section -->
            <div class="projects">
                <h2>Projects</h2>
                <div class="project-item">
                    <h3>Project 1</h3>
                    <p>None to Show</p>
                </div>
                <div class="project-item">
                    <h3>Project 2</h3>
                    <p>None to Show</p>
                </div>
            </div>

            <!-- Contact Section -->
            <div class="contact-me">
                <form class="contact-form">
                    <label for="email">Email Here</label>
                    <input type="email" placeholder="53099@students.riphah.edu.pk" required><br>
                    <label for="Message">Message Me Here</label>
                    <textarea placeholder="Message" required></textarea>
                    <button type="submit">Send</button>
                </form>
                <div class="social-links">
                    <a href="https://www.linkedin.com/in/sharjeel-khan-54b718342">
                        <button>LinkedIn</button>
                    </a>
                </div>
            </div>
        </div>
    </main>
</body>
</html>
