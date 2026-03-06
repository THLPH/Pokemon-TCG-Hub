🎴 Pokémon TCG Hub

Welcome to the Pokémon TCG Hub, a lightweight, responsive web application built to help players visualize their board and master the basics of the game. This project was designed to prove that you can create a tactile, interactive experience using HTML and CSS.
🚀 The Tour
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

🏃 How to Run

    Clone the repository.

    Open index.html in any modern web browser.

    Enjoy the 3D cards!

CSC 6370 - Project 1 (Spring 2026)
