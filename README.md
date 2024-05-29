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

### Directory and File Description

  - images/: This directory contains all image files used on the website.
  - whiskey-background.jpg: The background image for the callout container.
  - girl-image.png: Image used for the testimonial from Jane Doe.
  - guy-image.png: Image used for the testimonial from John Doe.
  - index.html: The main HTML file that structures the content of the Whiskey Drop homepage. 
    It includes sections such as navigation, callout, quotes, features, and a sign-up modal.

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

### Explanation
#### Fonts and Body Styles:

  - Sets the default font family to 'Roboto', ensuring a modern and clean look.

#### Containers:

  - callout-container: Defines a full-screen section with a background image, centered content using Flexbox, and a semi-transparent overlay.
  - opaque-overlay: Adds a semi-transparent black overlay to the callout container for better text readability.
  - quotes-container: Sets the text color for the quotes section.
  - features-container: Defines styles for the features section with uppercase text and specific background color.

#### Features:

  - Adds hover effects to feature boxes, including shadow and background color change for better interactivity.

#### Block Dividers:

  - Custom styles for horizontal dividers used between sections. Includes specific colors and sizes.

#### Jumbotron:

  - Styles for the jumbotron, including text colors, font weights, and margins.

#### Buttons:

  - Custom styles for call-to-action buttons, including colors, border radius, and hover effects.

#### Badge:

  - Custom styles for the success badge, altering its default color scheme.

#### Usage
  - These custom styles are applied throughout the index.html file to enhance the visual presentation and user experience. 
By following the CSS conventions and utilizing classes appropriately, the Whiskey Drop website maintains a consistent and engaging look.

## JavaScript

Bootstrap's JavaScript and its dependencies are included to enable interactive components like the modal and the dropdown menu.

## Script Example

By following this example, you can ensure that the interactive components of the Whiskey Drop website work seamlessly.

## Usage in the Project
By including these scripts at the end of the index.html file, we ensure that the necessary libraries are loaded after the HTML content, which helps in reducing the initial page load time and ensures that the DOM is fully loaded before any JavaScript code runs. This setup enables functionalities like the modal for sign-up and the dropdown menu for whiskey categories.

## How to Run

  - Clone the repository.
  - Open index.html in your web browser to view the website.

Enjoy exploring the world of whiskey with Whiskey Drop!

 This README file provides an overview of the Whiskey Drop project, including its features, technologies used, file structure, and how to run it. It also highlights the different sections of the webpage and includes code snippets to illustrate the structure and styling of the website.
