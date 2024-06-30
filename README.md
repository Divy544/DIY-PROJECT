<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MiCrO - Microprojects for Diploma Students</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" integrity="sha512-Fo3rlrZj/kMVq6xQm8rgeYXN7CQ4fZ+MNHfELR4J6mYYb4WZHJZ5yP0Hk6Wxj/xjR9pdeIWsd1E5xe0Z8bkgOg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        /* General styles */
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
            overflow-x: hidden;
        }

        h1, h2, h3 {
            margin: 0;
            font-weight: 700;
            animation: fadeInDown 1s ease-in-out;
        }

        p {
            margin: 0;
            line-height: 1.6;
            animation: fadeIn 2s ease-in-out;
        }

        a {
            text-decoration: none;
            color: #f39c12;
            transition: color 0.3s;
        }

        a:hover {
            color: #e67e22;
        }

        /* Header styles */
        header {
            background-color: #35495e;
            color: #f5f5f5;
            padding: 20px;
            text-align: center;
            animation: fadeIn 1s ease-in-out;
        }

        header h1 {
            font-size: 2.5em;
        }

        header p {
            font-size: 1.2em;
            margin-bottom: 20px;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
            animation: fadeInUp 1s ease-in-out;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            font-size: 1.2em;
            padding: 10px;
            border-radius: 4px;
            transition: background-color 0.3s;
            animation: fadeInUp 1.5s ease-in-out;
        }

        nav ul li a:hover {
            background-color: #f39c12;
        }

        /* Main content styles */
        main {
            padding: 40px 20px;
        }

        section {
            margin-bottom: 60px;
        }

        section h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
            text-align: center;
        }

        section p {
            font-size: 1.2em;
            max-width: 800px;
            margin: 0 auto 40px;
            text-align: center;
        }

        section ul {
            padding: 0;
            margin: 0;
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 40px;
            flex-wrap: wrap;
        }

        section ul li {
            max-width: 300px;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.3s, box-shadow 0.3s;
            animation: fadeInUp 1s ease-in-out;
        }

        section ul li:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }

        section ul li img {
            max-width: 100%;
            border-radius: 8px;
            animation: fadeIn 2s ease-in-out;
        }

        section .caption {
            font-size: 0.8em;
            color: #777;
            margin-top: 10px;
            animation: fadeIn 2.5s ease-in-out;
        }

        /* Animations */
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Footer styles */
        footer {
            background-color: #35495e;
            color: #f5f5f5;
            text-align: center;
            padding: 20px 0;
            animation: fadeIn 1s ease-in-out;
        }

        footer p {
            font-size: 0.9em;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2em;
            }

            header p {
                font-size: 1em;
            }

            nav ul li a {
                font-size: 1em;
                padding: 8px;
            }

            section h2 {
                font-size: 2em;
            }

            section p {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>DiY MiCrO</h1>
        <p>Microprojects for Diploma Students</p>
        <nav>
            <ul>
                <li><a href="#about" class="wiggle-button">About Us</a></li>
                <li><a href="#services" class="wiggle-button">Services</a></li>
                <li><a href="#contact" class="wiggle-button">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="about">
            <h2>About Us</h2>
            <p>MiCrO specializes in providing high-quality microprojects for diploma students across various branches including Electrical, Computer, IT, and more. Our goal is to help students achieve their academic goals by offering well-structured, innovative, and practical project solutions.</p>
        </section>
        <section id="services">
            <h2>Our Services</h2>
            <ul>
                <li>
                    <h3>Electrical Projects</h3>
                    <p>We offer a range of microprojects tailored for Electrical diploma students, covering topics such as circuit design, renewable energy, and automation.</p>
                    <img src="project-photo1.jpg" alt="Electrical Project Photo" class="project-photo">
                    <div class="caption">Example of an Electrical Project</div>
                </li>
                <li>
                    <h3>Computer Projects</h3>
                    <p>Innovative microprojects for Computer diploma students, focusing on programming, networking, and software development.</p>
                    <img src="project-photo2.jpg" alt="Computer Project Photo" class="project-photo">
                    <div class="caption">Example of a Computer Project</div>
                </li>
                <li>
                    <h3>IT Projects</h3>
                    <p>Comprehensive IT microprojects, including web development, database management, and cybersecurity.</p>
                    <img src="project-photo3.jpg" alt="IT Project Photo" class="project-photo">
                    <div class="caption">Example of an IT Project</div>
                </li>
                <li>
                    <h3>Mechanical Projects</h3>
                    <p>Practical microprojects for Mechanical diploma students, covering design, manufacturing, and robotics.</p>
                    <img src="project-photo4.jpg" alt="Mechanical Project Photo" class="project-photo">
                    <div class="caption">Example of a Mechanical Project</div>
                </li>
                <li>
                    <h3>Civil Projects</h3>
                    <p>Microprojects for Civil diploma students, focusing on construction, structural analysis, and environmental engineering.</p>
                    <img src="project-photo5.jpg" alt="Civil Project Photo" class="project-photo">
                    <div class="caption">Example of a Civil Project</div>
                </li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <p>For inquiries and project requests, please contact us at:</p>
            <p>Email: <a href="mailto:info@microprojects.com">info@microprojects.com</a></p>
            <p>Phone: +91 8799051812</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 MiCrO. All rights reserved.</p>
    </footer>
</body>
</html>
