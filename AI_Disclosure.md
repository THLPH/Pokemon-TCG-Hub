

# AI Usage Disclosure

**Project:** Pokémon TCG Hub

**Course:** CSC 6370 Project 1

**Term:** Spring 2026

This file explains how we used AI in the project. We mainly used it for quick help, creating basic boilerplate, fixing tricky CSS, and doing light code review to keep things clean.

## 1. Content and Copywriting

AI helped write and polish most of the readable text in the app, so everything sounded clean, consistent, and on‑theme.

* **Site Copy:** AI helped draft the intro text on the Home page, including the “Welcome to the Arena” section, to help keep the wording clean and consistent.

* **Team Documentation:** AI helped format the project descriptions and role sections, such as Technical Duties and QA, so everything looked clean and consistent.

* **Game Rules:** AI gave us a quick summary of the turn‑by‑turn phases and the three win conditions so we could present them more clearly in the app.

* **Lobby Notices:** AI helped create the copy for the "Fair Play & AI Ethics" warning message.

* **Project Documentation:** AI helped write the feature overviews, explain the tech choices, and put together the instructions so everything was clear and easy to follow.

## 2. Structural Layout

AI helped set up the basic HTML structure and the main CSS layout systems, so we did not have to spend extra time repeating code.

* **HTML Skeletons:** AI generated the consistent `<header>`, `<nav>`, `<main>`, and `<footer>` structure used across all the HTML pages to keep everything consistent.

* **Layout Engines:** AI helped set up the CSS Grid layout that separates the Active Zone and Bench Zone on the game board, making it easier to keep the layout organized and consistent.

* **Base Styling:** AI helped us to set up the root CSS variables (like `--primary-bg` and `--accent-red`) to keep styling consistent.

## 3. Complex CSS and Animations

AI helped us to fix the more advanced, heavy CSS needed for the 3D effects and the interactive, state‑based elements, making those parts easier to build and fine‑tune.

* **3D Card Flips:** AI helped with the 3D card‑flip animation by providing the CSS for the depth effect (`perspective: 1000px`), the `preserve-3d` transform setuo, and the `180-degree` hover rotation.

* **Backface Rendering:** AI also helped us with the `-webkit-backface-visibility: hidden`  and small `translateZ(1px)` adjustments to stop the back of the card from being visible through the front during animations.

* **The "Checkbox Hack":** AI also helped us in learning how to write the CSS logic that links the hidden `#safety-toggle` checkbox to the `.safety-content` visibility, along with the `@keyframes slide-down` animation.

## 4. Code Review and Refinement

AI also helped review the code for quality, consistency, and alignment with modern web standards.

* **Accessibility:** AI helped add and code accessibility features like  `:focus-visible` outlines for keyboard navigation and the `prefers-reduced-motion` media query, which turns off 3D flips for users who are sensitive to motion.

* **Responsive Design:** AI helped review and fix the layout setup to ensure it scales properly on smaller screens, such as the flex-direction movement for the header.
