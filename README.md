# Astroverse

AstroVerse - Interactive Solar System
Overview
AstroVerse is a modern, interactive astronomy website built with HTML, JavaScript, Three.js, and Tailwind CSS. It features a 3D top-down view of the solar system with orbiting planets, an asteroid belt, visible orbital paths, and a rocket animation on page load. Users can hover over planets to enlarge them and click/touch to zoom in with a hyperspace animation, displaying a detailed information card.
Features

3D Solar System: Top-down view with a central Sun and eight planets (Mercury to Neptune) orbiting along visible gray paths.
Rocket Animation: A white rocket flies from bottom-left to top-right on page load, following a curved path over 3 seconds.
Asteroid Belt: 200 asteroids orbiting between Mars and Jupiter.
Interactive Planets: Hover to scale planets to 1.5x size; click/touch to zoom with a 1-second hyperspace animation (blue radial gradient) and show a detailed card.
Planet Cards: Semi-transparent, blurred cards display planet name, description, and unique speciality, with a "Close" button to return to the overview.
Starry Background: 300 twinkling stars with a glow effect, created with CSS animations.
Smooth Rendering: High-resolution planet models (64x64 segments) with antialiasing for crisp visuals.
Responsive Design: Works seamlessly on desktop and mobile, with touch support.

Technologies Used

HTML5: Structure of the single-page application.
JavaScript: Logic for animations and interactions, using Three.js (r128) for 3D rendering.
Three.js: Handles 3D solar system, rocket, and asteroid belt rendering.
Tailwind CSS: Styling for the header, planet cards, and responsive layout.
CSS Animations: Starry background and hyperspace effects.

Setup Instructions

Download the Project:

Save the index.html file from the project source.
No additional files are required, as dependencies are loaded via CDNs.


Dependencies:

The project uses external CDNs:
Three.js: https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js
Tailwind CSS: https://cdn.tailwindcss.com


An internet connection is required to load these dependencies.


Run the Project:

Open index.html in a modern web browser (e.g., Chrome, Firefox, Edge).
No local server is required, as the project runs directly in the browser.



Usage

On Load: A white rocket flies from the bottom-left to the top-right of the screen over 3 seconds, disappearing afterward.
Navigation: 
Hover over a planet to enlarge it.
Click or tap a planet to zoom in with a hyperspace animation and view its details in a centered card.
Click the "Close" button on the card to return to the top-down solar system view.


Responsive: Use on desktop (mouse) or mobile (touch) devices.

Project Structure

index.html: The single file containing HTML, CSS (Tailwind and custom styles), and JavaScript (Three.js logic).
No external assets (e.g., textures) are used, keeping the project lightweight.

Notes

Ensure a stable internet connection to load Three.js and Tailwind CSS.
The rocket animation runs only once on page load.
Asteroids are non-interactive to maintain focus on planets.
The project is optimized for performance but may require a modern browser for best results.

License
This project is for educational and demonstration purposes. Feel free to modify and use it as needed, respecting the licenses of Three.js and Tailwind CSS.
