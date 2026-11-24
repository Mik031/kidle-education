Kidla – Early Learning School Website
A responsive educational website showcasing a modern school platform, with dedicated sections for learning programmes, teachers, tuition plans, parent testimonials, FAQs, and school news.


1. Project Description
Kidla is a frontend website concept for an early-learning educational institution. It provides parents and visitors with an organized way to explore the school's programmes, teaching team, educational approach, tuition options, and other important information.
The project focuses on building a visually engaging and responsive user interface using fundamental HTML5 and CSS3 technologies.
Key Features
* Homepage and Navigation: Educational introduction with navigation links and contact information.
* About Section: Introduces the school's educational philosophy and environment.
* Educational Services: Displays four learning programmes.
* School Statistics: Highlights experience, groups, qualified teachers, and enrolled students.
* Why Choose Us: Presents educational benefits and school advantages.
* Parent Testimonials: Displays feedback from parents.
* Teacher Profiles: Introduces teachers with interactive hover-based social icon effects.
* Pricing Section: Presents three tuition plans.
* FAQ Section: Displays frequently asked questions and a question input interface.
* Call to Action: Encourages visitors to join the school community.
* News and Articles: Showcases educational articles and school updates.
* Footer: Contains navigation link groups, social media icons, and a newsletter interface.
* Responsive Layout: Uses CSS media queries to adapt the layout to different screen sizes.
Technology Stack
Technology	Purpose
HTML5	Website structure and content
CSS3	Styling, layout, animations, and responsive design
CSS Grid	Multi-column content layouts
CSS Flexbox	Navigation, alignment, and component layouts
CSS Media Queries	Responsive layouts for different screen sizes
Google Fonts	Typography using Doto and Solway
External CDN Assets	Images, icons, and decorative SVG graphics
High-Level Architecture
This project follows a simple static frontend architecture.
Kidla Website
│
├── Frontend
│   ├── index.html
│   │   └── Website structure and content
│   │
│   └── style.css
│       └── Styling and responsive layouts
│
├── Local Assets
│   └── images/
│       └── img.png
│
└── External Resources
    ├── Google Fonts
    └── Websiteflow CDN images and SVG assets
Architecture overview:
Layer	Implementation
Frontend	HTML5 and CSS3
Backend	Not implemented
Database	Not implemented
External APIs	Not implemented
External Resources	Google Fonts and CDN-hosted visual assets
Notable Technical Decisions
* Semantic separation of concerns: HTML handles content structure while CSS manages presentation.
* Reusable styling: CSS classes and custom properties help maintain consistent visual styles.
* Responsive design: Breakpoints at 1024px, 768px, and 425px adjust layouts for different viewport sizes.
* CSS Grid and Flexbox: Different layout techniques are used according to the requirements of each section.
* Lightweight architecture: A static frontend avoids unnecessary backend dependencies and build tools.

2. Installation Guide
Prerequisites
You only need:
* A modern web browser (Google Chrome, Firefox, Safari, or Edge).
* A code editor (Visual Studio Code recommended).
* Git (optional, for repository management).
No additional installation is required.
This project does not currently use Node.js, npm, PHP, Laravel, a database, or a backend framework.
Step 1: Clone the Repository
git clone (https://github.com/Mik031/kidle-education)
Navigate into the project directory:
cd "Html-Css Project"
Step 2: Verify the Project Structure
Ensure your project contains the following files:
Html-Css Project/
│
├── index.html
├── style.css
│
└── images/
    └── img.png
Step 3: Check the CSS Connection
The HTML file already references the external stylesheet:
<link rel="stylesheet" href="style.css">
Make sure index.html and style.css remain in the same directory.
Step 4: Launch the Website
Open index.html directly in your preferred web browser.
Alternatively, open the project folder in Visual Studio Code and open index.html in your browser.
Environment Configuration
No .env file or environment variables are required.
Configuration	Status
Environment variables	Not applicable
Backend configuration	Not applicable
Database credentials	Not applicable
API keys	Not applicable
Database Setup and Migrations
Not applicable.
The current implementation is a static frontend project and does not include database integration, database schemas, or migration files.

3. Usage
Starting the Application
1. Open the project directory.
2. Locate index.html.
3. Open the file in a web browser.
4. Navigate through the different website sections.
Core User Workflows
User Workflow	Description
Explore the homepage	View the school's introduction and main navigation.
Learn about the school	Explore the about section and educational philosophy.
Browse programmes	Review the four educational service cards.
View teachers	Explore teacher profiles and hover over cards to reveal social icons.
Compare tuition plans	Review the three displayed pricing options.
Read FAQs	Browse common questions from parents and guardians.
Explore school news	View educational articles and updates.
Access contact interfaces	View the question and newsletter input fields.
Responsive Behaviour
The website uses three CSS media-query breakpoints.
Screen Width	Responsive Behaviour
Above 1024px	Desktop layout
1024px and below	Adjusted spacing and grid layouts
768px and below	Mobile navigation presentation, stacked sections, and adjusted content grids
425px and below	Single-column layouts and simplified visual elements
Example UI Workflow
Open Website
     |
     v
View Homepage
     |
     v
Explore Educational Programmes
     |
     v
View Teacher Profiles
     |
     v
Compare Tuition Plans
     |
     v
Read FAQs and School News
     |
     v
Explore Contact and Newsletter Interfaces
API Examples
Not applicable. The current repository does not contain backend endpoints or API integrations.
Implementation note: The FAQ question fields and newsletter input are currently frontend UI elements. Form submission, email delivery, and data persistence are not implemented.

4. Contributing
Contributions and suggestions for improving the website are welcome.
Development Workflow
The following workflow is a proposed contribution convention; the repository does not currently define formal contribution rules.
1. Fork the repository
Create your own copy of the project.
2. Create a feature branch
git checkout -b feature/your-feature-name
3. Make your changes
Follow the existing project structure:
* Use HTML for content and structure.
* Use CSS for styling and responsive layouts.
* Keep reusable styles organized.
* Test changes across desktop and mobile screen sizes.
4. Commit your changes
Recommended commit message format:
git add .
git commit -m "feat: improve responsive homepage layout"
Suggested commit prefixes:
Prefix	Purpose
feat	New features
fix	Bug fixes
style	CSS and visual improvements
refactor	Code structure improvements
docs	Documentation changes
5. Push your branch
git push origin feature/your-feature-name
6. Submit a Pull Request
* Provide a clear PR title and description.
* Explain the changes made.
* Include screenshots for UI changes.
* Verify desktop and mobile layouts.
* Request a review before merging.

5. Future Improvements
Potential improvements for future development include:
* Implement functional mobile navigation.
* Add interactive FAQ expand-and-collapse functionality.
* Connect the contact form to a backend service.
* Implement newsletter subscription functionality.
* Add dedicated pages for educational programmes and teacher profiles.
* Improve accessibility and keyboard navigation.
* Optimize image assets and loading performance.
* Add automated frontend testing.
These are proposed enhancements, not existing features.

6. Contact Information
Author: [TODO: Your Name]
Contact	Information
Email	minkhant1572@gmail.com
GitHub	https://github.com/Mik031
7. Project Status
Current Status: Frontend implementation
The current version demonstrates foundational frontend development skills, including responsive web design, CSS Grid, Flexbox, custom properties, hover interactions, and CSS animations.
Backend integration, database functionality, and automated testing are not included in the current repository.

7. Kidla – Early Learning School Website

A responsive educational website showcasing a modern
school platform for parents and students.

Live Demo -- https://kidle-education.vercel.app/

Built with HTML5 and CSS3.
