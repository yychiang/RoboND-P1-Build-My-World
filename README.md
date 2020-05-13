# RoboND-P1-Build-My-World
The first project of RoboND,


* Directory Structure

The Project1 folder has the following directory structure:
```text
Project1                          # Build My World Project 
    ├── model                          # Model files 
    │   ├── myhouse
    │   │   ├── model.config
    │   │   ├── model.sdf
    │   ├── myturtle
    │   │   ├── model.config
    │   │   ├── model.sdf
    ├── script                         # Gazebo World plugin C++ script      
    │   ├── hello.cpp
    ├── world                          # Gazebo main World containing models 
    │   ├── myworld.world
    ├── CMakeLists.txt                 # Link libraries 
    └──                              
```
If you want to view the robots along with their environment, just download it and put 'Project1' into your '/home' directory in Ubuntu. Then change the directory into world, just type:
```
$ cd ~/Project1/world
```
Then, type:
```
$ gazebo myworld.world
```
