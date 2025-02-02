This projects point was to simulate a plant in ROS Gazeebo. 

Right now the project is missing the STL file because of its size. You need to add it to catkin_ws/src/blueberry_model/meshes, for this project the name is blueberry_plant.stl

For this project to work you need to install ROS noetic and then add the following lines to the terminal.
cd ~/catkin_ws;
catkin_make;
source devel/setup.bash;
roslaunch blueberry_model display.launch;

Also added my sideproject Helios 3D plant webpennetree plugin procedually generated blueberry plant XML file parameters.
