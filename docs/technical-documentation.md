# Technical Documentation

## 1. Project Overview

This project is a responsive personal portfolio website developed using HTML, CSS, and JavaScript.

The website contains three main sections: About Me, Projects, and Contact. It also includes responsive design for different screen sizes and a light/dark theme toggle.

## 2. HTML Structure

The main structure and content of the website are contained in `index.html`.

The page includes:

- **Header and Navigation:** Contains my name and navigation links to the About, Projects, and Contact sections.
- **About Me:** Contains a short introduction about me.
- **Projects:** Displays two projects with screenshots and descriptions.
- **Contact:** Contains a form with Name, Email, and Message fields.

HTML elements such as `header`, `nav`, `main`, `section`, and `article` are used to organize the content.

## 3. CSS Styling

The website styling is contained in `css/styles.css`.

CSS is used to control the colors, spacing, typography, navigation bar, project cards, contact form, and light/dark themes.

Flexbox is used to arrange elements such as the navigation bar and project cards.

## 4. Responsive Design

The website is designed to work on desktop, tablet, and mobile screen sizes.

A CSS media query is used for screens with a maximum width of 768px.

On smaller screens:

- The navigation layout is adjusted.
- The project cards change from a horizontal layout to a vertical layout.
- Padding and spacing are reduced to fit smaller screens.
- The contact form adjusts to the available screen width.

The responsive layout was tested using Chrome Developer Tools.

## 5. JavaScript Functionality

The JavaScript code is contained in `js/script.js`.

JavaScript is used to implement the light/dark mode feature. When the user clicks the theme toggle button, JavaScript adds or removes the `dark-mode` class from the page.

The button icon also changes between a moon and sun depending on the selected theme.

## 6. Project Images

Screenshots of my projects are stored in the `assets/images/` folder.

The images are displayed in the Projects section using HTML `<img>` elements. CSS is used to control the size and appearance of the images so that they fit properly inside the project cards.

## 7. Testing

The website was tested throughout development to make sure the required features worked correctly.

The following tests were performed:

- Tested the navigation links between sections.
- Tested the light/dark mode toggle.
- Checked that the project images displayed correctly.
- Checked the contact form layout.
- Tested the website at different screen sizes.
- Used Chrome Developer Tools to test the mobile layout at approximately 400px width.
- Checked that the project cards changed to a vertical layout on smaller screens.