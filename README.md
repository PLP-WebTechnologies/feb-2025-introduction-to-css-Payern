# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨



ANSWER 


Step 1: Create the HTML File (`index.html`)


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Styled Webpage</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Welcome to My Styled Webpage</h1>
    </header>

    <!-- Navigation Section -->
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Main Content Section -->
    <main>
        <section id="content">
            <h2>Main Content</h2>
            <p>This is the main content of the webpage. Here you can find various information.</p>
            <img src="https://www.pexels.com/photo-of-mountain-2650092/" alt="Beautiful Landscape" class="styled-image">
        </section>
    </main>

    <!-- Footer Section -->
    <footer>
        <p>Contact us at: contact@example.com</p>
    </footer>
</body>
</html>
```

Step 2: Create the CSS File (`style.css`)


/* Basic Styling */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
}

/* Header Styling */
header {
    background-color: #4CAF50;
    color: white;
    padding: 10px 0;
    text-align: center;
}

/* Navigation Styling */
nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #333;
}

nav ul li {
    float: left;
}

nav ul li a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

nav ul li a:hover {
    background-color: #111;
}

/* Main Content Styling */
main {
    padding: 20px;
}

/* Styling the Image */
.styled-image {
    max-width: 100%;
    height: auto;
    border: 5px solid #ccc;
    margin: 20px 0;
}

/* Footer Styling */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}
