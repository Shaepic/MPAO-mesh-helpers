Usage-
Simply import these meshes into your 3D scene.
Position them in areas where natural occlusive shadowing is to be expected, adjusting extents, angles, intensity and color to suit.

Notes:
The meshes are packaged with thier corresponding 3-stop gradient textures and are meant to be blend-shaded with the reverse-subtract blending method.
To use the regular subtract blend method(may be less precise in some engines), simply invert the textures in a photo editor. Note it is also possible shade the meshes with a simple sdf function that
recreates the same gradient, illiminating the need to sample a texture.

It may be useful (or interesting) in some stylised cases to map the extents to the horizontal coordinates of a light source or the average of multiple sources. In fact, they can be mapped to a fake source
to give the faint impression of a real light source. 
