# GAME_PROGRAM-EX--3
## Aim
To replace the default third person character mesh with a custom skeletal mesh and apply new animations using an animation blueprint.
## Procedure
Import New Character Mesh and Animations:

In the Content Browser, import a new Skeletal Mesh along with its Animations (FBX files). Ensure the mesh is rigged correctly (ideally to the UE4 Mannequin Skeleton or compatible with it). Replace Character Mesh:

Open the ThirdPersonCharacter Blueprint (usually found in ThirdPersonBP/Blueprints). Select the Mesh component. In the Details Panel, change the Skeletal Mesh to the newly imported mesh. Set Animation Blueprint:

If available, assign a matching Animation Blueprint in the Details Panel under the Animation section. If not available, create one: Right-click in the Content Browser → Animation → Animation Blueprint. Choose the correct skeleton. In the AnimGraph, set up state machines or direct animation nodes. Compile and save. Preview and Test:

Place the character in the level. Press Play to test idle, walk, and run animations based on character movement.

## OUTPUT
<img width="1043" height="635" alt="image" src="https://github.com/user-attachments/assets/87e93ba0-9281-47e7-bb24-ff0fe9206fbc" />
<img width="1046" height="602" alt="image" src="https://github.com/user-attachments/assets/b6e5ae7c-bba5-474f-9b9c-2c03435f1381" />
<img width="715" height="613" alt="image" src="https://github.com/user-attachments/assets/51c4c326-769b-45eb-ba94-61e4a1299d67" />

## Result

Thus the replacement of the default third person character mesh with a custom skeletal mesh and apply new animations using an animation blueprint was executed sucessfully.
