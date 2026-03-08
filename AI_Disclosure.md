

# AI Usage Disclosure

**Project:** Pokémon TCG Hub

**Course:** CSC 6370 Project 1

**Term:** Spring 2026

This document outlines the extent to which Artificial Intelligence (AI) was utilized in the development of this project to ensure academic transparency. AI was used as a tool for copywriting, boilerplate generation, complex styling, and overall code review.

## 1. Content and Copywriting

AI was used to generate and refine the majority of the human-readable text across the application to ensure a professional and thematic tone.

* **Site Copy:** AI drafted the introductory text on the Home page, including the "Welcome to the Arena" section.

* **Team Documentation:** AI formatted the project descriptions, role breakdowns (e.g., Technical Duties, Quality Assurance).

* **Game Rules:** AI summarized the step-by-step turn phases and the three win conditions.

* **Lobby Notices:** AI generated the copy for the "Fair Play & AI Ethics" warning message.

* **Project Documentation:** AI assisted in writing the feature overviews, technology explanations, and the "How to Run" instructions.

## 2. Structural Layout

AI assisted in building the foundational HTML document structure and the core CSS layout systems to save time on boilerplate code.

* **HTML Skeletons:** AI generated the consistent `<header>`, `<nav>`, `<main>`, and `<footer>` scaffolding used across all HTML pages.

* **Layout Engines:** AI helped configure the CSS Grid architecture used to separate the Active Zone and Bench Zone on the game board.

* **Base Styling:** AI established the root CSS variables (like `--primary-bg` and `--accent-red`) and the global reset rules.

## 3. Complex CSS and Animations

AI was leveraged to write the more advanced, math-heavy CSS properties required for 3D rendering and state-based interactive elements.

* **3D Card Flips:** AI assisted in the 3D Card Flip animation logic. AI provided the CSS rules for the 3D depth effect (`perspective: 1000px`), the `preserve-3d` transform style, and the `180-degree` hover rotation.

* **Backface Rendering:** AI supplied the specific `-webkit-backface-visibility: hidden` vendor prefixes and `translateZ(1px)` adjustments to prevent the back of the card from clipping through the front during animations.

* **The "Checkbox Hack":** AI wrote the CSS logic that ties the hidden `#safety-toggle` checkbox to the `.safety-content` visibility, along with the `@keyframes slide-down` animation.

## 4. Code Review and Refinement

AI served as a secondary reviewer to check the overall code quality, consistency, and adherence to modern web standards.

* **Accessibility:** AI assisted in implementing accessibility features, such as `:focus-visible` outlines for keyboard navigation and the `prefers-reduced-motion` media query to disable 3D flips for sensitive users.

* **Responsive Design:** AI reviewed and refined the layout engines to ensure proper scaling on smaller screens, such as the flex-direction shift for the header.
