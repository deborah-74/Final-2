## Santa's Little Helper

Alternate Realities project by Amina and Debbie!

### Background

This Christmas, Santa is overwhelmed because he has so many presents to deliver and you are the only elf available to help him make preparations. You have three main tasks to complete in Santa’s magical factory!

- Put presents on the conveyor belt
- Put presents into Santa’s sack
- Use the candy cane key to start the engine for Santa’s sleigh

### Interaction Descriptions

- Sorting presents in the factory (ray interaction)
Taking presents from treadmill and into boxes

- Putting boxes in sleigh (direct + ray)
 Picking up the boxes and placing them in the sleigh
 
 - Starting the Santa Engine (direct)
 Take the key and place it into the right place
 
 - Teleportation inside the room (ray + direct)
 Moving around the environment

### Process

1) Firstly, we needed to decide a method to use to design the environment, since no external assets were allowed. We came up with the idea of using cubes as ‘pixels’ to design the objects in the scene. Our inspiration was minecraft

![](https://github.com/deborah-74/Santa-s-Little-Helper/blob/gh-pages/Screenshot%202021-10-06%20at%2000.31.06.png)


2) Secondly, (after adding an XR rig) we started designing the environment! Creating the christmas tree was the first asset on the list, as this would be important for the story going forward. This was made by stacking up a bunch of cubes. The great thing with this method was that everything could be done within unity, using the colours provided in the platform





3) The sleigh was also an important part of the story, so we used this same method to create a custom sleigh that would fly off at the end of the game.



4) Santa’s Candy Cane key



5) The next step was to create the interactables in the scene, which are the following: boxes/ presents using cubes/cylinders to create a desirable shape; santa’s sack/box; conveyor belt



6) Next, we needed to start adding both ray and direct interactions to the scene

7) Lifting the box onto the conveyer belt: both ray and direct interaction enabled with the attachment point in the bottom of the object. Simple script is written to track the position using onTriggerEnter and play sound after completing the task.
Putting wrapped presents in Santa’s bag: both ray and direct interaction enabled with the attachment point in the bottom of the object. The code is the advancement from the first interaction script, which now includes a counter and has the same sound effect that plays after completing the task.
Turning on the sleigh: direct interaction. The script utilizes all of the interaction concepts mentioned above as well as the lerp animation. Lerp is used to, first, turn the key 90 degrees and, second, make the sleigh slowly take off from the scene with a Happy Santa sound effect, indicating the end of the game.

### Additional contributors to the scene

- A large white plane to give the illusion of snow
- A custom skybox that fits the ‘minecraft’ theme
- Large white area light to imitate the blinding white of a factory
- Christmas colours: red, white and green
- Christmas theme sounds including background music

### Challenges

- Creating the assets was quite time-consuming and required a lot of brain power getting the design correct
- Setting up Unity collaborate was also very difficult and we experienced several problems. So we just ended up working separately on our laptops on different parts of the project and combining our scenes later
- Setting up the lerp animation with the key was also quite difficult

### What we learnt

Overall, we had a lot of fun creating our project and the main thing we learnt was how to create a storyline in unity without relying heavily on external assets and aesthetics. We mainly focused on using animations and interactions to build the environment and to create a storyline that makes sense.
