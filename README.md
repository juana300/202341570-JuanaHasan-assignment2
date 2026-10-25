# Personal Portfolio Website - Assignment 2

## Project Description

This project is an interactive and responsive personal portfolio website developed for Assignment 2 of the Web Engineering course.

It builds on the portfolio created in Assignment 1 by adding interactive features and improving the user experience. The website introduces me, showcases my projects, and provides a contact form with input validation and user feedback.

The website was developed using HTML, CSS, and JavaScript, with a focus on interactivity, responsive design, and usability across different screen sizes

## Features

- About Me section
- Projects section with project screenshots and descriptions
- Interactive project filtering (All Projects, Web Apps, and Visualization)
- Contact form with name, email, and message fields
- Form validation with error and confirmation messages
- Responsive design for desktop, tablet, and mobile devices
- Light and dark mode toggle with theme preference saved using localStorage
- Smooth scrolling between sections
- Hover effects on buttons and project cards
- Animated form feedback messages

## Technologies Used

- HTML
- CSS
- JavaScript
- CSS Flexbox
- CSS Media Queries
- CSS Transitions and Animations
- Browser localStorage
- Git and GitHub

## How to Run the Project

1. Clone or download this repository.
2. Open the project folder.
3. Open `index.html` in a web browser.

No additional installation or dependencies are required.

## Interactive Features

### Project Filtering

Users can filter the displayed projects by selecting All Projects, Web Apps, or Visualization. JavaScript updates the visible project cards based on the selected category.

### Dark and Light Mode

Users can switch between light and dark mode using the theme toggle button. The selected theme is saved using localStorage, allowing the website to remember the preference after refreshing the page.

### Contact Form Validation

The contact form checks that all required fields are filled in and that the email address follows a valid format. If the input is invalid, an error message is displayed. If all fields are valid, a confirmation message appears.

The contact form is a demonstration feature and does not send messages to a server.

### Animations and Transitions

Smooth scrolling, button hover effects, project card transitions, and animated form feedback messages were added to improve the user experience.

### Responsive Design

The website is designed to work on desktop, tablet, and mobile screen sizes. CSS Flexbox and media queries are used to adjust the layout for smaller screens.
## AI Usage

ChatGPT was used during the development of this assignment to help break down the requirements, suggest interactive features, explain JavaScript concepts, and assist with debugging and code improvements. AI assistance was particularly useful for implementing project filtering, saving theme preferences using localStorage, and developing contact form validation.

The generated suggestions were reviewed, tested, and adjusted during development.

A detailed explanation of AI usage is available in:

`docs/ai-usage-report.md`


## Project Structure

```text
├── assets/
│   └── images/
│       ├── project1.png
│       └── project2.png
├── css/
│   └── styles.css
├── docs/
│   ├── ai-usage-report.md
│   └── technical-documentation.md
├── js/
│   └── script.js
├── index.html
└── README.md