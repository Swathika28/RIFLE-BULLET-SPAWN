
# EXP 04 - RIFLE-BULLET SPAWN
[09:20, 6/1/2023] Harsha Daughter No. 2❤️: # EXP 04 - RIFLE-BULLET SPAWN

## AIM:

To Attach Rifle with character mesh and implementation bullet spawn from Rifle.

## PROCEDURE:

1. Import the character mesh and rifle model into your game engine or development environment. Ensure that both assets are properly rigged and prepared for animation.

2. Create an attachment point on the character's hand or shoulder where the rifle will be attached. This can be achieved by adding a socket or bone to the character's skeleton.

3. Attach the rifle model to the character's attachment point using the appropriate parenting or socketing mechanism provided by your game engine. This will ensure that the rifle follows the character's movements and animations correctly.

4. Implement the logic for bullet spawning. Yo…
[10:16, 6/1/2023] Harsha Daughter No. 2❤️: # EXP 01 - EFFECTS IN UNREAL

###### NAME: AASHIMA NAZREEN SAYEED S
###### REG NO: 212221240002 

## AIM:

To Implement various effects in a material such as emissive, roughness, and metallic properties in Unreal Engine.

## PROCEDURE:

1. Right-click in the content browser and choose material.  Rename the material and double-click to open it.

2. Right-click in the working space and search for constants. In constant choose constant vector 

3. After this double click on the constant vector 4 and edit the colour using the colour
picker.

4. After adjusting the colour click okay and save it.

5. They join the output of the constant vector 4 to the base colour.

6. Create a single constant using step 3 and adjust its value of it using detail panel by
adjusting…
[10:16, 6/1/2023] Harsha Daughter No. 2❤️: # EXP 02 - PAWN MOVEMENT

###### NAME: AASHIMA NAZREEN SAYEED S
###### REG NO: 212221240002 

## AIM:
To Create a player movement using pawn, collectible, player health, and score.

## PROCEDURE:

### To create and destroy the coin:

1. Create a new project in Unreal Engine and choose a template that suits your needs.

2. Add a new actor to the level and call it "Coin".

3. Create a new blueprint based on the Coin actor by selecting it in the Content Browser and choosing "Create Blueprint".

4. Open the Coin blueprint and add a static mesh component to represent the coin. You can import a 3D model or use one of the default shapes provided by Unreal Engine.

5. Add a collision component to the Coin blueprint so that the player can interact with it. Choose a simple collision shape like a sphere or a box.

6.  Add a variable to the Coin blueprint to keep track of whether the coin has been collected or not. Call it "IsCollected" and set its default value to false.

7.  Create a new blueprint based on the player character by selecting it in the Content Browser and choosing "Create Blueprint".

8. Open the player blueprint and add a collision component to represent the player's interaction with the coins.

9. Add an event to the player blueprint that gets triggered when the player collides with a coin. Use a collision event and check if the collided actor is a coin.

10. If the collided actor is a coin, check if it has already been collected. If not, set its IsCollected variable to true and add its value to a score variable in the player blueprint.

11. Remove the coin from the level by calling its Destroy function.

12. Add several instances of the Coin actor to the level and adjusttheir positions so that they are spread out and not too close to each other.

## OUTPUT:

### Starting position of the player:
![image](https://github.com/Aashima02/Pawn-Movement/assets/93427086/a07560f0-ad0e-4812-a6e8-80049c24d89f)

### Destroying the coins:
![image](https://github.com/Aashima02/Pawn-Movement/assets/93427086/a3dc2dc5-4aa5-4499-84d7-35246add6266)

### After destroying all the coins, the score and health bars get updated:
![image](https://github.com/Aashima02/Pawn-Movement/assets/93427086/e7b6f849-a07b-46f2-bec6-bee5b0cefc64)

## PROCEDURE:

### To redirect to levels:

1. Create a new level or open an existing one.

2.  Add a new widget blueprint by going to the Content Browser and right-clicking in the desired folder. Select User Interface and then Widget Blueprint.

3. Design your menu by adding buttons and other UI elements to the widget. You can use images, text, and other widgets to create a visually appealing menu.

4. Add a button to your menu by dragging and dropping a Button widget from the Palette onto your canvas.

5. In the Button's properties, scroll down to the On Click section and click the + button next to the On Click event.

6. Create a new custom event by clicking the New Binding button and selecting Custom Event.

7. Name the custom event "LoadScene" or something similar.

8.  Open the Level Blueprint by going to the Blueprint menu and selecting Open Level Blueprint.

9. Drag and drop your menu widget from the Content Browser into the Level Blueprint.

10. Create a new variable in the Level Blueprint by clicking the Add Variable button in the My Blueprint panel. Name the variable "MenuWidget" or something similar and set its type to the widget blueprint you created earlier.

11. In the Level Blueprint, drag from the MenuWidget variable and select Set to set the variable's value to the instance of the menu widget you added to the level.

12. Create a new function in the Level Blueprint by clicking the Add Function button in the My Blueprint panel. Name the function "LoadScene" or something similar.

13. Drag from the MenuWidget variable and select Get to get the instance of the menu widget.

14. Drag from the Get node and select Remove From Parent to remove the menu widget from the screen.

15. Drag from the LoadScene custom event and select Open Level to open the desired level or scene.

16. Connect the nodes in the LoadScene function as follows: LoadScene -> Remove From Parent -> Open Level.

17. Go back to your menu widget and select the button you added Earlier.

18. In the Button's properties, scroll down to the On Click section and select the LoadScene custom event you created earlier.

19. Save your changes and playtest your game. When the player clicks on the button in the menu, the menu widget will be removed and the desired level or scene will be loaded.

## CONNECTIONS:

### Play Button:
![image](https://github.com/Aashima02/Pawn-Movement/assets/93427086/f9abbce1-d07f-4486-a7f4-7b174e5fe11c)

### Quit Button:
![image](https://github.com/Aashima02/Pawn-Movement/assets/93427086/d1572e81-d8ba-4e29-8927-517e30dcd69f)

### Back Button:
![image](https://github.com/Aashima02/Pawn-Movement/assets/93427086/1fe733d1-d506-4d1d-a338-87dcea1f6193)

## RESULT:

Thus, To Create a player movement using pawn, collectible, player health, and score created and developed by unreal Engine.
