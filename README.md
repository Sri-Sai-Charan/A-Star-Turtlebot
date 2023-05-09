# A-Star-Turtlebot

# Overview

The TurtleBot kit consists of a mobile base, 2D/3D distance sensor, laptop computer or SBC(Single Board Computer), and the TurtleBot mounting hardware kit. 
# Usage

1. Place Part2 inside catkin_ws/src
2. catkin_make from root
3. source devel/setup.bash
4. execute `roslaunch astar_turtlebot3 demo.launch x_pos:=-4 y_pos:=-4 theta:=0 x_pos_f:=4 y_pos_f:=4 clearance:=2 rpm1:=60 rpm2:=55`

## Folder Structure 
```
📦A-Star-Turtlebot
 ┣ 📂launch
 ┃ ┗ 📜demo.launch
 ┣ 📂maps
 ┃ ┗ 📜map.world
 ┣ 📂scripts
 ┃ ┣ 📂__pycache__
 ┃ ┣ 📜AStar.py
 ┃ ┣ 📜Config.py
 ┃ ┣ 📜RRTStarFN.py
 ┃ ┣ 📜bidirectionalRRTStarFND.py
 ┃ ┣ 📜controller.py
 ┃ ┗ 📜utils.py
 ┣ 📜CMakeLists.txt
 ┣ 📜README.md
 ┗ 📜package.xml
 ```
