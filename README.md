## Delta-Graphed Random CSS Animation

##### LIVE DEMO: http://bullen.io/graphed-multi-animation/demo.html

This demo is an earlier version of my [3D spline animation](https://github.com/mattbullen/3D-spline-animation) demo. Like that demo, this one is also hand-rolled using plain, no-library Javascript.

This animates a small SVG-injected box around the screen by tweening the CSS properties `margin-top` and `margin-left` to random values. Each property takes a radomly selected tweening pattern: plain old linear intervals up to multi-point splines.

At the end of the animation, the page loads two simple line graphs for each CSS property. Each graph shows a visual for the delta intervals of its corresponding tween, which is useful for matching the more complex splines to the movement of the box around the screen.

Just for kicks, click on the animated box to change its background color, or reload the page for a new, random one. If you download the file and tinker with the Javascript, you can make this demo tween and graph any other CSS properties you might feel like trying out.

I also left some modal and JSON recording-via-AJAX code in there. It works fine, but I thought it cluttered up the presentation of what is really a very simple demo. Just remove the comment marks in the `demo.html` file and adjust accordingly, etc., to see those in action.

