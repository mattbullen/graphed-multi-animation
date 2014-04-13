## Random Animation With Delta Graphs

##### LIVE DEMO: http://bullen.io/graphed-multi-animation/demo.html

This demo is an earlier version of my [spline animation demo](https://github.com/mattbullen/3D-spline-animation). It animates a small SVG-injected box around the screen by tweening the CSS properties margin-top and margin-left to random values. Each tween gets a radomly selected tweening pattern: plain old linear intervals up to multi-point splines.

At the end of the animation, the demo loads two simple graphs for each CSS property. Each graph shows a visual for the delta intervals of the tween.

Just for kicks, click on the animated box to change its background color, or reload the page for a new, random one. If you download the file and tinker with the Javascript, you can get this demo to tween and graph any other CSS properties you might feel like trying out.

