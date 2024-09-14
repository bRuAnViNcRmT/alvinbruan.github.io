<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Verdana, "Lucida Sans Regular";
            background-color: aquamarine;
            margin: 0;
            padding: 0;
            color: #000000;
        }
        header {
            background: url('https://www.adobe.com/express/learn/blog/media_1a4723eb0c857716ca15b1ce012eb9128028b49a8.png?width=2000&format=webply&optimize=medium.jpg') no-repeat center center fixed;
            color: black;
            padding: 20px;
            text-align: center;
            background-size: cover;
        }
        header img {
            border-radius: 50%;
            width: 25vw;
            max-width: 120px; /* Reduce size */
            height: auto;
            display: block;
            margin: 0 auto;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            font-size: 1.8em;
            margin: 10px 0;
        }
        h2 {
            color: darkslategray;
            font-size: 1.5em;
            margin-bottom: 20px;
        }
        section {
            max-width: 1000px;
            margin: 20px auto;
            padding: 20px;
            border-radius: 15px;
            background-color: whitesmoke;
            box-shadow: 0 0 30px rgba(0, 0, 0, 0.1);
        }
        #projects {
            position: relative;
        }
        .container {
            display: flex;
            flex-direction: column;
            gap: 20px;
        }
        .container div {
            padding: 20px;
            border: 1px solid #aea6a6;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
            background-color: whitesmoke;
            text-align: center;
        }
        .container div:hover {
            background-color: #2f2929;
            color: aliceblue;
        }
        footer {
            background: url('https://www.adobe.com/express/learn/blog/media_1a4723eb0c857716ca15b1ce012eb9128028b49a8.png?width=2000&format=webply&optimize=medium.jpg') no-repeat center center fixed;
            color: rgb(0, 0, 0);
            font-weight: bold;
            background-size: cover;
            text-align: center;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        /* Responsive Design */
        @media (max-width: 768px) {
            h1 {
                font-size: 1.5em;
            }
            h2 {
                font-size: 1.3em;
            }
            .container div {
                padding: 15px;
                margin: 10px 0;
            }
            header img {
                width: 20vw;
                max-width: 100px; /* Smaller image size */
            }
            header, footer {
                padding: 20px;
            }
        }
        @media (max-width: 480px) {
            h1 {
                font-size: 1.3em;
            }
            h2 {
                font-size: 1.1em;
            }
            .container div {
                padding: 10px;
                margin: 10px 0;
            }
            header img {
                width: 30vw;
                max-width: 80px; /* Smaller image size */
            }
            header, footer {
                padding: 15px;
            }
            section {
                padding: 10px; /* Reduced padding */
            }
            .container {
                gap: 10px;
            }
        }
    </style>
</head>

<body>
    <header>
        <img src="https://github.com/bRuAnViNcRmT/alvinbruan.github.io/blob/main/419873735_378061001577662_4683229797514632158_n.jpg?raw=true" alt="Profile Picture">
        <h1>Hello there! Welcome to my Portfolio</h1>
        <p>Explore my projects, skills, and experience</p>
    </header>
    <section id="about">
        <h2><i class="fas fa-user"></i> About Me</h2>
        <p>Hello! I am Alvin Bruan, a second-year IT student with a passion for building user-friendly and functional websites. I usually focus on front-end development with experience in back-end technologies as well.</p>
    </section>
    <section id="projects">
        <h2><i class="fas fa-briefcase"></i> My Projects</h2>
        <div class="container">
            <div>
                <h3>PassGen</h3>
                <p>A password generator project that ensures secure and complex password creation.</p>
            </div>
            <div>
                <h3>Wordling</h3>
                <p>An interactive word-guessing-game designed to improve users' vocabulary and problem-solving skills.</p>
            </div>
            <div>
                <h3>Barangay Papers Management System</h3>
                <p>A system designed to streamline document management for local government units.</p>
            </div>
        </div>
    </section>
    <section id="contact">
        <h2><i class="fas fa-paper-plane"></i> Contact Me</h2>
        <p>Feel free to reach out for collaborations or just a friendly chat:</p>
        <p><i class="fas fa-envelope"></i> alvinbruan68@gmail.com</p>
        <p><i class="fas fa-phone"></i> +63 991 807 3592</p>
        <p><i class="fab fa-facebook"></i> Alvin Caramat Bruan</p>
    </section>
    <footer>
        <p>&copy; 2024 My Portfolio | All Rights Reserved</p>
    </footer>
</body>
</html>
