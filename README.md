# 3D Boxes Background Animation

This project demonstrates a 3D boxes animation effect using HTML, CSS, and JavaScript. It creates a grid of 3D boxes with interactive functionality. The user can click the "Magic" button to toggle the size and rotation of the boxes.

## Project Overview

The project consists of:

- A button labeled "Magic 🎩" that triggers the animation.
- A container (`div#boxes`) which holds a 4x4 grid of boxes.
- A JavaScript function that generates the boxes dynamically and adds them to the container.
- CSS styles that define the appearance and animations of the boxes.
- When the button is clicked, the grid expands, and the boxes rotate 360 degrees.

## Files

- **index.html**: The main HTML file that contains the structure of the webpage.
- **style.css**: The stylesheet for styling the layout, the boxes, and the button.
- **script.js**: The JavaScript file that handles the creation of the boxes and the interaction (box resizing and rotation).

## Getting Started

### Prerequisites

To run this project, all you need is a browser and an internet connection to fetch the required external resources.

### Installation

1. Clone this repository or download the project files.
2. Open the `index.html` file in any modern browser.

### Usage

1. Open the webpage and click on the **Magic 🎩** button.
2. Watch the boxes expand and rotate on the screen.

### Code Explanation

- **HTML (`index.html`)**:
    - The `button` element triggers the animation.
    - The `div#boxes` element is where the dynamically generated boxes are displayed.

- **CSS (`style.css`)**:
    - **Body styles** ensure that the content is centered on the page.
    - **Magic button styles**: The button is fixed at the top of the screen and is styled for a bright, attractive appearance.
    - **Boxes styles**: Each box has a 3D-like effect using `::before` and `::after` pseudo-elements. A transition effect is added for the resizing and rotating animations.
  
- **JavaScript (`script.js`)**:
    - The `createBoxes()` function generates a 4x4 grid of boxes. The `backgroundPosition` is set to create a seamless background across all boxes.
    - The `btn.addEventListener()` toggles the `big` class on the `boxes` container when the button is clicked, triggering the animation defined in the CSS.

### Features

- **Responsive design**: The layout adjusts according to the viewport size, ensuring the grid remains centered.
- **Interactive animation**: Clicking the button toggles an animation that resizes and rotates the boxes.
- **Dynamic grid generation**: Boxes are created dynamically using JavaScript.

### Live Preview

You can view a live preview of the project by opening `index.html` in any modern web browser.

### External Resources

This project uses the following external resources:

- **Font Awesome** for the button icon (`🎩`).
- **Google Fonts**: 'Roboto' and 'Poppins' fonts are used in the project.

### License

This project is open-source and free to use.
