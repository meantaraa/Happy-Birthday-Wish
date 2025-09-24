# Happy Birthday Wish

## Overview

This is a simple yet elegant web application designed to send a personalized birthday wish. It features a beautiful firework and balloon animation, creating a visually appealing and interactive greeting. The application is built with vanilla JavaScript, HTML, and CSS.

## Features

-   **Dynamic Text Animation**: The birthday message is animated as a sequence of fireworks that explode to reveal the letters.
-   **Interactive Balloon Release**: After the firework display, the letters are attached to balloons that float up and off the screen.
-   **Responsive Design**: The animation adapts to different screen sizes, ensuring a consistent experience across devices.
-   **Customizable**: The birthday message and various animation parameters can be easily customized in the `app.js` file.

## Technologies Used

-   **HTML5**: The structure of the web page is built using HTML5, with a `<canvas>` element for the animation.
-   **CSS3**: The application is styled with CSS3, which is used to create a full-screen canvas and style the text.
-   **JavaScript (ES6)**: All the animation logic is written in vanilla JavaScript, leveraging the HTML5 Canvas API for rendering.

## Setup and Usage

To run this project locally, follow these steps:

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/happy-birthday-wish.git
    ```
2.  **Navigate to the project directory**:
    ```bash
    cd happy-birthday-wish
    ```
3.  **Open `index.html` in your web browser**:
    You can simply open the `index.html` file in your preferred web browser to see the animation in action.

## Customization

You can customize the birthday message by editing the `opts.strings` array in the `app.js` file.

```javascript
// app.js

var opts = {
    strings: [ 'HAPPY', 'BIRTHDAY!', 'Your-Name' ], // Customize the message here
    // ... other options
};
```

You can also tweak other animation parameters in the `opts` object to change the look and feel of the animation.