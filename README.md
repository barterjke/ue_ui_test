# Unreal Engine UI Programmer Recruitment Task
## HUD, Pause Menu and Inventory

## Notes

By reqs: "Optimal part of the solution should be programmed using C++, following best practices.". I believe that simple interactions, like variable binding, triggers and UI (anything, that doesn't include complex logic or math) can be done and should be done in Blueprints, as it feels very native to Unreal, so I decided not to use C++ code at all. 


Task
Using Third Person Template, your task is to implement three features:

1. HUD containing visual indicators of ammunition left, character condition and life.

On the player interface (HUD) there should be visual indicators of ammunition, character stamina and life.
The player should start with 30 ammo rounds, and each shot from a weapon should reduce the amount of ammunition by 1. Once all 30 rounds have been used, the player should stop being able to shoot.
On the world map there should also be a Trigger Box that lowers the life of the player. The player entering this box receives damage, and the amount of life decreases, which should visually represent the UI.
Stamina should decrease when the player holds the SHIFT button while running. When the condition bar drops to 0, the character should stop being able to run and start walking. After a while, the stamina should start to recharge and the character should be able to run again.

2. Pause menu with one submenu.

Another part of the task is the pause screen. After pressing the ESCAPE button, the game should stop. The HUD should disappear from the screen, and a menu with two buttons should appear - "BACK TO GAME" and "OPTIONS".
By clicking on the former, the menu should close, thus returning to the game.
On the other hand, clicking on the "OPTIONS" button should bring up a menu where the player will be able to change at least one parameter affecting gameplay. This can be any parameter.

3. A simple inventory system (with only one slot), that allows the player to collect and manage items (in this case, single one).

The next part of the task is to introduce into the map a key item and a door. The key should be located in a place away from the door. The player approaching the key should be able to click on it and receive the key.
The inventory menu, which will contain only one empty slot, will be able to be opened with the TAB button. At the beginning of the game, the inventory slot should be empty. After taking the key, the key should disappear from the map and appear in the inventory. The previously mentioned door should be possible to open with this key.
The player, standing next to the door, should be able to open the inventory and, using Drag-And-Drop mechanics, drag the key onto the door, thereby opening it. Once opened, the player should be able to walk through it.

You will need to create UIs and integrate them into the interaction with the game world as mentioned.

## Requirements

Use Unreal Engine version 5.1 or later.
Use the Third Person Template provided by Unreal Engine as a starting point for the gameplay programming.
All mentioned systems should be fully functional and integrated into the game.
HUD, Pause Menu and inventory menu should be visually simple and easy to use.
Optimal part of the solution should be programmed using C++, following best practices.
As an extra task, provide a brief video documentation on how to use created features.


## Deliverables

A working Unreal Engine project that includes the HUD, pause menu, inventory system and integrated gameplay.
The source code should be uploaded to the GitHub repository.
A brief documentation explaining how to use mentioned features (extra).

## Evaluation Criteria
Your submission will be evaluated based on the following criteria:

Completeness and correctness of the implementation systems.
Quality of the code and adherence to best practices.
Usability of the new UI elements.
Overall organization and structure of the project.
Clarity and completeness of the documentation (extra).

## Submission

Please submit your project as a compressed file, along with a README file containing any instructions or information the evaluator should know about your submission. You can host your project on Google Drive or any public repository.

The code should be submitted on the public GitHub repository.
