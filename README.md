## Website Performance Optimization portfolio project

###Getting Started

A node localhost server file is included.  If you have node installed run npm install on your terminal.  All needed
files should be installed.

Run node server.js.  You will be able to access the app from http://localhost:8080.

A grunt task is included that will build the css and js files used in pizza.html.  Just run "grunt" from your terminal.
Production files are created in the build folder.

###Optimizations for main.js
1.  Calculate the number of small pizzas based on screen height.
2.  Replaced pizza image with optimized png.
3.  Stored array of moving pizzas once instead of generating it within updatePositions function.
4.  Moved calculations out of for loop to beginning of updatePositions.
5.  Stored all possible values of modulus operator in an array outside of for loop.  Refer to array instead of
calculating within for loop.
6.  Only update moving pizzas if they are viewable.
7.  Run updatePositions on window resize event.
8.  Moved resizePizza functions outside of function block.
9.  Changed windowwidth to passed variable in determineDx.
10. Moved calculations outside of for loop in changePizzaSizes.
