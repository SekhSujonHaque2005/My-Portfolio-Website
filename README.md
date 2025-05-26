# My-Portfolio-Website


Sekh Sujon Haque Portfolio Website
Overview
This portfolio website showcases the skills, projects, and achievements of Sekh Sujon Haque, a B.Tech CSE student at Lovely Professional University. With a cosmic-themed, futuristic design, it features interactive elements, multilingual support, and a responsive layout. Built using HTML, CSS (Tailwind CSS), and JavaScript, the website highlights expertise in Python, AI/ML, Arduino, Firebase, and more, with projects like the AI-Powered Agricultural Robot.
Features

Cosmic Design: Immersive starfield background using Three.js and glowing hover effects for a futuristic aesthetic.
Responsive Layout: Fully optimized for desktop, tablet, and mobile devices.
Multilingual Support: Language dropdown with translations (e.g., English, Hindi, Punjabi) for global accessibility.
Interactive Elements: Smooth scrolling, 3D card effects for project showcases, and animated transitions using GSAP.
Contact Form: Integrated with Web3Forms for secure, serverless form submissions.
Sections:
Home: Introduction with a dynamic hero section.
About: Details on skills, education, and experience.
Projects: Showcases like AI-Powered Agricultural Robot with detailed documentation.
Contact: Form and social media links.



Tech Stack

Frontend: HTML, CSS (Tailwind CSS), JavaScript
Libraries: Three.js (starfield), GSAP (animations), Web3Forms (contact form)
Fonts: Exo, Noto Sans (supports multiple scripts like Devanagari, Gurmukhi)
Tools: VS Code, Git, Firebase (for project data integration)

Prerequisites

Node.js (v16 or higher) for local development (optional, for Tailwind CSS compilation).
Web Browser: Chrome, Firefox, or any modern browser.
Internet Connection: For CDN-hosted libraries (Tailwind CSS, Three.js) and Web3Forms API.

Setup Instructions

Clone the Repository:git clone https://github.com/your-username/sujon-portfolio.git
cd sujon-portfolio

Install Dependencies (if using local Tailwind CSS):npm install

Configure Tailwind CSS (if not using CDN):
Create a tailwind.config.js:module.exports = {
  content: ["./*.html"],
  theme: { extend: {} },
  plugins: [],
};


Compile CSS:npx tailwindcss -i ./input.css -o ./output.css --watch

Update Web3Forms API Key:
Sign up at Web3Forms to get an API key.
Replace the placeholder key in index.html:<input type="hidden" name="access_key" value="YOUR_ACCESS_KEY">

Run Locally:
Open index.html in a browser, or use a local server:npx live-server

Customize Content:
Update translations object in index.html for additional languages.
Modify project details in the Projects section.
Add your social media links in the Contact section.

Usage:

Navigation: Use the top navigation bar to access Home, About, Projects, and Contact sections.
Language Switch: Select a language from the dropdown to view content in English, Hindi, Punjabi, or other supported languages.
Contact Form: Fill out the form to send inquiries directly to the portfolio owner’s email via Web3Forms.
Project Exploration: Click on project cards to view detailed documentation, such as the AI-Powered Agricultural Robot.

Contributing:
Contributions are welcome! To contribute:

Fork the repository.
Create a feature branch (git checkout -b feature/new-feature).
Commit changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature/new-feature).
Open a Pull Request.

License:
This project is licensed under the MIT License. See the LICENSE file for details.
Acknowledgments

Tailwind CSS: For rapid, responsive styling.
Three.js: For the cosmic starfield background.
Web3Forms: For serverless contact form integration.
Lovely Professional University: For supporting project development.

Contact:
For inquiries, reach out via the portfolio’s contact form or email at [sksujonhaque@gmail.com]. Follow on LinkedIn or GitHub.
