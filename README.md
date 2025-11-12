Habit Tracker App for school project.

https://github.com/Narri5/project-1
https://project-1-habit-tracker.onrender.com

Build Status

This project uses a Continuous Integration/Continuous Deployment (CI/CD) pipeline implemented with GitHub Actions, or at least try to use.

CI Status (Linting & Security):
![CI Workflow Status]
[![CI](https://github.com/Narri5/project-1/actions/workflows/ci.yml/badge.svg)](https://github.com/Narri5/project-1/actions/workflows/ci.yml)

Project Overview

This is a single-page application built using vanilla HTML, CSS, and JavaScript. It serves as a simple habit tracker that allows users to add habits, mark daily progress, view the last seven days of activity, and track a live streak count.

Key Features:

Data Persistence: Uses the browser's localStorage to save habit data between sessions.

Technology: Plain HTML, CSS, and JavaScript (No frameworks or external libraries).

Focus: Practicing core DOM manipulation, event handling, and date management.

The CI/CD Pipeline (DevOps/DevSecOps)

The automation pipeline for this project is built using GitHub Actions and is triggered automatically on every push to the main branch.

The pipeline performs three key functions:

Continuous Integration (CI): It sets up the Node.js environment and executes two critical quality checks:

Code Quality (ESLint): Ensures app.js adheres to specified JavaScript coding standards.

Security Audit (npm Audit): Scans project dependencies for high or critical vulnerabilities.

HTML Validation (htmlhint): Checks index.html for structural and accessibility issues.

Continuous Deployment (CD): After the CI checks successfully pass, the entire static project is automatically deployed to GitHub Pages, making the latest working version instantly available online.

Clone the repository:

git clone [https://github.com/Narri5/habit-tracker.git]

Open index.html in your web browser.

Stretch Goals (Completed)

[Completed] CI/CD Pipeline: Implemented CI for linting and security, and CD to GitHub Pages.

[Completed] HTML Validation: Added htmlhint check to the CI pipeline to validate index.html.

[Completed] Branch Protection: Enabled. I might break something whit this.
<img width="1920" height="1160" alt="Näyttökuva 2025-11-12 180003" src="https://github.com/user-attachments/assets/8fecf96c-6b56-4272-8459-74b85dac4535" />

[Completed] Lighthouse CI: This generated few repports.
<img width="859" height="1040" alt="Näyttökuva 2025-11-12 175111" src="https://github.com/user-attachments/assets/ed6153c6-2e53-4482-805f-4ce8add76c16" />
<img width="859" height="1040" alt="Näyttökuva 2025-11-12 175651" src="https://github.com/user-attachments/assets/b33a87cc-7348-407a-998c-e0dd638b30d5" />
