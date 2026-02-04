# Ex01 Portfolio
## Date:04-02-2026

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
Home page:
```
<!DOCTYPE html>
<html>
<head>
    <title>Home | Harish</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>

<div class="home">
    <h1>Hello, I'm Harish 👋</h1>
    <p>Frontend Developer & UI/UX Designer</p>
    <p>I build simple, clean and user-friendly websites.</p>
</div>

</body>
</html>

```
About page:
```
<!DOCTYPE html>
<html>
<head>
    <title>About</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>

<div class="page">
    <h1>About Me</h1>

    <p>
        I'm a passionate developer who enjoys creating websites that are clean,
        responsive and easy to use.
    </p>

    <p>
        I love learning new technologies and solving real-world problems
        through design and code.
    </p>
</div>

</body>
</html>

```

skill page
```
<!DOCTYPE html>
<html>
<head>
    <title>Skills</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>

<div class="page">
    <h1>My Skills</h1>

    <div class="skill">HTML</div>
    <div class="skill">CSS</div>
    <div class="skill">JavaScript</div>
    <div class="skill">React</div>
    <div class="skill">Python</div>
</div>

</body>
</html>

```
Project page:
```



<!DOCTYPE html>
<html>
<head>
    <title>Contact </title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>




<div class="page">
    <h1>My Projects</h1>

    <div class="projects-container">

        <div class="project">
            <h3>Portfolio Website</h3>
            <p>Built a personal portfolio using HTML and CSS with responsive design.</p>
            <a href="#">View Project</a>
        </div>

        <div class="project">
            <h3>Lifeline AI</h3>
            <p>
                AI-powered system that detects early signs of emotional distress,
                silent abuse, or mental health decline by analyzing subtle signals —
                like voice tone, message sentiment, and changes in phone usage.
            </p>
            <a href="#">View Project</a>
        </div>

        <div class="project">
            <h3>To-Do Web App</h3>
            <p>Simple task manager built with JavaScript for daily productivity.</p>
            <a href="#">View Project</a>
        </div>

    </div>
</div>
</body></html>


```
Contact page:
```
<!DOCTYPE html>
<html>
<head>
    <title>Contact</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>

<div class="page">
    <h1>Contact Me</h1>

    <p>Email: harishbalajj@email.com</p>
    <p>Phone: +91 9876543210</p>
    <p>LinkedIn: linkedin.com/in/harish</p>
</div>

</body>
</html>


```
style.css:
```
/*full body */
body {
    margin: 0;
    font-family: "Segoe UI", Arial, sans-serif;
    background: #0f172a;      
    color: white;
}

/* Navbar */
.nav {
    text-align: center;
    padding: 20px;
    background: #111827;
    box-shadow: 0 4px 15px rgba(0,0,0,0.4);
}

.nav a {
    color: #e5e7eb;
    text-decoration: none;
    margin: 0 20px;
    font-size: 17px;
    font-weight: 600;
}

.nav a:hover {
    color: #8b5cf6;   
}

/* port.html */
.home {
    text-align: center;
    padding: 160px 20px;

    background: linear-gradient(135deg, #4f46e5, #7c3aed);
}

.home h1 {
    font-size: 52px;
    margin-bottom: 10px;
}

.home p {
    font-size: 18px;
    opacity: 0.95;
}

/*page */
.page {
    max-width: 1000px;
    margin: 60px auto;
    padding: 60px 30px;

    background: #1e293b;  
    border-radius: 18px;

    box-shadow: 0 15px 40px rgba(0,0,0,0.5);
}

/* skills.html */
.skill {
    display: inline-block;
    padding: 10px 18px;
    margin: 10px;
    border-radius: 25px;

    background: #8b5cf6;
    color: white;
    font-weight: bold;
}

/* Projects.html */
/* ===== GRID LAYOUT ===== */
.projects-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
    margin-top: 40px;
}

/* ===== CARD ===== */
.project {
    background: #1f2937;
    padding: 25px;
    border-radius: 14px;
    color: white;

    box-shadow: 0 10px 30px rgba(0,0,0,0.5);

    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

/* button */
.project a {
    margin-top: 15px;
    display: inline-block;
    padding: 8px 14px;
    background: #38bdf8;
    color: black;
    border-radius: 6px;
    text-decoration: none;
    font-weight: 600;
}


/* Contact.html */
.contact p {
    margin: 10px 0;
    font-size: 16px;
}

/* Footer */
.footer {
    text-align: center;
    padding: 18px;
    background: #111827;
    margin-top: 40px;
}

/*responsive*/
@media(max-width: 600px){
    .project {
        width: 90%;
    }

    .home h1 {
        font-size: 34px;
    }
}

```
## OUTPUT
### Home page:

![alt text](<Screenshot 2026-02-04 195749.png>)

### About page:

![alt text](<Screenshot 2026-02-04 195800.png>)

### Skills page:

![alt text](<Screenshot 2026-02-04 195820.png>)

### Project page:

![alt text](<Screenshot 2026-02-04 195903.png>)

### Contact page:

![alt text](<Screenshot 2026-02-04 195913.png>)


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.