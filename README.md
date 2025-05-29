# Demo-AutomationTesting-Website-with-all-elements
This is demo automation testing website. You can use cypress tool for testing in this site. This website has all web elements.

Link : https://qatester1320.github.io/Demo-AutomationTesting-Website-with-all-elements/

Cypress Automation Testing Demo Site
This repository contains a comprehensive demo website designed specifically for practicing and demonstrating Cypress automation testing. It features a wide array of interactive UI elements, dynamic content, and common web application functionalities, making it an ideal playground for learning and refining your Cypress skills.

Features :
The demo site includes the following sections and interactive elements:

Forms with Various Input Types:

Text, Password, Number Inputs
Dropdown (Select)
Radio Buttons
Checkboxes
Textarea
Form Submission and Validation feedback
File Uploads:

Single File Upload
Multiple File Upload
Drag and Drop File Upload
Shadow DOM File Upload: Demonstrates interacting with elements encapsulated within a Shadow DOM.
Interactions & Dialogs:

Hover effects with Tooltips
Custom Modal Dialogs: Simulating application-specific modals.
Native Browser Dialogs (Alert, Confirm, Prompt): Designed to show how Cypress handles browser-native pop-ups, even if they don't visibly appear in headless modes or iframes.
Primary and Secondary Buttons with click feedback
Internal and External Links
Tabs: Interactive tab navigation with different content sections.
Accordions: Collapsible content panels.
Slider/Carousel: Image/content rotator.
Date Pickers
Keyboard Interactions (e.g., Enter key detection)
Dynamic Content & Scrolling:

Search with Autocomplete: Dynamic auto-suggest dropdown for search inputs.
Advanced Filter Dropdown: A multi-select filter simulation.
Dynamic Dropdown: Dependent dropdowns (e.g., Country selects City).
Tables with Sorting, Filtering, and Pagination: Interactive data table functionalities.
Scroll Testing Area: A long list designed to demonstrate infinite scrolling or specific scroll position testing.
E-commerce Functionality (Shopping Cart):

Product display with "Add to Cart" buttons.
Shopping cart display with quantity adjustment and item removal.
Cart total calculation and checkout simulation.
Admin Panel:

Login form with pre-filled credentials for easy access.
Simulated admin dashboard with various management sections.
Logout functionality.
Advanced Interactions:

Window Handling: Button to open a new blank browser window/tab.
Iframe Handling: An embedded iframe with its own interactive elements to practice cross-origin or iframe element selection.
Mouse Operations: Elements demonstrating dblclick (double-click) and contextmenu (right-click) events.
Responsive Layout Elements:

The entire site is built with responsive design using Tailwind CSS, adapting to different screen sizes.
Technologies Used
HTML5: For semantic structure.
Tailwind CSS: For rapid and responsive UI styling.
JavaScript: For all interactive functionalities and dynamic content generation.
Font Awesome: For icons.
How to Use for Cypress Testing
This demo site is a single HTML file, making it incredibly easy to set up and use with Cypress:

Save the Code: Copy the entire HTML content and save it as an .html file (e.g., cypress_demo.html) in a location accessible to your Cypress project (e.g., in your cypress/fixtures folder or a public folder).

Start Cypress: Open your Cypress project in your terminal and run cypress open.

Create a Test File: Inside your cypress/e2e folder, create a new JavaScript file (e.g., demo_site.cy.js).

Visit the Page: In your test file, use cy.visit() to load the HTML file.
