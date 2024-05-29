# Whiskey Drop

## Overview

Welcome to Whiskey Drop, where you can taste a new whiskey every month! Our service delivers the finest whiskeys from around the world directly to your doorstep. Sign up today and enjoy your first bottle for free!

## Features

- **Monthly Whiskey Delivery:** Receive a carefully selected bottle of whiskey every month.
- **Variety of Whiskeys:** Discover Irish, Scotch, Japanese, and American whiskeys.
- **First Bottle Free:** Sign up now and get your first bottle on us.

## Technologies Used

- **HTML5 & CSS3:** For structuring and styling the web page.
- **Bootstrap 4:** To create a responsive and modern layout.
- **FontAwesome:** For using icons throughout the website.
- **Google Fonts:** For custom fonts.

## File Structure


## Sections 

1. Navigation

The navigation bar includes links to Home, About, Whiskeys (with dropdown for different types), and Sign In/Sign Up.

<nav class="navbar navbar-light navbar-expand-sm bg-light">
    ...
</nav>

2. Alert Box

An important alert message for visitors regarding age restrictions and responsible drinking.

<div class="alert-container">
    ...
</div>

3. Callout

A full-screen section with a promotional message and a sign-up call to action.

<div class="container-fluid callout-container">
    ...
</div>

4. Quotes

Customer testimonials displayed in a media object format for a better visual representation.

<div class="container quotes-container">
    ...
</div>

5. Features

A section highlighting the main features of the service, including special offers.

<div class="features-container">
    ...
</div>

6. Sign-Up Modal

A modal form for new users to sign up for the service.

<div class="modal" tabindex="-1" role="dialog" id="signUpModal">
    ...
</div>

## Styling
The custom CSS styles are applied to ensure a consistent look and feel:

  - Fonts: 'Roboto' from Google Fonts.
  - Colors: A palette of white, black, green, and orange.
  - Layout: Flexbox and Bootstrap grid for responsive design.
  - Transitions and Effects: Smooth transitions on hover and shadow effects.

## Custom CSS Example

body {
    font-family: 'Roboto', sans-serif;
}

/* Callout Container */
.callout-container {
    height: 100vh;
    background: url('images/whiskey-background.jpg') no-repeat center center fixed;
    background-size: cover;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
}

.opaque-overlay {
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    background-color: rgba(0, 0, 0, 0.5);
}

/* Buttons */
.btn--cta {
    font-weight: bold;
    border-radius: 23px;
    width: 160px;
}

.btn--red {
    color: white;
    background-color: #f05f40;
    border-color: #f05f40;
}

## JavaScript
Bootstrap's JavaScript and its dependencies are included to enable interactive components like the modal and the dropdown menu.

## Script Example

## How to Run
  - Clone the repository.
  - Open index.html in your web browser to view the website.

Enjoy exploring the world of whiskey with Whiskey Drop!


This `README.md` file provides an overview of the Whiskey Drop project, including its features, technologies used, file structure, and how to run it. It also highlights the different sections of the webpage and includes code snippets to illustrate the structure and styling of the website.
