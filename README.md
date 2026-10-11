Personal Portfolio Website

1. Project Overview

This project is a personal portfolio website created for Web and Scripting Programming. It uses HTML5 and CSS3 to present my introduction, personal information, academic projects, and contact information.

The website consists of four separate pages:

Home: Introduces the portfolio and provides navigation to the other pages.

About Me: Contains my personal photo, a short introduction, and an embedded introductory video.

Projects: Describes projects and assignments I have completed during my studies.

Contact Me: Provides a contact form with input validation for the user's name, email address, cellphone number, and comments.

The website uses semantic HTML elements, responsive layouts, and CSS styling. It is intended to be hosted publicly using GitHub Pages.

2. Technologies Used

HTML5: Creates the structure and content of the website.

CSS3: Controls the website's colours, typography, spacing, gradients, and responsive layouts.

Media Queries: Apply different styles depending on the viewport width.

Git and GitHub: Track changes to the project and store the source code.

GitHub Pages: Hosts the portfolio website.

3. Project Structure

The project is organized into separate HTML pages, CSS files, and media folders.

Assiginment-1-portfolio/
├── css/
│   ├── base.css
│   ├── mobile.css
│   ├── tablet.css
│   └── laptop.css
├── images/
│   ├── profile.jpg
│   └── video-poster.jpg
├── videos/
│   └── introduction.mp4
├── about.html
├── contact.html
├── index.html
├── projects.html
└── README.md

The base.css file contains the shared styles used throughout the website. The other CSS files contain styles for specific viewport sizes. The images and videos folders store the media used on the website.

4. Colour Scheme

The website uses a dark navy and teal colour scheme for a modern IT portfolio design.

Midnight Navy: #101827 — main background

Slate Blue-Grey: #1D2A3D — header and content cards

Teal: #19B6A4 — buttons and accents

Off-White: #F4F7FA — main text

Muted Blue-Grey: #A8B5C7 — secondary text

The teal accents contrast with the dark backgrounds, while the lighter text improves readability.

5. Responsive Design

Separate CSS files are used for mobile, tablet, and laptop layouts.

Mobile: Up to 600px. Content is arranged vertically to fit narrow screens.

Tablet: 601px–1024px. Layouts use the additional space available on medium-sized screens.

Laptop/Desktop: 1025px and above. Wider layouts allow content such as project cards to appear side by side.

The website uses media queries and percentage-based widths. Flexbox is not used.

6. CSS Gradients

Two types of linear gradients are used in the website.

Normal linear gradient

A normal linear gradient is used for the hero section on the website.

Example:

background: linear-gradient(to right, #101827, #1D2A3D);

The gradient transitions horizontally from midnight navy to slate blue-grey, adding depth to the section while keeping the design consistent.

Angled linear gradient

An angled linear gradient is used on buttons and accent elements.

Example:

background: linear-gradient(135deg, #087F8C, #19B6A4);

The gradient transitions diagonally between two teal shades to make interactive elements stand out from the darker background.

7. Form Validation

The Contact Me page includes a form with the following validation rules:

Full Name: Required, with a minimum of 2 characters and a maximum of 100 characters.

Email Address: Required and checked against an email format pattern.

Cellphone Number: Required and restricted to 10–15 digits.

Comments: Required, with a minimum of 5 characters and a maximum of 1,000 characters.

The form uses HTML attributes such as required, minlength, maxlength, type="email", and pattern to provide browser-based validation.

The current form does not use a server-side system to deliver messages to an email inbox.

8. Semantic HTML and Accessibility

Semantic HTML elements are used to organize the website's content and improve its structure. These include:

<header> for the page header.

<nav> for navigation links.

<main> for the primary page content.

<section> and <article> for grouped content and project descriptions, where appropriate.

<footer> for contact information and copyright details.

Form controls have associated labels, and the navigation identifies the current page. Images should have appropriate alternative text, and the website should be checked for accessibility issues before submission.

9. Testing and Validation

The following checks will be performed before submission.

HTML validation: Check the HTML pages using the W3C Markup Validation Service.

CSS validation: Check the CSS files using the W3C CSS Validation Service.

Link validation: Use the W3C Link Checker to identify broken links.

Spelling: Review the page text and correct spelling and grammar errors.

Accessibility: Test the website using the WAVE Web Accessibility Evaluation Tool.

Responsive design: Test the website at mobile, tablet, and laptop/desktop widths.

Navigation: Confirm that the links between all four pages work correctly.

Contact form: Test required fields and confirm that invalid email addresses and cellphone numbers are rejected.

Media: Confirm that the profile photo and introductory video load correctly and that the video controls work.

The checklist will be updated after the tests have been completed.

10. Version Control and Deployment

The source code is maintained in a GitHub repository. Commits are used to document important stages of development, such as creating the pages, implementing the styling, adding responsive layouts, and completing validation.

The website will be published using GitHub Pages.

Live website: [Add the published GitHub Pages URL here]

GitHub repository: [Add the public repository URL here]

11. References and External Resources

The following resources may be used to validate and test the website:

W3C Markup Validation Service: https://validator.w3.org/

W3C CSS Validation Service: https://jigsaw.w3.org/css-validator/

W3C Link Checker: https://validator.w3.org/checklink

WAVE Web Accessibility Evaluation Tool: https://wave.webaim.org/

Any external code, tutorials, or other resources used in the implementation must be identified here, with the source and author where available, in accordance with the assignment requirements.