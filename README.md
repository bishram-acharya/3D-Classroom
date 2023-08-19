# 3D-Classroom
The project's main focus is to develop an interactive and visually appealing simulation of our Classroom using the OpenGL graphics library. Through this project, users will be able to navigate virtual replica of our Classroom, providing  an engaging experience.
## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [HOW TO RUN ON YOUR LOCAL MACHINE](#HOW_TO_RUN_ON_YOUR_LOCAL_MACHINE)
- [Screenshots](#screenshots)
- [Controls](#controls)
- [Contributing](#contributing)

## Features

- Realistic 3D classroom environment
- Interactive camera controls for exploration
- Rendered classroom elements: walls, furniture, windows, snowman, fans, etc.
- Animations for fan rotation
- User-friendly interface and controls
  
## Getting Started
### Prerequisites

- [OpenGL](https://www.opengl.org/)
- [GLUT (OpenGL Utility Toolkit)](https://www.opengl.org/resources/libraries/glut/)
- C++ compiler (e.g., g++)
  
### HOW TO RUN ON YOUR LOCAL MACHINE
Opening a solution in Visual Studio and configuring OpenGL and GLUT (OpenGL Utility Toolkit) involves a few steps to ensure your project is set up correctly for OpenGL development. Here's a step-by-step guide:

Step 1: Open an Existing Solution:

Launch Visual Studio.
Go to "File" > "Open" > "Project/Solution..."
Navigate to the directory where your solution is located and select the .sln file.
i.e 3D-CLASSROOM-OPENGL.sln
Click "Open" to load the solution.
Step 2: Download and Prepare GLUT:

Download the GLUT library files (freeglut) from https://www.transmissionzero.co.uk/software/freeglut-devel/.
Extract the downloaded files to a location on your computer.
Step 3: Configure Project Settings:

In Visual Studio, right-click on your project in the Solution Explorer.
Select "Properties".
Step 4: Configure C/C++ Settings:

Under "Configuration Properties", select "VC++ Directories".
Set "Include Directories" to include the path to the "include" folder inside your GLUT directory. For example, C:\path\to\freeglut\include.
Set "Library Directories" to include the path to the "lib" folder inside your GLUT directory. For example, C:\path\to\freeglut\lib.
Step 5: Configure Linker Settings:

Still in the project properties, navigate to "Configuration Properties" > "Linker" > "Input".
Add the following library dependencies:
opengl32.lib
freeglut.lib
Ensure the "Additional Dependencies" field includes these libraries.


## Controls 
* Use arrow keys for camera movement (forward, backward, sideways)
* Use 'w', 'a', 's', 'd' keys for camera movement (forward, left, backward, right)
* Use 'x' and 'z' keys to roll the camera
* Move the mouse to adjust camera view direction

## Contributions
Contributions are welcome Aug 21 onwards ! If you'd like to enhance the project or fix any issues, feel free to fork this repository, make your changes, and submit a pull request.
