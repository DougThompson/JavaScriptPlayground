# Canvas Fun #

CanvasFun.html - This file has three different experiments and is written without line-terminating semi-colons just for fun.  The lack of line-terminating semi-colons looks very odd to me,; but after reading some drama about them, I thought I'd experiment.

The Experiments:

* Animated rotating squares
* Mandelbrot fractal generator
* Biomorph fractal generator

The two fractal experiments use a setTimeout function to draw the fractals in blocks, while the rotating squares uses an animation polyfill to handle the animation.

The fractals can be zoomed in by drawing a zoom-square on the canvas.  CTRL+drag will draw a square selection band to keep the aspect ratio the same as the canvas.