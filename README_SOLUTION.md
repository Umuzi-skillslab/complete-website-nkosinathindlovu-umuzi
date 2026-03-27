# Portfolio Debug & Completion Capstone

## Project Overview
I was tasked with taking an incomplete and "broken" portfolio starter kit and turning it into a professional, fully functional website. This project required me to audit the code for 41 intentional errors, implement HTML5 semantic standards, and create a clean, responsive design using CSS.

## Issues Identified & Fixed
I performed a full audit of the provided files and identified over 15 major issues (out of the 41 total). Some of the key fixes included:
* **HTML Validation:** Added missing `<!DOCTYPE html>` and `<html>` tags across all pages to meet W3C standards.
* **Semantic Layout:** Converted non-semantic `div` containers into proper `<header>`, `<nav>`, `<main>`, and `<footer>` elements.
* **Navigation Logic:** Built a consistent navigation menu for all 4 pages, which was entirely missing in the starter code.
* **Accessibility:** Assigned descriptive `alt` text to all images and corrected the color contrast in the hero section to ensure readability.
* **Form Completion:** Expanded the contact form from a basic layout to a validated version with 5+ input types (text, email, select, checkbox, and textarea).
* **Data Presentation:** Created a structured `<table>` with `<thead>` and `<tbody>` on the About page to display technical skills.

## Technical Implementation
The styling was kept clean and entry-level to ensure the code remains maintainable:
* **Box Model:** I used a mix of padding, margins, and borders to create a balanced layout.
* **CSS Selectors:** I utilized 5+ selector types, including Element, Class, ID, Descendant, and Pseudo-classes (`:hover` and `:nth-child`).
* **Organization:** All styles are housed in a dedicated `css/` directory, and images are organized in an `images/` folder.

## Folder Structure
* `index.html`, `about.html`, `projects.html`, `contact.html` - Main pages.
* `/css/styles.css` - Custom stylesheet.
* `/images/` - Site assets and project screenshots.
* `/design/` - Sitemap and Wireframe PDFs.

## How to View
1. Clone the repository to your local computer.
2. Open the project folder.
3. Double-click `index.html` to open the site in your preferred browser.

## Reflection
This project taught me how to identify bugs in existing code and the importance of semantic HTML for accessibility. The hardest part was fixing the alignment issues in the CSS, but using the browser's developer tools helped me visualize the Box Model and get the spacing exactly right.
