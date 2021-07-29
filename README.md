# WebGL Fluid Simulation

This project demonstrates a simple WebGL fluid simulation in a web app. The
ultimate goal of this project is to have this used in Webflow, but this also
works as a standalone static site.

This is adapted from https://github.com/PavelDoGreat/WebGL-Fluid-Simulation, but
I modified a good chunk of the code to be more clean, have less promos, and have
better web coding standards.

## How to use this code for your Webflow site

1. Create a new Webflow project
2. In custom code, add the following to your header
   ```html
   <script type="text/javascript" src="https://mikinty.github.io/webgl-fluid-simulation/dat.gui.min.js"></script>
   <link rel="stylesheet" href="https://mikinty.github.io/webgl-fluid-simulation/style.css">
   ```
3. In custom code, add the following to your footer
   ```html
   <canvas></canvas>
   <script src="https://mikinty.github.io/webgl-fluid-simulation/script.js"></script>
   ```
4. For the steps above, it is up to you how you want to reference the script,
   css and `dat.gui.min.js` files. You can either host them on Webflow and use them
   there, or use the files from this Github directly.


## How this works

This project is classic example of using Javascript ahd HTML together. In HTML,
we just create a simple `canvas` element, and in the Javascript code, we code a
bunch of logic that controls how the `canvas` will behave.

In terms of Webflow, we are just providing pointers to files that we want
embedded into our site.
