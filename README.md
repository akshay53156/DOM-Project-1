# Simple DOM Manipulation Project

This project demonstrates basic DOM manipulation using vanilla JavaScript to style a `div` element dynamically. The project contains a simple HTML file and a JavaScript file that changes the appearance of a `div` by applying inline styles through JavaScript.

## Project Structure

- `index.html`: The main HTML file containing the structure of the page.
- `script.js`: The JavaScript file that manipulates the DOM by applying styles to the `div` element.

### Files Overview:

#### index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple DOM Manipulation</title>
</head>
<body>
    <div id="container">Hello, I'm a div!</div>
    <script src="./script.js"></script>
</body>
</html>

#### script.js

The `script.js` file contains the JavaScript code that manipulates the DOM by applying styles to the `div` element with the ID "container".

```javascript
let container = document.getElementById("container");

container.style.backgroundColor = "yellow";
container.style.margin = "20px";
container.style.padding = "10px";
container.style.fontSize = "18px";
container.style.fontWeight = "bold";
container.style.height = "200px";
container.style.width = "300px";
container.style.color = "blue";

How to Run the Project Locally
Clone this repository:
bash
Copy code
git clone https://github.com/akshay53156/DOM-Project-1.git
Navigate to the project directory:
bash
Copy code
cd DOM-Project-1
Open the index.html file in your browser to see the project in action.
Live Demo
You can view the live version of the project here: Live Demo

Project Functionality
A div element is dynamically styled using JavaScript.
The styles applied include background color, margin, padding, font size, and more.
The content inside the div ("Hello, I'm a div!") is made bold, enlarged, and centered within a styled box.
