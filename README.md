# Music-Evolved
A music visualizer was made using Blender with a few nodes and baked noise.
# Instructions
Here are the steps to making your own visualizer
1.![image](https://github.com/user-attachments/assets/f482ad0a-ec93-4eb0-b947-5276c31e821a)

Create a basic plane and box

2. Go into edit mode with the plane selected and subdivide the mesh until you get a large number of squares.
The more subdivisions, the more detailed the final render will be. I chose to do 30 subdivisions.
Also, increase height and decrease x and y size, then bevel the cube slightly in edit mode so that the cubes look a little more realistic.

3. Go into geometry nodes and create the following layout: 
![image](https://github.com/user-attachments/assets/70606bab-2bf0-4ada-b6b7-9fb2878abdf2)

4. In the object info node, add the cube.
Essentially, the nodes place an object at each point in the mesh, allowing for a grid-like layout
You can also control the length and width of cubes using the combine xyz node, while the z node is going to get the input from the noise texture because it will need to be animated.
As for the noise texture, it will displace the cubes.
5. (Optional) If you choose to, you may change the w value in the modifiers tab of the plane, which will change the seed of the noise texture, but I recommend you set it to 0 for the best result.
6.
