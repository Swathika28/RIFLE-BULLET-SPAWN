
EXP 04 - RIFLE-BULLET SPAWN
AIM:
To Attach Rifle with character mesh and implementation bullet spawn from Rifle.

PROCEDURE:
Import the character mesh and rifle model into your game engine or development environment. Ensure that both assets are properly rigged and prepared for animation.

Create an attachment point on the character's hand or shoulder where the rifle will be attached. This can be achieved by adding a socket or bone to the character's skeleton.

Attach the rifle model to the character's attachment point using the appropriate parenting or socketing mechanism provided by your game engine. This will ensure that the rifle follows the character's movements and animations correctly.

Implement the logic for bullet spawning. You'll need to determine the position and direction from which the bullets should be spawned based on the rifle's barrel. Usually, this involves creating a spawn point on the rifle model, such as the barrel tip.

When the player triggers the shooting action (e.g., pressing a button or clicking the mouse), instantiate a bullet object at the spawn point you determined in the previous step. The bullet object should have its own movement and collision logic.

Set the initial velocity and direction of the bullet based on the rifle's orientation and any additional factors you want to consider, such as recoil or spread.

Continue updating the bullet's position and check for collisions or other interactions until it reaches its target or goes out of bounds. Handle any necessary effects or damage calculations upon collision.

Repeat the bullet spawning process as needed whenever the player triggers the shooting action.

TO IMPLEMENT SCORE WEIGHT:
Create a score variable: Declare a variable to keep track of the player's score. For example, you can initialize it to zero at the beginning of the game.

Detect bullet-object collision: Implement a collision detection system to detect when a bullet collides with an object. This can vary depending on the game engine or framework you are using. Typically, you would check for collisions between the bullet and the object using their respective collision shapes or bounding boxes.

Handle collision events: When a collision between a bullet and an object is detected, trigger a collision event or callback function. This function will be responsible for handling the specific actions associated with the collision.

Increase the score: Inside the collision event function, increment the score variable by a certain amount. For example, you can add one point to the score every time a bullet hits an object.

Update the score widget: After increasing the score, update the score widget to display the updated score value. This can be done by accessing the score widget element or object and setting its text or value to the updated score variable.

Display the score widget: Ensure that the score widget is visible to the player during gameplay. This might involve placing it in a prominent position on the screen or integrating it into the game's user interface (UI) system.

Repeat the process: Repeat steps 2 to 6 for each object that the player can interact with or shoot at. Whenever a bullet collides with an object, increase the score and update the score widget accordingly.

Optional: Add visual and audio feedback: To enhance the player's experience, you can consider adding visual and audio feedback when a bullet hits an object. For example, you might display a particle effect or play a sound effect to signify a successful hit

OUTPUT:
GUN:
242312096-0fcba2f8-52e4-4374-b59f-2165846c6858

GUNACTOR:
242315601-2bd0f7c5-b0cc-46e6-9cd4-96dffc0b4045

BULLETACTOR:
242315843-2c8fa646-257d-4acc-bb12-5fdb8bc2e590

BLUEPRINTS FOR GUN SPAWN AND BULLET SPAWN:
242316260-8ac82ecb-bb16-4e9f-b647-699af419325c

242316671-7a70f0e3-b7d1-4d02-b9ec-830d515f822f

242317352-47c681db-cf9b-46da-ac01-113aae3ca8c7

242317619-4ac62e9c-cc77-468c-a363-2d32422ec77c

RESULT: To Attach Rifle with character mesh and implementation bullet spawn from Rifle is implemented successfully
