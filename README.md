Features
HTML Structure:

The document is structured with a <!DOCTYPE html> declaration and includes essential elements such as <head>, <meta>, and <link> for styling.
The body contains a div with the class container, housing another div with the class wheel.
The wheel has six lines and six cabins positioned to form a complete Ferris wheel.
CSS Styling:

Wheel Design:
The .wheel class styles the Ferris wheel with a border, rounded edges, and dimensions that adapt to the viewport size while maintaining a maximum size.
The wheel has an infinite rotation animation (@keyframes wheel) with a duration of 10 seconds, creating a continuous spinning effect.
Background:
The body uses a background image (Wonderland.jpg) that covers the entire viewport without repeating.
Container:
The .container class centers the wheel horizontally and adds a top margin to position it correctly on the page.
Lines:
The .line class creates the spokes of the wheel, positioned absolutely and rotated to form a hexagonal pattern.
Cabins:
The .cabin class styles the cabins with a red background, absolute positioning, and dimensions relative to the wheel.
The cabins rotate in the opposite direction of the wheel to maintain their upright position using the @keyframes cabins animation, and change colors throughout the rotation cycle.
Animations
Wheel Rotation:

Defined using the @keyframes wheel animation, the wheel rotates from 0 to 360 degrees over 10 seconds, repeating infinitely.
Cabin Rotation and Color Change:

The @keyframes cabins animation rotates each cabin in the opposite direction of the wheel (from 0 to -360 degrees) to keep them upright.
The cabins change their background color through a spectrum of colors (red, orange, yellow, green, blue, indigo, violet) at different keyframes during the rotation cycle.
Usage
To view and interact with this animated Ferris wheel:

HTML File: Create an HTML file and insert the provided HTML structure.
CSS File: Create a CSS file named styles.css and add the provided CSS code.
Background Image: Ensure the image Wonderland.jpg is in the same directory or update the CSS to point to the correct path.
Open in Browser: Open the HTML file in a web browser to see the animated Ferris wheel in action.
Conclusion
This project combines HTML and CSS to create a dynamic and visually appealing Ferris wheel animation. The use of CSS animations for both the wheel and cabins adds an engaging element to the webpage, making it a fun and interactive design.
