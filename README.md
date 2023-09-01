<div align="Center">
  
# Frontend-Fullstack
</div>

## Table of Contents

- ReactJS (Tribute to APJ ABDUL KALAM)
- AngulaJS (Planets)
- AJAX (Birthday)
- Javascript (Form and Form with validation)
- Canvas
- React programs
- One-component-in-another(React)
- React Calculator
- jQuery (Fade)


## A. P. J. Abdul Kalam - React App

This React app showcases a brief timeline of the life and achievements of Dr. A. P. J. Abdul Kalam, the "Missile Man of India" and the "People's President." The app displays his image, and a timeline of significant events in his life, and provides a link for further information.

## Getting Started

To run this React app, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory using your terminal.
3. Run `npm install` to install the necessary dependencies.
4. Run `npm start` to start the development server.
5. Open a web browser and go to `http://localhost:3000` to view the app.

### Prerequisites

You need Node.js and npm (Node Package Manager) installed on your machine to run this app.

### App Components:

### `App.js`

This file contains the main React component that renders the timeline of Dr. A. P. J. Abdul Kalam's life. It displays his image, name, a short description, and a chronological list of his achievements and milestones.

### `App.css`

The CSS file provides styling for the app. It includes a class `.avatar` that gives the circular border to the displayed image.



## Planets - AngularJS 

This repository contains a simple AngularJS application that displays information about planets in the solar system. The app allows users to search and sort the planets based on various criteria.

### Introduction
This AngularJS application provides an interactive interface to explore information about different planets in the solar system. Users can filter planets based on their names and sort them by name, type, distance from the Sun (in Astronomical Units), and the number of moons.

### Usage
1. Users can search for specific planets by typing their names in the search box.
2. Sorting can be done using the dropdown menu to arrange the planets based on name, type, distance, or number of moons.

### Features
- **Search**: Users can search for specific planets by entering their names in the search box.
- **Sorting**: Users can sort the planets by name, type, distance, or number of moons.
- **Table Display**: The app displays a table with columns for planet name, type, distance, and number of moons.

### Technologies
- AngularJS: A JavaScript framework that facilitates building dynamic web applications.

### Working
1. Clone the repository to your local machine.
2. Open the `index.html` file in a web browser to see the application in action.

### Note
- Make sure you have a modern web browser that supports JavaScript and AngularJS.
- This app is meant for educational purposes and serves as a basic example of an AngularJS application.
- You can modify and enhance the app's functionality or style according to your preferences.



## Birthday

This repository contains a simple web page that demonstrates the use of AJAX (Asynchronous JavaScript and XML) to display a birthday greeting message. The example consists of two HTML files: `Birthday.html` and `surprise.html`.

### Files :

### `Birthday.html`

This file is the main HTML page that provides the user interface for the birthday greeting example. It contains:

- A `<h1>` tag displaying the heading "Today's your special day!"
- A button with the text "Why's that?" that triggers the AJAX request when clicked.
- A `<div>` element with the ID `ajax-content` where the fetched content will be displayed.
- Inline JavaScript code that sets up the AJAX request using the `XMLHttpRequest` object and defines a function (`sendTheAJAX()`) to send the request.

### `surprise.html`

This file contains the surprise birthday greeting message. It includes:

- An empty `<head>` section.
- A `<h1>` tag with the ID `birthday-greeting` that contains the text "It's your birthday!".
   
### How It Works

When you click the "Why's that?" button on the main page (`Birthday.html`), the JavaScript code uses the `XMLHttpRequest` object to asynchronously fetch the content of the `surprise.html` file. Once the request is complete and the content is received, the fetched greeting message is displayed in the `ajax-content` `<div>`, replacing the button.



## React Calculator App

This repository contains a simple calculator application built using React. The app allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division on two numbers. The calculator's UI and functionality are implemented in the `app.js` file.

### Working

1. Enter the first number in the input field labelled "First Number".
2. Enter the second number in the input field labelled "Second Number".
3. Click on one of the operation buttons to perform the corresponding arithmetic operation:
   - "Add" button: Adds the two entered numbers.
   - "Subtract" button: Subtracts the second number from the first number.
   - "Multiply" button: Multiplies the two entered numbers.
   - "Divide" button: Divides the first number by the second number.
4. The result of the selected operation will be displayed below the buttons.
                                 

## jQuery - Fade In, Fade Out, Fade Toggle

This repository provides examples and explanations for using jQuery to implement fade-in, fade-out, and toggle effects. These effects can enhance your web applications' visual appeal and user experience by smoothly transitioning elements on and off the screen.

### Fade In Effect
The fade in effect gradually increases the opacity of an element, making it visible in a smooth and elegant manner. To achieve this effect using jQuery, you can use the fadeIn() method.
### Fade Out Effect
The fade-out effect gradually decreases the opacity of an element, making it disappear from the screen in a subtle way. To apply the fade-out effect using jQuery, you can use the fadeOut() method.
### Toggle Effect
The toggle effect combines both the fade-in and fade-out effects into a single action. If an element is visible, the toggle effect will fade it out, and if it's hidden, the toggle effect will fade it in. This creates a seamless show/hide experience. To implement the toggle effect using jQuery, you can use the fadeToggle() method.







