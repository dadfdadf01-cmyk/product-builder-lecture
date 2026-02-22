# Application Blueprint

## Overview

This is a simple lottery number recommendation web application. It allows users to generate a set of random lottery numbers.

## Style, Design, and Features

*   **UI:**
    *   A main container with a title.
    *   A button to generate lottery numbers.
    *   A section to display the generated numbers.
    *   **Theme Toggle:** A button to switch between Light Mode and Dark Mode.
*   **Styling:**
    *   Modern and clean design.
    *   Responsive layout for mobile and web.
    *   Use of CSS variables for theming (Light/Dark).
    *   Interactive animations for number generation.
*   **Functionality:**
    *   Clicking the "Generate" button will produce 6 unique random numbers between 1 and 45.
    *   Numbers are sorted in ascending order.
    *   Persistence: Theme preference is saved in `localStorage`.
    *   **Formspree Integration:** A functional contact/affiliate form for user inquiries.

## Task Progress

*   **Task 1: Create Lottery Number Recommendation Page (Completed)**
    *   HTML structure created.
    *   Basic styling added.
    *   Logic to generate 6 random numbers implemented.
*   **Task 2: Implement Dark/Light Mode (Completed)**
    *   CSS variables added for both themes.
    *   Toggle button and logic added to `index.html` and `main.js`.
    *   Persistence implemented via `localStorage`.
    *   Added animations and sorting for better UX.
*   **Task 3: Implement Affiliate Contact Form (Completed)**
    *   Integrated Formspree for handling form submissions.
    *   Added styling for form inputs to match theme.
    *   Form fields: Name, Email, Message.
