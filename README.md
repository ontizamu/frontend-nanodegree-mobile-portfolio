## Website Optimization portfolio project

In this project, the online portfolio website was optimized to achieve a PageSpeed score of 90 and to run at 60 frames per second.

To run the optimized website you need to open the index.html file. 

### Optimizations performed

####Part 1: Optimizations to achieve a PageSpeed score of 90. 
Changes done to index.html.

* Optimized two images: procfilepic.jpg and pizzeria.jpg
* Inline the complete style.css file
* Make analytics script asynchronous
* Add media query for print.css
* Don't include the web fonts

####Part 2: Optimizations to run at 60 frames per second. 
Changes done to views/main.js and views/css/style.css.

* Create number of animating pizzas dinamically, based on the screen size.
* Use variables instead of accesing the DOM many times.
* Declare variables outside the loops.
* Force each moving pizza to have its own composite layer.
* Use document.getElementsByClassName or document.getElementById instead of document.querySelectorAll().

