<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sarthak Roy | Student Resume</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: #0f172a;
            color: #e2e8f0;
            line-height: 1.7;
        }

        header {
            text-align: center;
            padding: 60px 20px;
            background: #172338;
            border-bottom: 3px solid #38bdf8;
        }

        header h1 {
            font-size: 42px;
            color: #38bdf8;
        }

        header p {
            color: #cbd5e1;
            margin-top: 8px;
        }

        nav {
            margin-top: 20px;
        }

        nav a {
            color: #38bdf8;
            text-decoration: none;
            margin: 8px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        main {
            max-width: 900px;
            margin: auto;
            padding: 25px;
        }

        section {
            background: #172338;
            margin: 22px 0;
            padding: 25px;
            border-radius: 12px;
            border: 1px solid #334155;
        }

        h2 {
            color: #38bdf8;
            margin-bottom: 15px;
            border-bottom: 1px solid #334155;
            padding-bottom: 8px;
        }

        h3 {
            margin-bottom: 5px;
        }

        .muted {
            color: #94a3b8;
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .skills span {
            background: #26364f;
            color: #7dd3fc;
            padding: 7px 13px;
            border-radius: 6px;
        }

        ul {
            padding-left: 22px;
        }

        a {
            color: #7dd3fc;
        }

        footer {
            text-align: center;
            padding: 25px;
            color: #94a3b8;
        }

        @media (max-width: 600px) {
            header h1 {
                font-size: 32px;
            }

            main {
                padding: 12px;
            }

            section {
                padding: 18px;
            }
        }
    </style>
</head>

<body>

    <header>
        <h1>Sarthak Roy</h1>
        <p>First-Year Engineering Student</p>
        <p>Information Technology (IT)</p>
        <p>Dharmsinh Desai University, Nadiad, Gujarat</p>

        <nav>
            <a href="#about">About</a>
            <a href="#education">Education</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>

        <section id="about">
            <h2>About Me</h2>
            <p>
                I am an enthusiastic Information Technology student
                at Dharmsinh Desai University. I am interested in
                programming, software development and emerging
                technologies. I enjoy learning new skills, solving
                problems and building practical projects.
            </p>
        </section>

        <section id="education">
            <h2>Education</h2>
            <h3>Bachelor of Technology (B.Tech.)</h3>
            <p>Branch: Information Technology (IT)</p>
            <p>Dharmsinh Desai University, Nadiad, Gujarat</p>
            <p class="muted">Expected Graduation: 2029</p>
            <p>CGPA: Add your current CGPA</p>
        </section>

        <section id="skills">
            <h2>Technical Skills</h2>
            <div class="skills">
                <span>C</span>
                <span>C++</span>
                <span>Java</span>
                <span>HTML</span>
                <span>CSS</span>
                <span>Git</span>
                <span>GitHub</span>
                <span>Problem Solving</span>
            </div>
        </section>

        <section id="projects">
            <h2>Projects</h2>

            <div style="margin-bottom: 20px;">
                <h3>Student Resume Website</h3>
                <p>
                    A personal portfolio website developed using
                    HTML and CSS to present my education, technical
                    skills and projects.
                </p>
                <p><strong>Technologies:</strong> HTML, CSS</p>
                <a href="https://github.com/" target="_blank"
                   rel="noopener noreferrer">GitHub</a>
            </div>

            <div>
                <h3>Project 2 — Add Your Project</h3>
                <p>
                    Add details about another project you have
                    completed or are currently developing.
                </p>
                <p><strong>Technologies:</strong> Add your technologies</p>
            </div>
        </section>

        <section id="certifications">
            <h2>Certifications & Achievements</h2>
            <ul>
                <li>Add completed certifications and courses.</li>
                <li>Add coding competitions or hackathon participation.</li>
                <li>Add relevant college achievements.</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>
                <strong>Email:</strong>
                <a href="mailto:your-email@example.com">
                    your-email@example.com
                </a>
            </p>

            <p>
                <strong>GitHub:</strong>
                <a href="https://github.com/" target="_blank"
                   rel="noopener noreferrer">
                    Add your GitHub profile
                </a>
            </p>

            <p>
                <strong>LinkedIn:</strong>
                <a href="https://www.linkedin.com/" target="_blank"
                   rel="noopener noreferrer">
                    Add your LinkedIn profile
                </a>
            </p>
        </section>

    </main>

    <footer>
        <p>© 2026 Sarthak Roy | Student Portfolio</p>
        <p>Learning Today. Building Tomorrow.</p>
    </footer>

</body>
</html>
