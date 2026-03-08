# 🎴 Pokémon TCG Hub

Welcome to the Pokémon TCG Hub, a lightweight, responsive web application built to help players visualize their board and master the basics of the game. This project was designed to prove that you can create a tactile, interactive experience using HTML and CSS.

[🏃 Jump to Run Instructions](#-how-to-run) | [⚖️ Jump to AI Disclosure](#-project-integrity--ai-disclosure)

# 📝 Pages Overview

🏟️ The Deck Table

The heart of the app. It uses CSS Grid to create a structured "Arena" where you can manage your Active Pokémon and your Bench.

    3D Card Flips: Hover over (or tap) any card to see it flip in 3D space.

    Tactile Zones: Distinct visual areas for the Active spot and the Bench, styled with Pokémon-themed accents.

🤝 Game Lobby

A simulated matchmaking environment.

    Status Tracking: Check which rooms are open or currently in a match.

    The "Checkbox Hack": A CSS-only interactive "Fair Play Notice." It uses a hidden checkbox and the sibling selector (~) to toggle content visibility without a single line of script.

📜 Rules & Strategy

A quick-reference guide for the heat of battle.

    Turn Phases: A clean breakdown of Draw, Attach, Play, and Attack phases.

    Stat Comparison: A side-by-side look at how stats scale from a Basic Pokémon (Charmander) to a Stage 2 Evolution (Charizard).

🛠️ Behind the Scenes (The Tech)

    Layout Engine: Powered by CSS Grid for the complex table layout and Flexbox for the responsive navigation and lobby.

    Animations: Custom @keyframes and perspective transforms create smooth 3D motion.

    Accessibility First: * Focus States: High-visibility blue outlines for keyboard navigation.

    Reduced Motion: A dedicated media query that disables 3D flips for users who prefer less movement.

    Themed Styling: A centralized system of CSS variables ensures the "Pokémon Red" and "Pokémon Blue" aesthetic is consistent across every page.

<a id="-how-to-run"></a>
🏃 How to Run

    Clone the repository.

    Open index.html in any modern web browser.

    Enjoy the 3D cards!

<a id="-project-integrity--ai-disclosure"></a>
⚖️ Project Integrity & AI Disclosure

This project was developed for CSC 6370 (Spring 2026). In alignment with academic honesty and transparency, a full breakdown of AI usage for copywriting, 3D CSS logic, and boilerplate generation is documented.
View the Full Disclosure: [⚖️ AI Disclosure](./AI_Disclosure.md)

## 📓 Development Journal & Challenges
Building a purely HTML/CSS project without JavaScript helped us get creative, especially with the interactive elements. 

* **The Checkbox Hack:** Figuring out how to toggle the Fair Play Notice in the lobby was a fun challenge. I ended up relying on a hidden checkbox and the `~` sibling selector to trigger the state change.
* **3D Card Flips:** Getting the `backface-visibility` to play nicely across different elements took some trial and error, specifically ensuring the text didn't bleed through the back of the card during the `rotateY(180deg)` transition. 
* **Layout Choices:** I initially tried building the entire table using Flexbox, but quickly realized CSS Grid was vastly superior for creating the rigid, defined zones for the Active and Bench areas.

CSC 6370 - Project 1 (Spring 2026)
