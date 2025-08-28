<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pavani Kolli - Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Roboto', sans-serif;
        }

        body {
            line-height: 1.6;
            color: #333;
            background-color: #f9f9f9;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        /* Container */
        .container {
            width: 90%;
            max-width: 1000px;
            margin: auto;
            padding: 20px 0;
        }

        /* Hero Section */
        .hero {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 40px;
            padding: 80px 20px;
            background: linear-gradient(to right, #4facfe, #00f2fe);
            color: white;
            flex-wrap: wrap;
        }
        .hero-text {
            flex: 1;
        }
        .hero-text h1 {
            font-size: 2.8rem;
        }
        .hero-text p {
            font-size: 1.2rem;
            margin: 10px 0 20px;
        }
        .hero-text a {
            display: inline-block;
            margin: 5px 10px;
            padding: 10px 20px;
            background-color: white;
            color: #4facfe;
            border-radius: 25px;
            font-weight: bold;
            transition: 0.3s;
        }
        .hero-text a:hover {
            background-color: #00f2fe;
            color: white;
        }
        .hero-img {
            flex: 1;
            text-align: center;
        }
        .hero-img img {
            width: 200px;
            height: auto;
            border-radius: 20px;
            object-fit: cover;
            border: 4px solid white;
            border-radius: 10px solid black;
            box-shadow: 10px solid black;
        }

        /* Section Styles */
        section {
            padding: 60px 20px;
        }
        section h2 {
            text-align: center;
            margin-bottom: 40px;
            font-size: 2rem;
            color: #4facfe;
        }

        /* About */
        .about p {
            max-width: 700px;
            margin: auto;
            font-size: 1.1rem;
        }

        /* Skills */
        .skills {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .skill {
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            width: 220px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            text-align: center;
        }
        .skill h3 {
            margin-bottom: 10px;
            color: #00f2fe;
        }

        /* Projects */
        .projects-flex {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .project-card {
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            flex: 1 1 280px;
            max-width: 320px;
        }
        .project-card h3 {
            margin-bottom: 10px;
            color: #4facfe;
        }
        .project-card p {
            font-size: 0.95rem;
        }

        /* Education & Achievements */
        .list-item {
            background-color: white;
            padding: 15px 20px;
            margin: 10px 0;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.08);
        }

        /* Contact */
        .contact {
            text-align: center;
        }
        .contact a {
            display: inline-block;
            margin: 5px 10px;
            padding: 10px 20px;
            background-color: #4facfe;
            color: white;
            border-radius: 25px;
            font-weight: bold;
            transition: 0.3s;
        }
        .contact a:hover {
            background-color: #00f2fe;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
        }

        /* Responsive */
        @media(max-width: 768px){
            .hero {
                flex-direction: column;
            }
            .hero-img img {
                width: 200px;
            }
        }
    </style>
</head>
<body>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-text">
            <h1>Pavani Kolli</h1>
            <p>| Python & Web Developer | | SQL | </p>
            <a href="https://github.com/pavanikolli06">GitHub</a>
            <a href="https://www.linkedin.com/in/pavani-kolli-a0955a291/">LinkedIn</a>
            <a href="pavists22@gmail.com">Email</a>
        </div>
        <div class="hero-img">
            <img src="150kb.png"alt="Pavani Kolli">
        </div>
    </section>

    <!-- About Me -->
    <section class="about container">
        <h2>About Me</h2>
        <p>
            I am a Computer Science graduate passionate about Python, SQL, and Full-stack development.
            Currently exploring scalable architectures and IT service management,
            I strive to build eﬃcient and secure solutions.and With excellent verbal and written communication skills, I excel at building positive relationships and exceeding goals. Eager to learn, adapt, and contribute to innovative projects. 
    </section>

    <!-- Skills -->
    <section class="skills container">
        <h2>Skills</h2>
        <div class="skills">
            <div class="skill">
                <h3>PYTHON</h3>
                <p>Python (Data Science)</p>
            </div>
            <div class="skill">
                <h3>Web Development</h3>
                <p>HTML, CSS, JavaScript</p>
            </div>
            <div class="skill">
                <h3> SQL </h3>
                <p>SQL, Data Modeling</p>
            </div>
            
        </div>
    </section>

    <!-- Projects -->
    <section class="projects container">
        <h2>Projects</h2>
        <div class="projects-flex">
            <div class="project-card">
                <h3>Student  Management System </h3>
                <p>Built using instead of plain data structures like lists/dictionaries. Features: Student Class,StudentManagementSystem Class,Encapsulation,Easy to Extend.</p>
            </div>
            <div class="project-card">
                <h3>Retail_Sales Analysis</h3>
                <p>Built using SQL. Used aggregation and filtering queries to analyze customer behavior, sales volume, and transaction trends.</p>
            </div>
            <div class="project-card">
                <h3>CURD APPLICATIONS ON CARS SHOEROOM</h3>
                <p>Using html,css ,javascript, Worked on front-end integration with APIs to fetch and manipulate data .</p>
            </div>
        </div>
    </section>

    <!-- Education -->
    <section class="education container">
        <h2>Education</h2>
        <div class="list-item">
            <strong>Bachelor’s Degree in Computer Science</strong> – ISTS WOMEN'S ENGINEERING COLLAGE(2022-2026) | CGPA: 8.5
        </div>
        <div class="list-item">
            Intermediate (2020-2022) – State Board | CGPA: 7.2
        </div>
        <div class="list-item">
            High School (2019-2020) – State Board | CGPA: 9.8
        </div>
    </section>

    <!-- Achievements -->
    <section class="achievements container">
        <h2>Achievements & Certifications</h2>
        <div class="list-item">NPTEL (PYTHON WITH DS) Certification</div>
        <div class="list-item">ANDROID VIRTUAL INTERSHIP</div>
    </section>

    <!-- Contact -->
    <section class="contact container">
        <h2>Contact Me</h2>
        <a href="https://github.com/pavanikolli06">GitHub</a>
        <a href="https://www.linkedin.com/in/pavani-kolli-a0955a291/">LinkedIn</a>
        <a href="pavists22@gmail.com">Email</a>
    </section>

    <!-- Footer -->
    <footer>
        &copy; 2025 Pavani Kolli. All rights reserved.
    </footer>

</body>
</html>



       
