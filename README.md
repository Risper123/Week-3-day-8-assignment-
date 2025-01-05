Project Requirements:
Website Design:

Design a website that has at least three pages (e.g., Home, About, Contact).
Each page should have unique content but maintain a consistent layout and design (using a common theme or template).
The website should be responsive, meaning it must look good and function properly on devices of all sizes (desktop, tablet, mobile).
You are encouraged to use modern design trends (flat design, minimalism, or material design) and UI/UX principles.
HTML5 Structure:

Use semantic HTML5 tags where appropriate (<header>, <footer>, <main>, <section>, etc.).
Ensure the website has a navigation menu that allows users to navigate between pages.
CSS3 Styling:

Create a style sheet using CSS3 to design your website (you may use CSS frameworks like Bootstrap or TailwindCSS to speed up the process, but it is not mandatory).
Implement CSS3 transitions and animations to enhance interactivity (e.g., hover effects, smooth scrolling, fade-in elements).
Make sure your website is responsive, using media queries to adjust the layout for various screen sizes.
JavaScript Functionality:

Incorporate JavaScript to add interactivity to your website (e.g., form validation, image sliders, modals, or interactive maps).
Use event listeners (e.g., onclick, onmouseover) for user interactions.
Ensure form validation is functional for all forms on the website (e.g., contact form, subscription form).
Optimizations:

Optimize your images (compress them without losing quality).
Minify your CSS and JavaScript files.
Test your website on various browsers (Chrome, Firefox, Safari) and devices to ensure compatibility.
Deployment:

Deploy your website to a hosting platform. Choose one of the following platforms for deployment:
GitHub Pages
Netlify
Vercel
Ensure that your website is live and accessible on the internet via a unique URL.
Deliverables:
Website Files:

HTML files for each page (e.g., index.html, about.html, contact.html).
CSS file(s) for styling.
JavaScript file(s) for functionality.
All images and assets used in the project (stored in an assets/ folder).
README.md file with a description of the project and instructions on how to run it locally.
Live Website:

Provide a link to the live website deployed on your chosen hosting platform (GitHub Pages, Netlify, or Vercel).
Ensure that the website is fully functional, responsive, and looks good across devices.
Documentation:

Write a brief documentation (100-200 words) explaining:
Your design choices (why you chose the layout, colors, etc.).
The features you implemented using JavaScript (e.g., form validation, interactive elements).
Any challenges you faced during development and how you overcame them.
The deployment process you followed.


# Week-3-day-8-assignment-
My assignment for week 3 day 8

index.html (Home Page):

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h1>Welcome to Our Website</h1>
            <p>This is the home page with unique content.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Your Website. All rights reserved.</p>
    </footer>
</body>
</html>


about.html (About Page):

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h1>About Us</h1>
            <p>This page contains information about our website and team.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Your Website. All rights reserved.</p>
    </footer>
</body>
</html>


contact.html (Contact Page):

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h1>Contact Us</h1>
            <form action="#" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>
                
                <button type="submit">Submit</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Your Website. All rights reserved.</p>
    </footer>
</body>
</html>


/* Reset some default styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem 0;
}

nav ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

nav ul li a:hover {
    text-decoration: underline;
}

main {
    padding: 2rem;
}

section {
    max-width: 800px;
    margin: 0 auto;
    text-align: center;
}

h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}

p {
    font-size: 1.2rem;
    line-height: 1.6;
}

form {
    background: #f9f9f9;
    padding: 2rem;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

label {
    display: block;
    margin-bottom: 0.5rem;
    font-weight: bold;
}

input, textarea {
    width: 100%;
    padding: 0.8rem;
    margin-bottom: 1rem;
    border: 1px solid #ddd;
    border-radius: 4px;
    font-size: 1rem;
}

input:focus, textarea:focus {
    border-color: #007BFF;
    outline: none;
    box-shadow: 0 0 8px rgba(0, 123, 255, 0.5);
}

button {
    background-color: #007BFF;
    color: white;
    border: none;
    padding: 0.8rem 1.5rem;
    border-radius: 4px;
    cursor: pointer;
    font-size: 1rem;
}

button:hover {
    background-color: #0056b3;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem;
}

document.addEventListener('DOMContentLoaded', () => {
    // Form validation for Contact page
    const contactForm = document.querySelector('form');

    contactForm.addEventListener('submit', function(e) {
        e.preventDefault(); // Prevent form from submitting

        const name = document.getElementById('name').value.trim();
        const email = document.getElementById('email').value.trim();
        const message = document.getElementById('message').value.trim();

        let valid = true;

        // Name validation
        if (name === '') {
            alert('Name is required.');
            valid = false;
        }

        // Email validation
        if (email === '') {
            alert('Email is required.');
            valid = false;
        } else if (!validateEmail(email)) {
            alert('Please enter a valid email.');
            valid = false;
        }

        // Message validation
        if (message === '') {
            alert('Message is required.');
            valid = false;
        }

        // Submit form if valid
        if (valid) {
            alert('Form submitted successfully!');
            contactForm.submit(); // Actually submit form
        }
    });

    function validateEmail(email) {
        const regex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
        return regex.test(email);
    }
});


Minified CSS (style.min.css):

body{font-family:Arial,sans-serif;margin:0;padding:0;box-sizing:border-box}header{background-color:#333;color:white;padding:1rem 0}nav ul{list-style-type:none;padding:0;margin:0;display:flex;justify-content:center}nav ul li{margin:0 15px}nav ul li a{color:white;text-decoration:none;font-weight:bold}nav ul li a:hover{text-decoration:underline}main{padding:2rem}section{max-width:800px;margin:0 auto;text-align:center}h1{font-size:2.5rem;margin-bottom:1rem}p{font-size:1.2rem;line-height:1.6}form{background:#f9f9f9;padding:2rem;border-radius:8px;box-shadow:0 0 10px rgba(0,0,0,0.1)}label{display:block;margin-bottom:0.5rem;font-weight:bold}input,textarea{width:100%;padding:0.8rem;margin-bottom:1rem;border:1px solid #ddd;border-radius:4px;font-size:1rem}input:focus,textarea:focus{border-color:#007BFF;outline:none;box-shadow:0 0 8px rgba(0,123,255,0.5)}button{background-color:#007BFF;color:white;border:none;padding:0.8rem 1.5rem;border-radius:4px;cursor:pointer;font-size:1rem}button:hover{background-color:#0056b3}footer{background-color:#333;color:white;text-align:center;padding:1rem}


Minified JavaScript (script.min.js):

document.addEventListener('DOMContentLoaded',()=>{const contactForm=document.querySelector('form');contactForm.addEventListener('submit',function(e){e.preventDefault();const name=document.getElementById('name').value.trim();const email=document.getElementById('email').value.trim();const message=document.getElementById('message').value.trim();let valid=true;if(name===''){alert('Name is required.');valid=false}if(email===''){alert('Email is required.');valid=false}else if(!validateEmail(email)){alert('Please enter a valid email.');valid=false}if(message===''){alert('Message is required.');valid=false}if(valid){alert('Form submitted successfully!');contactForm.submit()}});function validateEmail(email){const regex=/^[^\s@]+@[^\s@]+\.[^\s@]+$/;return regex.test(email)}});


git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
