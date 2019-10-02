# Threejs Example Code
This is a repo to hold basic example code of Threejs. I suspect that A-Frame is what you actually want to use to build WebXR applications but since A-Frame itself is a Threejs framework some understanding of how Threejs works might be of value.

### What is Threejs?
- A JavaScript library and API used to create and display animated 3D graphics in the browser
- It uses WebGL (if that is of interest)

### What is A-Frame?
- An entity component system for Threejs
- It's a Unity-like 3D / WebXR development tool compared to pure Threejs which is probably more like with OpenGL directly to create your application
- TLDR: It's what you probably want to use

### Note
I run threejs locally so you'll probably have to play around with the script import path. Check the threejs documentation. I avoid loading from a module for now as the intention is to provide example threejs code not necessarily best development practice. 

### Note Note
It's worth remembering when you are writing academic code that works enough to get the necessary data it doesn't have to work with the best development practices. Ask about Mark's VR keyboard study which constantly crashed and had a hard time limit of usage if you want an example of that. 

### Examples Overview:
- 01-spinning-cube: Heavily commented example to show setup of a camera, scene, renderer and display a rotating cubes
- 02-spinning-cube-2: Builds on previous example, adds lighting, two additional cubes, alters renderer code
