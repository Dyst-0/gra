## Instructions for constructing gazebo cone track worlds in this workspace

1. run 'rosrus gazebo_ros gazebo' to launch an empty world
2. In gazebo, go into "Insert" and choose "Add Path"
3. Select gazebo_world_building -> models
4. Design track as desired (the first object placed will take awhile to load)
5. Save the world as a .world file in ackermann_vehicle_gazebo -> worlds -> gazebo_world_building
6. Go into the world file, and change all fields of uri to be absolute paths (Use Change all occurrences in VScode)
E.g. <uri>model://cone_blue/cone_blue.dae</uri> becomes <uri>file:///root/gra/ros/ackermann_vehicle_gazebo/worlds/gazebo_world_building/models/cone_blue/cone_blue.dae</uri>
