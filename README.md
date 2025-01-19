Blog Post Card Project

Overview

This project creates a visually appealing and responsive blog post card using HTML and CSS. The card is centered on the page and includes:

An image filling the card's width.

A title and excerpt for the blog post.

A call-to-action link styled as a button with hover effects.

This project demonstrates basic web development concepts such as Flexbox, Grid, and CSS styling.

Features

Responsive Design: The card is fully responsive and centered on any screen size.

Customizable Styling: Easy to update colors, fonts, and dimensions.

Interactive Elements: Includes a button with hover effects for better user engagement.

File Structure

project-folder/
├── index.html   # HTML structure of the blog post card
├── style.css    # CSS styling for the blog post card
└── README.md    # Documentation (this file)

How to Use

Prerequisites

A modern web browser (e.g., Chrome, Firefox, Edge).

Basic knowledge of HTML and CSS.

Steps

Clone the repository or download the files.

Open index.html in a browser to view the card.

Customize the style.css file to change styles as needed.

Code Highlights

HTML Structure

<div class="blog-post-card">
    <img src="https://cdn.freecodecamp.org/curriculum/labs/cover-photo.jpg"
         alt="Blog Cover" class="post-img">
    <div class="post-content">
        <h2 class="post-title">Blog Post Title</h2>
        <p class="post-excerpt">This is a summary of the blog post content.</p>
        <a href="#" class="read-more">Read More</a>
    </div>
</div>

CSS Styling

body {
    font-family: Arial, sans-serif;
    background-color: #f9f9f9;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    margin: 0;
}

.blog-post-card {
    background-color: #fff;
    border-radius: 8px;
    width: 300px;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.post-img {
    width: 100%;
    border-bottom: 2px solid #ddd;
}

.post-content {
    padding: 16px;
}

.post-title, .post-excerpt {
    margin: 16px 0;
    color: #333;
}

.read-more {
    display: inline-block;
    padding: 8px 16px;
    margin: 16px 0;
    background-color: #007BFF;
    color: #fff;
    border-radius: 4px;
    text-decoration: none;
    transition: background-color 0.3s;
}

.read-more:hover {
    background-color: #0056b3;
}

Customization

Image: Replace the src attribute in the <img> tag with your own image URL.

Colors: Update the background and text colors in the .blog-post-card, .post-title, and .read-more styles.

Dimensions: Adjust the width of .blog-post-card for larger or smaller cards.

Future Enhancements

Add responsiveness for larger or smaller devices using media queries.

Include animations for smoother hover effects.

Integrate with a backend for dynamic content generation.

License

This project is open-source and free to use. Contributions are welcome!


