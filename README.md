# Game-Engine
A Java 2D game engine!

![](/Objects.gif)

The Game Engine is able to handle 10000s of objects. In this demo 10000 objects are accelerated towards the mouse cursor.

![](/Collision.gif)

The Game Engine uses the Seperating Axis Theorum to check for collisions; this allows for hitboxs to be rotated and still allow for efficient collision caculation. To check for collisions between two hitboxes the hitboxes are projected on each vertix of both hitboxes. If a gap is found between the projected hitboxes then the objects are not colliding.


