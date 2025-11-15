📦 Voxel World Generator (Ursina Engine)

This is a basic 3D voxel game built using the Ursina Engine in Python. It creates a simple, explorable world featuring a grass plane, randomly placed mountains, and trees. The player can walk, jump, and dynamically modify the world by placing and destroying blocks.

🚀 Features

First-Person Control: Players can move through the 3D world using standard FPS controls (W/A/S/D, mouse look, and Space to jump).

Voxel Placement/Destruction: The world is editable:

Left Click: Places a new grass block adjacent to the block you are looking at.

Right Click: Destroys the block you are looking at.

Procedural Generation: Randomly generates features on the starting plane:

A grid of grass blocks (boxes).

Randomly placed Mountains (tall brown blocks).

Randomly placed Trees (brown trunks with green spherical leaves).

Game Over Condition: If the player falls below the world (player.y < -1), the game terminates immediately.

🎮 Controls

Action

Key/Mouse

Function

Move Forward

W

Move in the direction the camera is facing

Move Back

S

Move backward

Strafe Left

A

Move left

Strafe Right

D

Move right

Jump

Space

Jump

Look Around

Mouse Movement

Rotate the camera view

Place Block

Left Mouse Button

Adds a new grass block

Destroy Block

Right Mouse Button

Removes the targeted block

⚠️ Requirements

This script is written in Python and requires the Ursina Engine to run.

To install Ursina, you must use pip:

pip install ursina


To run the game, save the code as a Python file (e.g., main.py) and execute it:

python main.py
