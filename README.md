# 3D-Classroom
The project's main focus is to develop an interactive and visually appealing simulation of our Classroom using the OpenGL graphics library. Through this project, users will be able to navigate virtual replica of our Classroom, providing  an engaging experience.
# HOW TO RUN ON YOUR LOCAL MACHINE
Opening a solution in Visual Studio and configuring OpenGL and GLUT (OpenGL Utility Toolkit) involves a few steps to ensure your project is set up correctly for OpenGL development. Here's a step-by-step guide:

Step 1: Open an Existing Solution:

Launch Visual Studio.
GGo to "File" > "Open" > "Project/Solution..."
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


# Features
*Replica of real BCTAB classroom
*Navigable
*Rotating fan animation
