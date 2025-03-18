Poor Naming Conventions:

The variable themeChangerBtn could be renamed to themeToggle for simplicity.

CSS variables like --bg-color and --text-color could be renamed to --background and --text for better readability.

Redundant Logic:

The theme toggle logic checks localStorage twice. This can be simplified by combining the logic into a single function.

Hardcoded Values:

The max-width: 300px for the form is hardcoded. Consider using relative units like em or rem for better responsiveness.
Accessibility Improvements
Form Labels:

Add aria-describedby to form inputs for additional context (e.g., "Enter your full name").

Theme Toggle Button:

Replace the emoji with a text label like "Toggle Dark Mode" for better accessibility.

Error Messages:

Use aria-live="polite" to ensure error messages are announced clearly to screen readers.

Performance Improvements
Lazy-Loading:

Add loading="lazy" to images for better initial load performance.

Minify CSS and JavaScript:
Minify style.css and script.js to reduce file size.

Reduce Unused Code:

Use the Coverage Tool to identify and remove unused CSS and JavaScript.
