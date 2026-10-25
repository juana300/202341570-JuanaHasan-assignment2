# AI Usage Report

## 1. Tools Used and Use Cases

### ChatGPT

I used ChatGPT for the following tasks:

- Breaking assignment requirements into smaller steps.
- Getting suggestions for interactive features that could be added to my existing portfolio.
- Learning how to do project filtering using JavaScript.
- Adding CSS animations and transitions to improve the user experience.
- Improving the documentation for the project.

## 2. Benefits of Using AI

Using ChatGPT helped me understand the new assignment requirements and how to extend my portfolio from Assignment 1 without starting over.

It also helped me understand how JavaScript can be used to make the website more interactive. For example, I learned how to use JavaScript to filter projects based on the button selected by the user and how to use localStorage to remember the selected theme.

AI was also useful when debugging problems. When the contact form validation did not work as expected, I used ChatGPT to help identify the issue and understand how to fix it.

## 3. Challenges and Limitations

One challenge of using AI was that the suggested code did not always work correctly when added to my existing project.

For example, when I first implemented the contact form validation, the browser displayed its default validation message instead of the custom error messages. After adding the novalidate attribute, the custom messages still did not appear.

I reviewed the HTML and JavaScript code and found that the form-feedback element was missing from the HTML. I added the missing element and tested the form again until the error and confirmation messages appeared correctly. This showed me that AI suggestions still need to be checked and tested because they may require adjustments to work with the existing code.

## 4. Learning Outcomes

Through this assignment and the use of AI assistance, I improved my understanding of:

- Using JavaScript event listeners to respond to user interactions.
- Filtering project cards using data-filter and data-category attributes.
- Using localStorage to save and retrieve user preferences.
- Validating form inputs using JavaScript.
- Displaying error and confirmation messages based on user input.
- Using CSS transitions and animations to improve the user experience.
- Testing and modifying AI-generated suggestions instead of accepting them automatically.

## 5. Responsible Use and Modifications

I used AI as a learning and development assistant rather than submitting its output without reviewing it.

I reviewed the suggested features that can be possibly added to my portifolio website and make the final decision of what suits it the most.

I tested the project filtering buttons and verified that the dark/light mode preference was saved after refreshing the page.

When the contact form validation did not work correctly, I reviewed the HTML and JavaScript, added the missing element, and tested the form again until the messages appeared correctly.

I also tested the responsive layout using Chrome Developer Tools to make sure the new features worked on smaller screens.

Through this process, I made sure that I understood the main HTML, CSS, and JavaScript used in the project and that the final website reflected my own decisions and requirements.

## 6. Conclusion

This assignment helped me understand how AI can support software development while still requiring the developer skills in coding, understanding the code and making the final decisions.

## 7. AI Usage Log

The complete ChatGPT conversation is included in the ZIP.

| ID | Tool (model) | Date | Purpose | Files affected | What I changed and how I verified it |
| --- | --- | --- | --- | --- | --- |
| C01 | ChatGPT (GPT-6) | 2026-10-19 | Get step by step guidance for extending Assignment 1, suggesting and implementing features, debugging, and preparing documentation. | `index.html`, `css/styles.css`, `js/script.js`, `README.md`, `docs/technical-documentation.md`, `docs/ai-usage-report.md` | I chose to continue with HTML, CSS, and JavaScript, implemented the suggested features in my existing portfolio, and tested them in the browser and Chrome Developer Tools. |
| A01 | ChatGPT (GPT-6) | 2026-10-17 | Generate project-filtering as interactive feature. | `index.html`, `css/styles.css`, `js/script.js` | I added categories and filter buttons to my existing projects and tested All Projects, Web Apps, and Visualization to check which cards appeared. |
| A02 | ChatGPT (GPT-6) | 2026-10-17 | Implement dark mode functionality with `localStorage`. | `js/script.js` | I added the existing theme toggle and tested that light and dark mode stayed selected after refreshing the page. |
| A03 | ChatGPT (GPT-6) | 2026-10-17 | Generate contact-form validation and feedback suggestions and help debug them. | `index.html`, `js/script.js`, `css/styles.css` | I added `novalidate` and the missing `form-feedback` element, then tested empty inputs, invalid email addresses, and valid inputs until the messages appeared correctly. |
| A04 | ChatGPT (GPT-6) | 2026-10-18 | Suggest CSS hover effects, smooth scrolling, animations for project card and buttons. | `css/styles.css` | I added the suggested styling to my existing CSS and reviewed the layout and interactions in the browser, including mobile view. |
| A05 | ChatGPT (GPT-6) | 2026-10-18 | Draft updated Assignment 2 README content. | `README.md` | I reviewed the draft against my portfolio features and done some modifications and updated the project documentation. |
| A06 | ChatGPT (GPT-6) | 2026-10-18 | Draft technical documentation describing the interactive features and testing. | `docs/technical-documentation.md` | I reviewed the explanations against the implementation and the tests described in my development process and done some modifications to the documentation. |
| A07 | ChatGPT (GPT-6) | 2026-10-18 | Draft AI usage report. | `docs/ai-usage-report.md` | I reviewed and modified the report to describe my actual AI use, debugging experience, modifications, and learning outcomes. I added the new ai declaration requirements. |

## 8. Commits
Commits containing ai assisted code that is assisted-by: ChatGPT (GPT-6)
- Add project filtering functionality  as an interactive feature
- Implement dark mode functionality with localStorage support
- Add contact form validation with user feedback and error messages
- Add smooth scrolling and hover effects for project cards and buttons
- Fix nested paragraph tags in the About Me section


## 9. AI Usage Declaration

I declare that this report and the attached evidence document all of my AI use in this assignment, with complete and unedited conversations, and that I understand and can explain all the code I submitted. I understand that undeclared AI use or a false declaration will be treated as plagiarism according to KFUPM regulations.

Name: Juana
Id: 202341570
Date: 2026-10-25