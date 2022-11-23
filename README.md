# POV_WebGL_Movement

In this activity, we need to modify the given project to add movement to the pawn through the controller. The rotation of the movement is specified by the orientation of the camera. We just have to add the keys corresponding to going forward or backwards.

For this, we need to modify the file /Shared/Controller.razor.cs, changing a few lines of code corresponding to the functions keydownEvent and keyupEvent. These changes can be seen in the images below.

![asd](/Img/keydownEvent.png)

![asd](/Img/keyupEvent.png)

To go backwards, we simply go in the opposite direction of the forward vector, inverting this value. We reset the values of the movement vector to zero once we stop pressing the movement keys.

![asd](/Img/gif.gif)
