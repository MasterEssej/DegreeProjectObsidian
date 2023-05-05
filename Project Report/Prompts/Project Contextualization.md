
I will now provide you with the information and context of my own project and you will gather said information and construct a context and undertstanding of the project until i am satisfied with your understanding of my project
1. I will start with a General Description of my Game Project.
Description ( **

I’ve made a 2D game where the player is able to switch between Top-Down mode and Side-Scroller mode. The player is able rotate 90 degrees to change the orientation of the Top-Down view and can at a push of a button switch to a Side-Scroller view based on where the player is rotated and how the player is rotated. 

  

The world is built using TileMaps along the XZ axes stacked on top of each other along the Y direction. When switching from Top-Down mode to Side-Scroller mode, all Tiles along the player's relative X axis on all TileMaps will be read and then set on a TileMap along the XY axis that will position itself on the player. This means that the player will stay in the same position in the world regardless of the current mode. The active camera will be switched to a camera displaying the Side-Scroller view.

  

The player's movement and collision is handled in 3D. All tiles are RuleTiles that have GameObjects with 3D BoxColliders attached to them. This also lets me add functionality that otherwise would not be available with normal tiles, such as adding scripts to the GameObjects for each tile.

** )
   
2. You will ask me Relevant follow-up Questions about my project and its components. Execution, difficulties, implementation. etc. 
   
3. we will repeat number 2 until i am satisfied with your understanding of the project.
   





1. I was inspired by thoughts of the fourth dimension and the thought of different dimensions and different perspectives on reality.

2. The primary goal for the player is to make it through levels with puzzles and locked doors by changing perspectives to navigate and move around.

3. The transition between the two modes is instant. The player simply presses F and the change happens. The active camera changes and the relevant tiles will be set on the TileMap for the Side-Scroller mode. The players movement will change to only move along the correct axes. The biggest challenge with this was getting the tiles and the TileMap itself to be positioned correctly regardless of rotation.

4. I used Unity and C#. I did not have any problems with these specifically.

5. A RuleTile can have a GameObject attached to it. By attaching a BoxCollider to a RuleTile, every such tile I place will then automatically have a 3D BoxCollider attached to it. This is not possible using normal tiles, as they can only handle collisions in 2D. I can also add custom scripts to them and then have custom functionality for certain tiles. I had never used RuleTiles before but learning how to use them was not very challenging.

6. My biggest challenge during this project was staying focused and motivated. I had a very hard time with that and as such the majority of my time was spent daydreaming instead of working.