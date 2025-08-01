Resume Builder - Progressive Web App
An offline-first, installable Progressive Web App (PWA) for building professional resumes. Built with vanilla HTML, CSS, and JavaScript.

Project Summary
This project is an offline-first, installable Progressive Web App (PWA) for building professional resumes. It guides the user through a logical, multi-step process, from selecting their experience level to choosing a template and filling out their details. The app is highly customizable, allowing users to reorder, remove, and create custom sections. It leverages the browser's local storage to save all user data privately on their device.

Advanced features like AI-powered content generation, a cover letter builder, and multi-format exporting (PDF) make it a powerful and complete tool for job seekers.

The entire application is built using vanilla JavaScript (plain HTML, CSS, and JavaScript) along with the Bootstrap library for styling. It's a single-page application that works by showing and hiding different sections of the HTML, but it doesn't use a JavaScript framework like React, Angular, or Vue.

Tech Stack
Core Language: HTML5 and JavaScript (ES6) for structure and functionality.

Styling: CSS3 and the Bootstrap 5 framework for a responsive, modern UI.

Fonts & Icons: Google Fonts for typography and Bootstrap Icons for iconography.

Data Storage: Browser Local Storage is used to save user and resume data, making the app work offline.

Exporting:

html2pdf.js library for generating and downloading resumes as PDF files.

html-to-docx.js library for generating and downloading resumes as DOCX files.

Project Components & Features
This is a comprehensive, single-page web application with a multi-step, component-based structure:

Login & Dashboard
Local-Only Login: A simple system that personalizes the user experience by saving their name to local storage.

Main Dashboard: Acts as the central hub, displaying all saved resumes and cover letters and allowing the user to start a new resume.

Guided Resume Creation Flow
Experience Level Choice: Asks if the user is a "Fresher" or "Experienced" to tailor the editor sections.

Dynamic Editor: A powerful form for entering all resume details.

Conditional Template Selection: Intelligently shows different template options based on whether the user has uploaded a photo.

Final Preview Page: A dedicated screen to view the finished resume and make final style adjustments.

Customizable Editor Features
Dynamic Sections: Users can add or remove multiple entries for work experience, education, projects, etc.

Section Reordering: Users can move entire sections up or down to customize the resume's layout.

Section Removal: Any section can be deleted entirely.

Custom Sections: Users can create their own sections with custom titles.

Advanced Features
Live Template Switching: On the preview page, users can switch between different professional templates and see the result instantly.

Accent Color Picker: Users can choose an accent color to personalize their chosen template.

AI-Powered Assistance (Gemini API):

Auto-generates professional summaries.

Enhances work and project descriptions.

Resume Management: Users can save, edit, duplicate, and delete multiple resumes.

Cover Letter Builder: A separate editor for creating and saving cover letters.

How to Install and Run Locally
This is a static web application. No complex build steps are required.

Clone the repository:

git clone https://github.com/your-username/resume-builder.git

Navigate to the project directory:

cd resume-builder

Open index.html in your browser:

You can simply double-click the index.html file.

For the best experience (to avoid any CORS issues with local files), use a simple live server. If you use VS Code, the Live Server extension is a great option.

License
This project is licensed under the MIT License. See the LICENSE file for details.
