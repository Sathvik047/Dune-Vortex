# Dune-Vortex


**Overview**
This project is basically me creating a 3D interactive dune skybox using Three.js out of boredom where the camera is positioned to provide a first-person perspective, and users can interactively navigate the scene using the mouse or touchpad. This is pretty much a simulation of distant backgrounds in 3D environments, creating the illusion of a large environment surrounding the scene.




**Tech Stack**

Three.js: Used this JavaScript library for 3D graphics and WebGL rendering.
OrbitControls: A helper class in Three.js that allows easy camera control, enabling the user to orbit, pan, and zoom around the scene.



**Notes**
This skybox uses six images (arid_ft.jpg, arid_bk.jpg, arid_up.jpg, arid_dn.jpg, arid_rt.jpg, arid_lf.jpg) to create a seamless background illusion.(You can replicate this model by choosing various textures from https://opengameart.org/content/skiingpenguins-skybox-pack)
The camera's position, as well as the minimum and maximum distances that the user can zoom in and out, are configured in the init() function.
Feel free to explore the code in script.js to see how the I set up the skybox.
