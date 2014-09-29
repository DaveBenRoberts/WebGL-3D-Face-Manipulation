WebGL-3D-Face-Manipulation
==========================

re-creation of the Super Mario 64 Face Stretching aspect of the start screen in WebGL (utilizing three.js)

I'm currently working on a fun side project where I'm hoping to replicate the stretching and posing of Super Mario's face in the Super Mario 64 Start Screen.

Example of Super Mario 64 Face Stretching:
http://www.youtube.com/watch?v=3CfGQoSKePM

In this project, I need to implement face-picking via ray-casting, send the derived clicking point in world-space, along with the 2D vector defined by the mouse-drag to the vertex-shader as uniforms. In the vertex-shader, I need to check the world-position of the vertex against the clicked world-space point, and translate the vertex by the 2D drag-vector in camera space.


I'm looking to create another Cartoon Face (Our Schools Mascot) and have users find this as an easter egg on the schools website.

I've got the Viewer set up, with the model in .js format. Its displaying, but I'm looking for a way to allow the users to select a vertices and drag them to stretch the model.

Hi DaveBenRoberts, 

I too had this same idea. I want to re-create the SM64 face on the web. Provider a character and be able to manipulate its face just like Super Mario 64. Was just wondering if you ever got anywhere with the idea. I couldn't find another way to contact you so I'm submitting a pull-request. mikeamos@gmail.com 
