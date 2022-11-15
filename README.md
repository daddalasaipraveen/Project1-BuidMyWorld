# Project1-BuidMyWorld

Overview:
This project to design a Robot and simulation world for all your projects in this Robotics Software Engineer Nanodegree Program

1. Build a single floor wall structure using the Building Editor tool in Gazebo. Apply at least one feature, one color, and optionally one texture to your structure. Make sure there's enough space between the walls for a robot to navigate.
2. Model any object of your choice using the Model Editor tool in Gazebo. Your model links should be connected with joints.
3. Import your structure and two instances of your model inside an empty Gazebo World.
4. Import at least one model from the Gazebo online library and implement it in your existing Gazebo world.
5. Write a C++ World Plugin to interact with your world. Your code should display “Welcome to ’s World!” message as soon as you launch the Gazebo world file.

Directory Structure:
The sample simulation world folder has the following directory structure.
Here are the files that are available in project folder:
1. model Folder: Contains a folder for robot model designed in the Model Editor tool of Gazebo,
and Environment designed in the Building Editor tool of Gazebo
2. world folder: Gazebo world file that includes the all the models
3. script folder: Gazebo world plugin C++ script
4. CMakeLists.txt file to link the C++ code to libraries
