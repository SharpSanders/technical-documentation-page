# Frontend Development – Technical Documentation Page

A clean, responsive technical documentation page that explains fundamental frontend concepts including:

- HTML Basics  
- CSS Fundamentals  
- Responsive Design  
- JavaScript Essentials  
- DOM Manipulation  

This project follows the freeCodeCamp “Technical Documentation Page” user stories while using a modern, easy-to-read layout.

---

##  Overview

The page is structured with:

### 🔹 A fixed left-side navigation bar  
- Stays fixed on desktop  
- Converts to a top block on mobile  
- Links to each documentation section (`#HTML_Basics`, `#CSS_Fundamentals`, etc.)

### 🔹 A main content area  
Each section includes:
- A `<header>`
- Descriptive text
- Code examples (`<code>`)
- Concept bullet lists

### 🔹 Responsive behavior  
- Sidebar becomes full-width at mobile sizes (`max-width: 768px`)
- Main content shifts to single-column layout

---

##  Tech Stack

- **HTML** – semantic sections, anchors, code blocks  
- **CSS** – fixed sidebar, responsive layout, color palette  
- **No JavaScript needed** — the content is static and fully CSS-powered

---

##  Project Structure

```text
technical-documentation-page/
├── index.html      # Navigation + doc content
└── styles.css      # Layout, colors, typography, responsiveness
 Styling Highlights
Left navigation uses:

position: fixed

Full-height sidebar (100%)

Deep blue background #243B73

Active and hover link behavior:

Links slide right slightly using extra left padding

Hover color: soft coral #FF6B81

Main content:

Slight off-white background #f4f6fa

Increased line-height for readability

Code blocks use:

Light blue background

Monospace font

Rounded corners

 Sections Included
1. HTML Basics
Headings

Paragraphs

Links

Sample tags

2. CSS Fundamentals
Selectors

Colors

Box model

Example CSS snippets

3. Responsive Design
Media queries

Fluid images

Mobile-first approach

4. JavaScript Essentials
Console logging

Variables

Functions

Events

5. DOM Manipulation
Selecting elements

Updating text

Adding/removing classes

 Responsive Behavior
When the screen width falls under 768px:

Sidebar (#navbar) changes from fixed-left to top-floating

Main content loses margin-left and becomes full-width

Navigation links remove left padding on hover for cleaner stacking

This ensures readability and accessibility on phones/tablets.

 What I Practiced
Building a multi-section documentation layout

Fixed navigation bar with anchor links

Semantic HTML with accessible structure

Responsive CSS with media queries

Styling code blocks with readable formatting

 Future Improvements
Add smooth scrolling for nav links

Highlight active section while scrolling

Add collapsible sections for mobile

Add dark/light theme toggle

 Author
Created by Trevyn Sanders.