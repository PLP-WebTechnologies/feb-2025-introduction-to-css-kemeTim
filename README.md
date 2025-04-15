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


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>K.T. | Saxophonist & Technologist</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header id="main-header">
        <h1 class="title">K.T. - Sax & Syntax</h1>
    </header>

    <section class="bio">
        <p>Where music meets machine — blending smooth jazz with cutting-edge code.</p>
        <img src="https://via.placeholder.com/350x250" alt="Saxophonist Photo" class="styled-img">
    </section>

    <section class="quote">
        <blockquote>"Improvisation is not just music — it's life unfolding in real time."</blockquote>
    </section>

    <footer>
        <p id="footer-text">Crafted by K.T. | © 2025</p>
    </footer>
</body>
</html>

/* Jazz-inspired CSS for a personal webpage */
/* Jazz-inspired color palette */
/* Base styles */
body {
    margin: 0;
    padding: 0;
    font-family: 'Courier New', Courier, monospace;
    background-color: #1a1a1a;
    color: #f0f0f0;
}

/* Header with a deep blue tone */
#main-header {
    background-color: #002244;
    color: #ffcc00;
    padding: 30px;
    text-align: center;
    border-bottom: 4px solid #ffcc00;
}

/* Class selector for heading */
.title {
    font-size: 2.5em;
    font-family: 'Lucida Console', monospace;
    letter-spacing: 2px;
}

/* Bio section styling */
.bio {
    margin: 40px auto;
    padding: 20px;
    max-width: 700px;
    background-color: #2e2e2e;
    border-left: 6px solid #ffcc00;
    border-radius: 8px;
}

/* Styling the image with a smooth, jazz-inspired border */
.styled-img {
    display: block;
    margin: 20px auto;
    border: 6px solid #444;
    padding: 5px;
    border-radius: 10px;
}

/* Quote section */
.quote {
    text-align: center;
    font-style: italic;
    margin: 30px;
    padding: 15px;
    background-color: #262626;
    border-top: 2px dashed #ffcc00;
    border-bottom: 2px dashed #ffcc00;
}

/* Footer with a mellow outro */
#footer-text {
    text-align: center;
    padding: 15px;
    background-color: #111;
    color: #aaa;
    font-size: 0.9em;
}


