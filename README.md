# jfan0714_Quiz-8

# tracking missiles

## Part 1
This idea is inspired by the shooting aircraft games I played during childhood, where homing missiles could automatically track targets and continuously adjust their movement paths in real time. In my project, I would like to apply this target-seeking visual effect by having large numbers of triangles move from all directions toward the mouse position and disappear upon contact, creating an explosion-like visual feedback. As the mouse moves, all triangles dynamically change their trajectories to continue following the target. I believe this interactive motion can create a strong sense of movement, visual direction, and immersion within the artwork.
[Missile Inspiration](images/images.jpeg)
[Missile Inspiration](images/dS99qP.png)

## Part 2
For the coding technique, I researched particle systems and target-seeking movement in p5.js. This technique can create smooth and dynamic motion by allowing multiple triangles to continuously move toward the mouse position in real time. It is useful for producing the missile-tracking visual effect that I want to achieve in my project. Most of the example code I found is very similar to my idea, but in those examples the triangles appear from the mouse position. In my project, I would modify the behaviour so that the mouse position becomes the point where the triangles disappear instead.
[Example Code](https://p5js.org/examples/classes-and-objects-flocking/)
[Screenshot](images/screenshot.png)