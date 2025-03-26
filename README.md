# Digital-_portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prasath - Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ff0033;
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: #b2db21;
            text-align: center;
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
        }
        .sub-header {
            text-align: center;
            font-size: 16px;
            font-style: italic;
        }
        .navbar {
            background-color: #d60029;
            padding: 10px;
            text-align: center;
        }
        .navbar a {
            color: white;
            text-decoration: none;
            margin: 10px;
            font-size: 18px;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        .section {
            background-color: white;
            padding: 15px;
            margin: 15px 0;
            border-radius: 10px;
        }
        h2 {
            color: #d60029;
        }
        .resume-btn {
            display: block;
            text-align: center;
            background-color: black;
            color: white;
            padding: 10px;
            margin: 20px auto;
            width: 150px;
            border-radius: 5px;
            text-decoration: none;
        }
        .footer {
            text-align: center;
            padding: 10px;
            background-color: black;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <div class="header">Prasath</div>
    <div class="sub-header">Aspiring Developer</div>

    <div class="navbar">
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#resume">Resume</a>
    </div>

    <div class="container">
        <div class="section" id="about">
            <h2>About Me</h2>
            <p>Good active person with basic coding knowledge.</p>
        </div>

        <div class="section" id="education">
            <h2>Education</h2>
            <p>Prince Shri Venkateshwar Arts and Science College</p>
        </div>

        <div class="section" id="skills">
            <h2>Skills</h2>
            <ul>
                <li>Python</li>
                <li>C++</li>
                <li>CSS</li>
                <li>JavaScript</li>
            </ul>
        </div>

        <div class="section" id="projects">
            <h2>Projects</h2>
            <ul>
                <li>Guess a Number</li>
            </ul>
        </div>

        <div class="section" id="resume">
            <h2>Resume</h2>
            <a href="#" class="resume-btn">Download CV</a>
        </div>
    </div>

    <div class="footer">
        © 2025 Prasath
    </div>

</body>
</html>
