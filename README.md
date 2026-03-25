# picture-frame
Little site using threejs and manifoldCAD to make watertight picture frames. Drag to add shapes. Hold ctrl for orbit controls.

I started by trying traditonal 3d-scultping methods, pushing verticies around but this ultimately didn't work as well as I wanted and created lots of manifold problems.

Instead, this works by generating offset curves from the users cursor path, extruded down a certain thickness to define a new shape which is added to the frame using boolean operations. This makes the meshes retain their quality over time.

<img width="684" height="787" alt="image" src="https://github.com/user-attachments/assets/7cd2104a-863a-483e-b27b-b0cda6d28c1b" />


<img width="1604" height="1640" alt="image" src="https://github.com/user-attachments/assets/7ed153c4-dfb6-4566-8cce-37fb1c32195f" />




[Demo](https://youtu.be/aUw_yOV74YE)

[Pages](https://github.com/iwg-mk1/picture-frame)
