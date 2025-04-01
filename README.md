Group members: Fredrick Kwaleyela
               Guardian Mwenya

Page descriptions:
The website is a simple, responsive multi-page site featuring Home, Services, and Contact pages. The Home page has a hero section with a welcome message and a Flexbox layout displaying content side by side. The Services page uses CSS Grid to showcase different services in stylish cards with hover effects. The Contact page includes a user-friendly form with HTML5 validation and smooth animations for better interaction.
The navigation bar, styled with Flexbox, is shared across all pages for easy access. The design is fully responsive, adapting to different screen sizes using media queries. It also includes a responsive image, an animation using @keyframes, and hover effects for an interactive experience.

Summary of features used (selectors, Flex/Grid, media queries, animation):
 CSS Selectors
•	Used element selectors (nav, button, img) for basic styling.
•	Used class selectors (.content, .services-grid, .contact-form) for layout and styling.
•	Used pseudo-classes (:hover, :focus) for interactivity.

 Flexbox Layout
•	Used in the navigation bar (display: flex; justify-content: center;) for proper alignment.
•	Used in the Home page layout to display sections side by side.
 CSS Grid Layout
•	Used in the Services page (display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));) to arrange service cards.

 Media Queries
•	Applied at three breakpoints:
o	max-width: 1024px (for tablets)
o	max-width: 768px (for smaller tablets)
o	max-width: 480px (for mobile screens)

 Animations & Transitions
•	@keyframes animation (bounce) for button hover effects.
•	Smooth transitions on buttons and form inputs (transition: border-color 0.3s ease;).
