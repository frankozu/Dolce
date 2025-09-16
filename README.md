Features
Responsive Layout

Navigation bar adapts to different screen sizes (desktop, tablet, mobile).
Hamburger menu appears on screens under 900px.
Hero Section (Home Page)

Large background image filling the viewport.
Headline, sub-text, and a CTA button.
Flavors Page

Grid layout (7 columns on desktop, fewer columns on smaller screens).
Ice cream flavor “cards” with images, short descriptions, and hover effects.

Footer

Consistent footer at the bottom of each page.
Minimal styling, with contact or copyright info.

File Structure
dolce-ice-cream-website/
 ┣─ index.html
 ┣─ flavors.html
 ┣─ about.html
 ┣─ locations.html
 ┣─ order-online.html
 ┣─ contact.html
 ┣─ styles.css
 ┣─ script.js
 ┣─ images/
 ┗─ README.md

index.html: Home page with the hero section.
flavors.html: Displays various ice cream flavors in a grid.
about.html, locations.html, order-online.html, contact.html: Additional info pages.
styles.css: All the CSS styles, including responsive breakpoints.
script.js: JavaScript for the hamburger menu toggle and any other interactive features.
images/: Folder containing hero backgrounds, flavor images, and other graphics.
README.md: This file, describing the project and usage.

How to Use
Open Locally

Download or clone the project folder.
Double-click index.html to open it in your web browser.
Alternatively, use a local development server (e.g., Live Server in VSCode).
Navigation

In desktop view, the navigation menu is displayed across the top.
In mobile view, click the hamburger icon to open the menu.
Sub-Pages

Visit Flavors to see the flavor grid.
About, Locations, Order Online, and Contact provide additional info.

Customization
Header & Footer
Located in each HTML file for a consistent look. Adjust text or links as desired.
Hero Image
In styles.css, update .hero-section background images or sizes.
Flavors Page
Modify the .flavor-item elements in flavors.html to add, remove, or change flavors.
Adjust the grid columns in styles.css to control how many flavors appear per row.

License
This project is for an ice cream shop. You cannot adapt or reuse the code in accordance with your own licensing preferences.