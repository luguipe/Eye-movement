# Eye Movement Animation

## Overview
This project creates a simple eye movement animation using HTML, CSS, and JavaScript. The animation features a pair of eyes that follow the movement of the user's cursor on the screen.

## Files
- `index.html`: Contains the HTML structure for the eyes.
- `styles.css`: Includes the styling for the eyes and the overall page layout.
- `eyes.js`: JavaScript file responsible for the eye movement functionality.

## HTML Structure
The `index.html` file defines the structure of the eyes. It consists of a div with the class `eyes`, which contains two divs with the class `eye`, each having a nested div with the class `ball`. These represent the eyeballs.

## CSS Styling
The `styles.css` file provides styles for the eyes. The `.eye` class styles the eye containers, and the `.ball` class styles the eyeballs. The page background and positioning of the eyes are also defined here.

## JavaScript Functionality
The `eyes.js` script controls the movement of the eyeballs. It calculates the position of the user's cursor relative to the window and moves the eyeballs (`ball` class elements) accordingly.

## How to Run
1. Place all files (`index.html`, `styles.css`, `eyes.js`) in the same directory.
2. Open `index.html` in a web browser.
3. Move the cursor around the screen to see the eyes follow its movement.

## Features
- Responsive eye movement based on cursor position.
- Simple and clean UI design.
- Pure JavaScript implementation without any external libraries.

## Browser Compatibility
This animation should be compatible with most modern web browsers.

## Contributing
Contributions to enhance the animation or improve compatibility are welcome. Please ensure to maintain the simplicity and functionality of the project.
