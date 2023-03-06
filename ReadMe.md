# Rendering objects with opengl

## Introduction
this project is for rendering 3d objects in python using pyopengl and glfw
then we are going to test multi core rendering using multiprocessing and multithreading

## base of 3d rendering
3d rendering is a process of rendering 3d objects in 2d screen
we need to convert 3d objects to 2d screen
there are different concepts in 3d rendering some examples are:
1. camera
2. projection
3. view
4. model
5. world
6. light
7. shadow
8. texture

## the general steps to render a 3D object with lighting and shadows using OpenGL in Python:
1. Load the 3D object model and its texture into memory using a library such as PyOpenGL.

2. Set up the OpenGL rendering context and viewport. This includes creating an OpenGL window, specifying the projection matrix, and defining the camera position and orientation.

Define the lighting parameters, such as the light source position, intensity, and color. You can use different types of lighting models, such as diffuse, specular, and ambient lighting.

Set up the shadow mapping technique. This involves rendering the scene from the perspective of the light source and storing the depth information of the objects in a texture map.

Render the 3D object using the loaded model and texture. Apply the lighting and shadowing effects by calculating the color of each vertex based on the lighting and shadow maps.

Finally, present the rendered image to the user by swapping the back buffer with the front buffer.


