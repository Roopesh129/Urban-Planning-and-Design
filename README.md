# Urban-Planning-and-Design
🌆 Sustainable City Challenge – Project Overview
This project is a full-stack web app that allows users to submit ideas for sustainable urban planning. It's clean, interactive, and stores user input on the backend using Python and Flask.

🔍 Key Features
1. 🌿 Frontend: Beautiful and Responsive Design
A homepage explaining the challenge.

A form where users enter their name, email, and sustainable idea.

A gallery of inspirational city design images.

Includes CSS effects: hover transitions, shadows, rounded cards.

2. ✨ Interactivity with JavaScript
Form submission feedback with alert().

Scroll-to-top button appears after scrolling down.

Lightbox gallery: Click images to see a larger preview in a modal.

3. 🧠 Backend with Flask (Python)
Receives form submissions via a POST route (/submit)

Validates that all fields are filled.

Stores entries in a CSV file: submissions/ideas.csv

Uses flash() to provide user feedback on submission success/failure.

4. 🗃️ Data Storage (CSV Format)
Easy to use and portable.

Each form entry is appended as a new row.
