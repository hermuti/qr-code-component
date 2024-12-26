### Frontend Mentor - QR Code Component Solution

This is my solution for the Frontend Mentor - QR Code Component coding challenge. It focuses on building a fully responsive and pixel-perfect component based on the given design.

### Table of Contents

Overview
Links
Built With
What I Learned
Continued Development
Useful Resources
Author

### Overview

### The Challenge

The goal was to replicate a QR Code component based on the given design. It involved:

Implementing a responsive card component that adapts to different screen sizes.
Matching the design as closely as possible using semantic HTML and CSS.
Building a mobile-first layout and optimizing for desktop.

### Links

Solution URL: Add solution URL here
Live Site URL: Add live site URL here

### Built With

Semantic HTML5 markup
CSS custom properties
Flexbox for layout
Media queries for responsiveness
Mobile-first workflow

### What I Learned

This challenge helped me reinforce key concepts in responsive web design and component structure. Here are a few key takeaways:

Mobile-First Workflow: Starting with mobile ensured I created a streamlined experience for smaller devices before scaling up for desktops.

Flexbox Mastery: I used justify-content and align-items to perfectly center the QR code component within the page.

Example:

css

.qr {
justify-content: center;
width: 100%;
max-width: 300px;
border-radius: 10px;
}

page Responsiveness: Ensured the QR code resized fluidly with the layout using @media and max-width property.

css
@media (min-width: 1440px) {
body {
padding: 50px;
}
.card {
max-width: 400px;
padding: 30px;
}
.qr {
max-width: 350px;
}
.text {
font-size: 22px;

}
.tect {
font-size: 16px;
}
}

### Continued Development

Moving forward, I want to:

Explore CSS Grid for more complex layouts.
Practice integrating reusable components in larger projects.

### Useful Resources

geeks for geeks and google
MDN Web Docs - Flexbox Guide: Helped me refine my understanding of flexbox.
Frontend Mentor Challenges: An amazing platform to practice real-world projects and improve coding skills.

### Author

Website - hermella
Frontend Mentor - @hermuti
Twitter - @hemutiwo
