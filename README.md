<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Introduction</title>
    <!-- Linking external CSS file -->
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header id="main-header">
        <h1 class="title">Welcome to CSS Styling</h1>
    </header>
    <nav class="navigation">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
    <main>
        <section class="content-section">
            <h2>Getting Started with CSS</h2>
            <p>CSS (Cascading Style Sheets) is used to style and layout web pages.</p>  
            <div class="image-container">
                <img src="https://images.pexels.com/photos/11035380/pexels-photo-11035380.jpeg" 
                     alt="CSS code on a screen" 
                     class="styled-image">
                <p class="caption">Modern CSS makes web design beautiful</p>
            </div>
            <article class="feature-box">
                <h3>CSS Features</h3>
                <ul>
                    <li>Selectors to target HTML elements</li>
                    <li>Color and typography control</li>
                    <li>Layout and spacing tools</li>
                </ul>
            </article>
        </section>
    </main>
</body>
</html>
STYlES.css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Element Selector - styles all <body> elements */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f9f9f9;
    padding: 20px;
}

/* ID Selector - styles the element with id="main-header" */
#main-header {
    background-color: #2c3e50;
    color: white;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 5px;
    text-align: center;
}

/* Class Selector - styles elements with class="title" */
.title {
    font-family: 'Georgia', serif;
    font-size: 2.5rem;
    letter-spacing: 1px;
}

/* Navigation styling */
.navigation {
    background-color: #34495e;
    margin-bottom: 30px;
    border-radius: 5px;
}

.navigation ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
}

.navigation li {
    padding: 15px 20px;
}

.navigation a {
    color: white;
    text-decoration: none;
    font-weight: 500;
    transition: color 0.3s;
}

.navigation a:hover {
    color: #f1c40f;
}

/* Content section styling */
.content-section {
    background-color: white;
    padding: 30px;
    margin-bottom: 30px;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.content-section h2 {
    color: #2c3e50;
    margin-bottom: 15px;
    font-size: 1.8rem;
}

/* Image styling */
.styled-image {
    width: 100%;
    max-width: 600px;
    height: auto;
    display: block;
    margin: 20px auto;
    border: 3px solid #3498db;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    transition: transform 0.3s;
}

.styled-image:hover {
    transform: scale(1.02);
}

.caption {
    text-align: center;
    font-style: italic;
    color: #7f8c8d;
    margin-bottom: 20px;
}

/* Feature box styling */
.feature-box {
    background-color: #ecf0f1;
    padding: 20px;
    border-left: 5px solid #3498db;
    margin-top: 20px;
}

.feature-box h3 {
    color: #2c3e50;
    margin-bottom: 10px;
}
.feature-box li {
    margin-bottom: 8px;
    margin-left: 20px;
}
/* Footer styling */
#main-footer {
    text-align: center;
    padding: 20px;
    background-color: #2c3e50;
    color: white;
    border-radius: 5px;
}
