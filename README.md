# Music-Evolved
A music visualizer was made using Blender with a few nodes and baked noise.
# Instructions
Here are the steps to making your own visualizer
1.![image](https://github.com/user-attachments/assets/f482ad0a-ec93-4eb0-b947-5276c31e821a)

Create a basic plane and box

2. Go into edit mode with the plane selected and subdivide the mesh until you get a large number of squares.
The more subdivisions, the more detailed the final render will be. I chose to do 30 subdivisions.
![image](https://github.com/user-attachments/assets/d71ccde4-d67c-4895-9bed-f199da54b382)

Also, increase height and decrease x and y size, then bevel the cube slightly in edit mode so that the cubes look a little more realistic.
![image](https://github.com/user-attachments/assets/2a872f89-e4dc-44ce-a0a8-dcd8447f5e9c)

4. Go into geometry nodes and create the following layout: 
![image](https://github.com/user-attachments/assets/70606bab-2bf0-4ada-b6b7-9fb2878abdf2)

5. In the object info node, add the cube.
Essentially, the nodes place an object at each point in the mesh, allowing for a grid-like layout
You can also control the length and width of cubes using the combine xyz node, while the z node is going to get the input from the noise texture because it will need to be animated.
As for the noise texture, it will displace the cubes.
6. (Optional) If you choose to, you may change the w value in the modifiers tab of the plane, which will change the seed of the noise texture, but I recommend you set it to 0 for the best result.
7. Now you have to animate the plane. Click the animate button for scale:
![image](https://github.com/user-attachments/assets/16a43ded-55b9-4d44-b096-f8bc692e2b62)

And change your timeline to the graph editor and go to channel, then sound to samples, and choose the audio track that you want to use.
![image](https://github.com/user-attachments/assets/9dbd9e67-5817-4a0a-b94f-d02abd53e245)

8. Go to the video editor and add your soundtrack and press play that's it!
![image](https://github.com/user-attachments/assets/104d0f07-a66f-4fcb-b3e5-78c705499db8)

Make sure to change the frames so that it includes the entire song.
