# Spline Path Animation

This is an earlier version of my [3D spline animation](https://github.com/mattbullen/3D-spline-animation) page. It animates a small SVG icon around the screen by tweening the CSS properties `margin-top` and `margin-left` to random values. Each property takes a randomly selected tweening pattern: plain linear intervals up to multi-knot splines.

At the end of the animation, the page loads a  line graph for each CSS property. Each graph shows the delta intervals of its corresponding tween, which is useful for matching more complex splines to the movement of the icon along its path.

##### Try it out: http://bullen.io/spline-path-animation/demo.html
