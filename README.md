# Ex01 Portfolio
## Date:24-102026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Rohith V - Portfolio</title>

<style>
    @page {
        size: A4;
        margin: 0;
    }

    * {
        box-sizing: border-box;
    }

    body {
        margin: 0;
        background: #e8edf4;
        font-family: Arial, sans-serif;
        color: #243047;
    }

    .page {
        width: 210mm;
        min-height: 297mm;
        margin: 20px auto;
        padding: 15mm 17mm;
        background: white;
    }

    header {
        text-align: center;
        border-bottom: 2px solid #243b64;
        padding-bottom: 15px;
    }

    .profile {
        width: 105px;
        height: 105px;
        border-radius: 50%;
        object-fit: cover;
        border: 3px solid #243b64;
    }

    h1 {
        margin: 12px 0 5px;
        color: #243b64;
        font-size: 28px;
    }

    header p {
        margin: 5px;
        font-size: 13px;
    }

    h2 {
        color: #243b64;
        font-size: 16px;
        border-bottom: 1px solid #c8d2e2;
        padding-bottom: 5px;
        margin-bottom: 8px;
    }

    section {
        margin-top: 17px;
    }

    p, li {
        font-size: 12px;
        line-height: 1.6;
    }

    p {
        margin: 5px 0;
    }

    ul {
        margin: 5px 0;
        padding-left: 20px;
    }

    .skills {
        display: flex;
        justify-content: space-between;
        gap: 12px;
    }

    .skills ul {
        flex: 1;
    }

    .project-title {
        font-weight: bold;
        font-size: 12px;
    }

    footer {
        text-align: center;
        border-top: 1px solid #c8d2e2;
        margin-top: 20px;
        padding-top: 10px;
        font-size: 10px;
    }

    @media print {
        body {
            background: white;
        }

        .page {
            margin: 0;
            width: 210mm;
            min-height: 297mm;
            box-shadow: none;
        }
    }
</style>
</head>

<body>
<div class="page">

    <header>
        <img src="Portfolio/WhatsApp Image 2026-10-24 at 2.28.01 PM.jpeg" alt="Rohith's profile picture"
             class="profile">

        <h1>ROHITH V</h1>
        <p><strong>Information Technology Student</strong></p>
        <p>Aspiring AI Developer | Python Programmer</p>
        <p>Chennai, Tamil Nadu</p>
        <p>
            Email: rohithveeravel29@gmail.com |
            GitHub: github.com/Rohith540-web
        </p>
    </header>

    <section>
        <h2>ABOUT ME</h2>
        <p>
            Third-year Information Technology student passionate
            about Python, Artificial Intelligence, Data Science,
            and software development. Interested in building
            practical technology solutions to real-world problems.
        </p>
    </section>

    <section>
        <h2>TECHNICAL SKILLS</h2>
        <div class="skills">
            <ul>
                <li>Python Programming</li>
                <li>Java Programming</li>
                <li>HTML & Web Development</li>
            </ul>
            <ul>
                <li>Artificial Intelligence</li>
                <li>Data Science</li>
                <li>Git & GitHub</li>
            </ul>
        </div>
    </section>

    <section>
        <h2>PROJECTS</h2>

        <p class="project-title">1. FoodBridge AI</p>
        <p>
            An intelligent platform concept for connecting surplus
            food donors with organizations supporting people in need.
        </p>

        <p class="project-title">2. ProcessDNA AI</p>
        <p>
            An AI-based project concept focused on analyzing
            business processes and identifying unusual patterns.
        </p>

        <p class="project-title">3. Employee Management System</p>
        <p>
            A Python-based application concept for organizing
            and managing employee information.
        </p>
    </section>

    <section>
        <h2>EDUCATION</h2>
        <p><strong>Bachelor of Engineering - Information Technology</strong></p>
        <p>Saveetha Engineering College, Thandalam, Chennai</p>
        <p>Currently pursuing third year</p>
    </section>

    <section>
        <h2>CERTIFICATIONS & ACHIEVEMENTS</h2>
        <ul>
            <li>AWS Educate - Introduction to Cloud 101</li>
            <li>AWS Academy Graduate - Cloud Foundations</li>
            <li>IBM Z Datathon - Participation</li>
        </ul>
    </section>

    <section>
        <h2>CAREER OBJECTIVE</h2>
        <p>
            To develop my technical skills, gain practical
            experience, and contribute to innovative software
            and AI-based solutions.
        </p>
    </section>

    <footer>
        <p>ROHITH V | PERSONAL PORTFOLIO</p>
        <p>Learning Today • Building Tomorrow</p>
    </footer>

</div>
</body>
</html>

```

## OUTPUT

![alt text](<Screenshot 2026-10-24 143026.png>)
![alt text](<Screenshot 2026-10-24 143046.png>)

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
