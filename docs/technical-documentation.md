# Technical Documentation

## 1. Project Overview

This project is an interactive and responsive personal portfolio website developed using HTML, CSS, and JavaScript.

It builds on Assignment 1 by adding project filtering, saved light/dark mode preferences, contact form validation, and animations to improve the user experience.

## 2. HTML Structure

The main structure and content of the website are contained in `index.html`.

The page includes:

- **Header and Navigation:** Contains my name and navigation links to the About, Projects, and Contact sections.
- **About Me:** Contains a short introduction about me.
- **Projects:** Displays two projects with screenshots and descriptions, along with buttons to filter projects by category.
- **Contact:** Contains a form with Name, Email, and Message fields as well as validation and feedback messages.

HTML elements such as `header`, `nav`, `main`, `section`, and `article` are used to organize the content.

Additional HTML attributes such as data-filter and data-category are used to identify project categories for filtering.

## 3. CSS Styling

The website styling is contained in `css/styles.css`.

CSS Flexbox is used to arrange elements such as the navigation bar and project cards.

Additional CSS styles were added for the active filtering button, form validation messages, and animations.

CSS transitions are used to create smooth hover effects on buttons and project cards. Smooth scrolling was also added to improve navigation between sections.

## 4. Responsive Design

The website is designed to work on desktop, tablet, and mobile screen sizes.

A CSS media query is used for screens with a maximum width of 768px.

On smaller screens:

- The navigation layout is adjusted.
- The project cards change from a horizontal layout to a vertical layout.
- Padding and spacing are reduced to fit smaller screens.
- The contact form adjusts to the available screen width.
- The project filtering buttons can wrap to fit smaller screens.

The responsive layout was tested using Chrome Developer Tools.

## 5. JavaScript Functionality

The JavaScript code is contained in `js/script.js`.

JavaScript is used to implement project filtering, persistent light/dark mode, and contact form validation.

### Project Filtering

Users can select All Projects, Web Apps, or Visualization. JavaScript uses the data-filter and data-category attributes to show or hide project cards based on the selected category.

### Dark and Light Mode

The theme toggle adds or removes the dark-mode class and updates the moon/sun icon. The selected theme is saved using localStorage and restored when the page loads.

### Contact Form Validation

JavaScript checks that the Name, Email, and Message fields are not empty and that the email follows a valid format.

Invalid inputs display error messages, while valid inputs display a confirmation message and clear the form. The form uses preventDefault() to avoid refreshing the page.

The contact form is a demonstration feature and does not send messages to a server.


## 6. Error Handling and User Feedback

The website provides feedback to users when interacting with the contact form.

If required fields are empty, error messages are displayed to explain what information is missing.

If the email address has an invalid format, the user is asked to enter a valid email address.

When all fields are valid, a confirmation message appears.

Error and confirmation messages use different colors to help users understand the result.
## 7. Testing

The website was tested throughout development to make sure the required features worked correctly.

The following tests were tested:

- Navigation links between sections and project filtering.
- Light/dark mode and saved theme preferences after refreshing.
- Contact form validation with empty, invalid, and valid inputs.
- Project images, animations, and hover effects.
- Responsive layout on desktop and mobile, including the iPhone 16 Pro Max device view.
- Vertical stacking of project cards and scrolling on smaller screens.

## 8. Technologies Used
- HTML
- CSS3, Flexbox, Media Queries, and Animations
- JavaScript and Browser localStorage
- Chrome Developer Tools
- Git and GitHub