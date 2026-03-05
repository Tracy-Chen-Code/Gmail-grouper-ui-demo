⚡ Smart Gmail Grouper - UI Demo

This is a demo project showcasing the pure front-end UI interaction of the Smart Gmail Grouper Chrome extension.

This project simulates the basic Gmail inbox interface and fully replicates the front-end effects after the extension is injected into the Gmail page, including the "floating button", "sidebar interaction", "AI grouping suggestion display", and "quick actions (archive, mark as read, undo)".

🌐 Live Demo
(If you have deployed this to GitHub Pages, insert your link here)

✨ Features

🎨 Mock Gmail Interface: Uses pure HTML/CSS to simulate Gmail's left navigation bar and right email list, providing an immersive presentation context.

🖱️ Smooth Sidebar Interaction: A fixed "Group Inbox" button at the bottom right of the screen that smoothly slides out the AI smart grouping sidebar when clicked.

🤖 AI Analysis Simulation: Simulates the loading process of calling a backend LLM for email sender analysis, and displays AI grouping suggestions (e.g., Ads, Subscriptions, Important, etc.) along with the reasoning.

⚡ Quick Actions & Animations: Supports simulated clicks on buttons like "Archive All" and "Mark Read", complete with smooth card removal animations.

↩️ Undo Function: A prompt pops up at the bottom after an action is taken, supporting a one-click restoration of the just-removed card.

📦 Zero Dependencies: Written in pure Vanilla JS + HTML + CSS. The single file can be run directly without needing any build tools (Webpack/Vite) or front-end frameworks (React/Vue).

🚀 How to Run

This is a pure static front-end project and is extremely simple to run:

Download or save the index.html file to your computer.

Double-click the index.html file, and it will automatically open in your default browser (such as Chrome, Edge, or Safari).

Click the "⚡ Group Inbox" button in the bottom right corner of the page to start experiencing it.

🛠️ Project Structure

For maximum convenience in demonstration and deployment, this project adopts a Single-File Architecture:

📦 gmail-grouper-ui-demo
 ┣ 📜 index.html    # Contains all HTML structure, CSS styles, and interactive JavaScript logic
 ┗ 📜 README.md     # Project documentation


Secondary Development Guide

If you want to further develop based on this UI (for example, transforming it into a real Chrome extension), you can:

Extract the Extension UI CSS from the <style> tag into a separate content.css file.

Extract the logic from the <script> tag into a content.js file.

Replace the mocked mockData with real Gmail API calls (such as gapi.client.gmail.users.messages.list).

License
MIT License
