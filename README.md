# Chaos Engine™
Developed by Team Mayhem™

![alt text](ChaosEngine.jpg)

## Description
Chaos Engine is a C++/Opengl (later added support for Linux and Vulkan) developed by a team of 3 devs called Team Mayhem during a 5 month time period as part of a graduation project, The objective of this project was to make a Game engine from scratch using as few libraries as possible.

## Constraints
- The editor must work on Windows (Later added support for Linux).
- The engine must use a custom mathematics library.
- The engine must support OpenGL as rendering API (Later added Vulkan).
- The engine can use an existing physic library.

## My part
During the development process i was responsible for:
- Setting up an Event System/Dispatcher.
- Asset conditioning (.chaosasset)
- Low level Rendering pipeline.
- Shader creation for different types of materials.
- Lighting system.
- Camera system.
- Post processing effects (GBuffer, FXAA, Blur, etc).
- Deferred rendering pipeline.
- PingPong shading.
- Shadows
- PBR rendering pipeline.
- Editor creation 

## Libraries used
- PhysX
- Assimp
- SpdLog
- OpenGl
- Qt

## How to Buid Chaos Engine
CMake 3.12.2 or newer is needed to complete the build.
First under ChaosEngine/Source folder run GenerateProject.bat to generate the VS solution,
this will create a build folder that will contain said solution.
Solution's output will be located at ChaosEngine/Build.

## Project status
- The project is currently a work in progress, some new features will be added on future updates.
- We are currently halfway through the time given for the project.

# Chaos Editor™
Developed by Team Mayhem™

![alt text](ChaosEditor.jpg)

# How to Build Chaos Editor
First install Qt 5.12.0 in C:/ or specify in ChaosEditor/Source/ChaosEditor/CMakeLists.txt the Qt folder path then under ChaosEditor/Source run GenerateProject.bat to generate the VS solution, this will create a build folder that will contain said solution.
Solution's output will be located at ChaosEditor/Build.

## General Inputs
 Right Click: Fly mode.
 Middle Click: Pan mode.
 Alt: Orbit mode.
 Left Shift: Move faster.
 
 Fly Mode:
  W: Move forward.
  A: Move left.
  S: Move backward.
  D: Move right.
  Q: Move down.
  E: Move up.

 Pan Mode:
  Mouse drag: Pan.

 Orbit Mode:
   Left Click & Drag: Orbit.

## Engine Inputs
 ESC: Quit.
 1:  Change main mesh to cube.
 2:  Change main mesh to sphere.
 R:  Reload all shaders.
 U:  Unload all resources.
 L:  Load all resources.
 G:  Toggle grid.
 B: Spawn light orbs.
 F1: Toggle wireframe.
 F5: Switch to scene 1.
 F6: Switch to scene 2.
 ↑:  Move main gameobject on -Z axis.
 ↓:  Move main gameobject on Z axis.
 ←:  Move main gameobject on -X axis.
 →:  Move main gameobject on X axis.

 ## Editor Inputs
 
 Q: Select tool.
 W: Move tool.
 E: Rotate tool.
 R: Scale tool.