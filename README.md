Brian Makini Portfolio
Overview
This project is a personal portfolio website built for a Power Learn Academy assignment, using only vanilla HTML and CSS. It showcases my skills as a teacher and aspiring front-end developer, focusing on creating accessible, responsive web interfaces for educational purposes. The portfolio leverages CSS animations and transitions to create a dynamic, modern design without JavaScript or PHP.
Features

Responsive Navigation: A sticky navbar with “BM” initials on mobile (≤768px), a white hamburger menu icon, and a centered “Get in Touch” button, optimized for accessibility and responsiveness.
Hero Section: Features a profile image, CSS-only typing animation cycling through “Teacher & Developer”, “Education Innovator”, and “Self-Taught Coder”, and social links (GitHub, LinkedIn, Email).
About Section: Describes my background as a teacher and self-taught HTML/CSS developer, passionate about educational web design.
Skills Section: Displays proficiency in HTML5 and CSS3 with animated progress bars, styled using CSS.
Education Section: Lists my Bachelor of Education Arts (2021–2025) and ongoing software engineering course.
Resume Section: Uses a CSS-only accordion (via <input type="checkbox">) to display work experience (Web Developer Intern, Freelance UI/UX Designer, DOS Assistant).
Interests Section: Highlights my passion for EdTech, open-source web projects, and collaboration.
Projects Section: Showcases three static prototypes (Elimudigital, Task Manager, Personal Portfolio), built with HTML and CSS, with links to code and live demos.
Contact Section: Includes a static form prototype (no submission functionality) with enhanced CSS animations and contact information (email, phone, location).
Floating Buttons: WhatsApp and Back-to-Top buttons with CSS hover effects for quick navigation.
Footer: Contains navigation links and a copyright notice.
CSS Animations: Includes a typing effect, floating particles, scroll-down indicator, and hover transitions, all implemented with pure CSS.

Technologies Used

HTML5: Provides semantic, accessible structure for the portfolio’s content.
CSS3: Handles styling with custom properties, gradients, media queries, and animations (e.g., typing effect, particles, accordion toggles, hover transitions).
External Resources:
Placeholder images via via.placeholder.com.
SVG icons for social links, contact info, and navigation, embedded via CSS background.



Setup Instructions
To view or test this portfolio locally, follow these steps:
Prerequisites

A modern web browser (e.g., Chrome, Firefox, Safari).
A code editor (e.g., VS Code) for viewing or editing files.
Git (optional, for cloning the repository).

Installation

Clone or Download the Repository:

Clone: git clone https://github.com/lykerclassy/portfolio.git (replace with your repository URL).
Or download the ZIP file and extract it.


Add Assets:

Place your profile image (profile.jpeg), background image (banner-bg.png), and resume PDF (cv.pdf) in the assets/ folder.
Update project image URLs in the Projects section if using custom images instead of placeholders.


Run the Project:

Open index.html in a web browser (e.g., double-click the file or use VS Code’s Live Server).
No server is required, as the project uses only static HTML and CSS.



Deployment

GitHub Pages:
Push the project to a GitHub repository.
Enable GitHub Pages in the repository settings, selecting the main branch and / (root) folder.
Access the site at https://lykerclassy.github.io/portfolio.


Other Hosting:
Upload index.html, styles.css, and the assets/ folder to any static hosting service (e.g., Netlify, Vercel).
Ensure asset paths (assets/profile.jpeg, etc.) are correct relative to the server root.



Usage

Navigation: Use the navbar links or hamburger menu (on mobile) to jump to sections (About, Skills, Education, Resume, Interests, Projects, Contact).
Typing Animation: View the CSS-driven typing effect in the Hero section, cycling through three phrases every 12 seconds.
Resume: Click accordion labels to expand/collapse work experience details using CSS-only toggles.
Projects: Hover over project cards to view details (via CSS opacity transition) and click links to explore code or live demos.
Contact: View contact information (email, phone, location); the form is a static prototype with animated focus/hover effects but does not submit data.
Social Links: Use footer or hero section links to visit my GitHub, LinkedIn, or send an email.
WhatsApp: Click the floating WhatsApp button to start a chat at +254791567689.

Testing

Responsiveness:
Test on small screens (≤768px) to confirm:
“BM” initials are visible in the logo (white with purple-blue gradient, z-index: 1002).
Hamburger menu and “X” icon are white (#F1F5F9, z-index: 1003).
“Get in Touch” button is centered without overlapping the logo or menu.


Resize the browser or use developer tools to simulate mobile devices.


Animations:
Verify the typing animation cycles through three phrases with a blinking cursor.
Check CSS-driven effects (particles, scroll-down indicator, hover transitions, accordion) render smoothly.


Accessibility:
Test aria-label, role, and tabindex attributes with screen readers (e.g., NVDA, VoiceOver).
Ensure keyboard navigation (Tab, Enter) toggles the accordion and navigates links.


Assets and Icons:
Confirm images (assets/profile.jpeg, assets/banner-bg.png, assets/cv.pdf) load correctly.
Verify all icons (GitHub, LinkedIn, Email, Phone, Location, WhatsApp, Back to Top, Menu) display properly.



Project Structure
portfolio/
├── assets/
│   ├── profile.jpeg        # Profile image
│   ├── banner-bg.png       # Hero section background
│   ├── cv.pdf              # Resume PDF
├── index.html              # Main portfolio page
├── styles.css              # Stylesheet
└── README.md               # This file

Known Issues

Asset Paths: If images or the resume PDF don’t load, verify paths in assets/ match your hosting setup.
Browser Compatibility: Older browsers may not support CSS gradients or animations. The fallback color: #F1F5F9 ensures “BM” logo visibility.
Form: The contact form is a static prototype and does not submit data, as required by the HTML/CSS-only constraint.
Typing Animation: In some browsers, the CSS typing animation may clip long phrases on small screens; ensure phrases are concise.

Future Improvements

Add more CSS animations (e.g., fade-in effects for sections).
Enhance the typing animation with additional phrases or styles.
Improve accessibility with more ARIA attributes or high-contrast modes.
Replace placeholder images with custom project screenshots.

Contact
For questions or feedback, reach out via:

Email: kanewalker483@gmail.com
WhatsApp: +254 791 567 689
GitHub: github.com/lykerclassy
LinkedIn: linkedin.com/in/kane-walker-0b715b218

Acknowledgments

Power Learn Academy for the assignment and training in HTML and CSS.
Placeholder images from via.placeholder.com.
"# plp-projects-2025-july-cohort-hackathon" 
"# plp-projects-2025-july-cohort-hackathon" 
