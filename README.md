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
- Largest of 3 and Odd_Even


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

$~~~~~~~~~~~$

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

$~~~~~~~~~~~$

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

$~~~~~~~~~~~$

##  Form Validation

This repository contains a simple HTML form for student registration with JavaScript-based client-side validation. The purpose of this code is to validate user inputs before submitting the form to ensure data integrity and accuracy.

### Getting Started

To use the registration form and validation script, follow these steps:

1. Clone the repository to your local machine or download the `main.html` and `right.html` files directly.

2. Open the `main.html` file in a web browser.

3. Fill out the registration form, and the validation script will check each field for correctness based on defined criteria.

4. If all fields pass validation, the form will be submitted to the `right.html` page, indicating a successful registration.

## Form Fields and Validation Criteria

The registration form consists of the following fields, each with its own validation criteria:

- **First Name:** Should contain at least 6 alphabetic characters.
- **Last Name:** Should contain only alphabetic characters.
- **Email Address:** Should be a valid email format (e.g., `user@example.com`).
- **Password:** Should contain at least 6 alphanumeric characters.
- **Address:** A mandatory text area for entering the user's address.
- **Mobile No:** Should contain exactly 10 numeric digits.
- **Gender:** Choose between male and female.

### Validation Functions

The validation script utilizes various JavaScript functions to validate form inputs. Here are the functions used:

- `notEmpty(elem, helperMsg)`: Checks if the input element is not empty.
- `isNumeric(elem, helperMsg)`: Validates if the input consists of only numeric digits.
- `isAlphabet(elem, helperMsg)`: Validates if the input consists of only alphabetic characters.
- `isAlphanumeric(elem, helperMsg)`: Validates if the input consists of only alphanumeric characters.
- `lengthRestriction(elem, min)`: Checks if the input meets a minimum length requirement.
- `emailValidator(elem, helperMsg)`: Validates if the input is a valid email address.
- `lengthRestriction1(elem, min, max)`: Checks if the input has a specific length range.

### Usage

The `formvalidator ()` function is called when the form is submitted. It sequentially validates each input field according to the defined criteria. If all validations pass, the form is submitted; otherwise, an alert message is displayed, and the focus is set on the first incorrect input.

$~~~~~~~~~~~$

## Canvas

This repository contains a simple HTML file demonstrating how to create a canvas element and implement basic drawing functionality using JavaScript. Users can click and drag the mouse on the canvas to draw lines.

### Getting Started

To run this example, simply open the `canvas.html` file in a web browser that supports HTML5 and JavaScript.

### Prerequisites

You only need a modern web browser to run this example. No additional installations are required.

### Usage

1. Open the `canvas.html` file in a web browser.
2. Click and hold the mouse button on the canvas.
3. Drag the mouse around to draw lines.
4. Release the mouse button to stop drawing.

###  Code Description

The HTML file `canvas.html` contains a canvas element and JavaScript code to handle the drawing functionality. The canvas is initialized with a width and height of 400 pixels each. The JavaScript code inside the `<script>` tag handles the mouse events and drawing operations.

The functions included are:
- `startDrawing(event)`: Initiates drawing when the mouse button is pressed.
- `drawLine(event)`: Draws lines as the mouse is moved while holding the button.
- `stopDrawing(event)`: Stops drawing when the mouse button is released.

$~~~~~~~~~~~$

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
                                 
$~~~~~~~~~~~$

## jQuery - Fade In, Fade Out, Fade Toggle

This repository provides examples and explanations for using jQuery to implement fade-in, fade-out, and toggle effects. These effects can enhance your web applications' visual appeal and user experience by smoothly transitioning elements on and off the screen.

### Fade In Effect
The fade in effect gradually increases the opacity of an element, making it visible in a smooth and elegant manner. To achieve this effect using jQuery, you can use the fadeIn() method.
### Fade Out Effect
The fade-out effect gradually decreases the opacity of an element, making it disappear from the screen in a subtle way. To apply the fade-out effect using jQuery, you can use the fadeOut() method.
### Toggle Effect
The toggle effect combines both the fade-in and fade-out effects into a single action. If an element is visible, the toggle effect will fade it out, and if it's hidden, the toggle effect will fade it in. This creates a seamless show/hide experience. To implement the toggle effect using jQuery, you can use the fadeToggle() method.

$~~~~~~~~~~~$

## Largest_of_3.

### Description:
This HTML file contains a simple JavaScript program that takes three numbers as input and determines the largest among them. It uses basic conditional statements to compare the numbers and display the largest one to the user.

### Usage:
1. Open the `Largest_of_3.html` file in a web browser.
2. The browser will display three prompts asking you to enter three numbers.
3. After entering the numbers, the browser will show an alert indicating the largest number among the three.

### Example:
- If you enter `5`, `12`, and `8`, the alert will display: "The largest number is: 12"

## odd_even.

### Description:
This HTML file contains a simple JavaScript program that determines whether a given number is even or odd. It takes a number as input and uses the modulo operator to check its divisibility by 2. If the number is divisible by 2, it is considered even; otherwise, it is considered odd.

### Usage:
1. Open the `odd_even.html` file in a web browser.
2. The browser will display a prompt asking you to enter a number.
3. After entering the number, the browser will show an alert indicating whether the number is "Even" or "Odd".

### Example:
- If you enter `7`, the alert will display: "Odd"
- If you enter `12`, the alert will display: "Even"
- If you enter a non-numeric input, the alert will display: "Invalid input. Please enter a valid number."


<div align="center">
<b>THE END  </b>
</div>






