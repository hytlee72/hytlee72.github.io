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

Sources used for research:
http://creativejs.com/resources/requestanimationframe/
https://developer.mozilla.org/en-uS/docs/Web/API/window/requestAnimationFrame
http://www.w3.org/TR/animation-timing/#requestAnimationFrame
https://www.igvita.com/
https://developer.chrome.com/devtools/docs/demos/too-much-layout
https://developers.google.com/web/fundamentals/look-and-feel/animations/animations-and-performance?hl=en
http://www.html5rocks.com/en/tutorials/speed/high-performance-animations/
http://www.html5rocks.com/en/tutorials/speed/animations/