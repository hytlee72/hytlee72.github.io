## Website Performance Optimization portfolio project

####Part 1: Optimize PageSpeed Insights score for index.html
Optimized using:
 Inline CSS
 Optimized images
 Optimized Webfonts
 Setting JS scripts to async

####Part 2: Optimize Frames per Second in pizza.html

Optimized pizza.html using basically the same steps in Part 1.

Changes to main.js
	Optimized changePizzaSizes function by:
		Removing unecessary vars from the for loop
		and calling the function using rAF

	Optimized the pizza creation for loop by:
		Removing unecessary vars from the for loop
		Wrapping the for loop in a function and
		calling the function with rAF

	Optimized the updatePositions function by:
		Removing unecessary vars from the for loop
		Debouncing the scroll events
		And using rAF to call the function