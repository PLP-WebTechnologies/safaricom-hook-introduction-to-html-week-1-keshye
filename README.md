[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/TUGW0SrP)
# Welcome to the HTML5 Basics Assignment repository! 

This assignment is designed to help you build foundational knowledge of HTML5, understand its structure, and practice creating web page content using semantic elements.

## Learning Objectives

By completing this assignment, you will:

  Understand the structure and purpose of HTML5 in web development.
  Learn to create basic web page content using core HTML5 elements.
  Explore semantic HTML elements and their benefits for readability and SEO.
  Gain a basic understanding of accessibility and SEO best practices in HTML.
  
## Assignment Content
  1. HTML5 Basics
Learn the structure of an HTML document (e.g., <!DOCTYPE html>, <html>, <head>, <body>).
Explore core elements such as headings, paragraphs, lists, links, and images.
  2. Semantic HTML
Introduction to semantic tags like <header>, <footer>, <nav>, <section>, and <article>.
Learn how semantic elements improve content readability and support SEO.
  3. Accessibility and SEO Basics
Understand the importance of accessible HTML and SEO-friendly practices.
Use attributes like alt, title, and semantic structures to improve usability.

## Activities

Creating a Simple Webpage: Design a basic webpage that includes text, images, and links.
Use common HTML tags like h1, p, a, img, and ul or ol.
Structure a webpage with semantic tags such as header, footer, nav, section, and article.
Ensure the content is well-organized for readability and SEO.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A simple webpage example with text, images, and links.">
    <title>Simple Webpage Example</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <h1>Welcome to My Simple Webpage</h1>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#gallery">Gallery</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<section id="about">
    <article>
        <h2>About This Page</h2>
        <p>This is a simple webpage designed to showcase basic HTML structure. It includes various HTML elements such as headings, paragraphs, images, and links.</p>
    </article>
</section>

<section id="gallery">
    <h2>Image Gallery</h2>
    <p>Here are some images:</p>
    <ul>
        <li><img src="image1.jpg" alt="Description of image 1" width="300"></li>
        <li><img src="image2.jpg" alt="Description of image 2" width="300"></li>
        <li><img src="image3.jpg" alt="Description of image 3" width="300"></li>
    </ul>
</section>

<section id="contact">
    <h2>Contact Me</h2>
    <p>If you have any questions, feel free to reach out!</p>
    <p>Email: <a href="mailto:example@example.com">example@example.com</a></p>
</section>

<footer>
    <p>&copy; 2023 My Simple Webpage. All rights reserved.</p>
    <p><a href="https://www.example.com" target="_blank">Visit my blog</a></p>
</footer>

</body>
</html>
