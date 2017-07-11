# Web Optimization Project

## Steps to optimize

### 1. Optimizing index.html
* Minimized and inlined the entire style.css file into index.html header.
* Added a "Print" media query for the print.css file.
* Added async to the google analytics script.
* Used the web font loader to asynchronously load the google font.
* Optimized the pizzeria thumbnal.

### 2. Optimizing pizza.html
* Modified 2 of the Javascript loops in main.js
	* Moved many of the static variables in changePizzaSizes outside of the loop to avoid unnecessary calculations
	* Did the same with the updatePositions function. Isolated static variables.
	* In the DOMContentLoaded eventlistener, created a rows variable and multiplied it by the columns so that we create only the necessary amount of movingpizzas
* Inlined style.css into the HTML header
* Reduced the size of the pizzeria image

You can view the project at https://yelrow.github.io/Web-Optimization-Project/index.html

You can view the optimized pizzeria page at https://yelrow.github.io/Web-Optimization-Project/views/pizza.html

