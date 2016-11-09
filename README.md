## Website Performance Optimization portfolio project

### Project Instructions:

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

To get started, check out the repository and inspect the code.

### Getting started

####Part 1: Optimize PageSpeed Insights score for index.html

* Pushed site to [github pages](https://jonathandwood.github.io/pagespeed-testing/)
* Optimised all images using tinyjpg.com
* CSS minified with https://cssminifier.com/
* Added permatters.js inline in script tags


####Part 2: Optimize Frames per Second in pizza.html

* Added new variables to prevent recalculations in updatePositions function on line 504 and changed items to use getElementsByClassName
* Added variable pizzas, using getElementsByClassName and numberOfPizzas in function changePizzaSizes
* Changed windowWidth variable to use getElementById rather than queryselector in determineDx
* Keeping it DRY and using getElementById in changeSliderLabel function
* added movingpizzas variable in document.addEventListener at end of file, also changed number of pizzas to 18 rather than 200 in for loop as that is the max on the screen at a given time

You might find the FPS Counter/HUD Display useful in Chrome developer tools described here: [Chrome Dev Tools tips-and-tricks](https://developer.chrome.com/devtools/docs/tips-and-tricks).
