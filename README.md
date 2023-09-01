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
- )ne-component-in-another(React)
- React Calculator
- jQuery (Fade)


## jQuery - Fade In, Fade Out, Fade Toggle

This repository provides examples and explanations for using jQuery to implement fade-in, fade-out, and toggle effects. These effects can enhance your web applications' visual appeal and user experience by smoothly transitioning elements on and off the screen.

### Fade In Effect
The fade in effect gradually increases the opacity of an element, making it visible in a smooth and elegant manner. To achieve this effect using jQuery, you can use the fadeIn() method.
### Fade Out Effect
The fade-out effect gradually decreases the opacity of an element, making it disappear from the screen in a subtle way. To apply the fade-out effect using jQuery, you can use the fadeOut() method.
### Toggle Effect
The toggle effect combines both the fade-in and fade-out effects into a single action. If an element is visible, the toggle effect will fade it out, and if it's hidden, the toggle effect will fade it in. This creates a seamless show/hide experience. To implement the toggle effect using jQuery, you can use the fadeToggle() method.

********************************************************************************************************

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



