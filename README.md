Read Me

Question 1

https://a360.co/3Abcq31


1) a) Workspace - catkin_ws
   b) package   - catkin_ws/src/bot_description

2)  Mechanical Design is done by using Fusion 360 and converted into ROS by plugin https://github.com/syuntoku14/fusion2urdf  

3) To Visualize the Rviz
    roslaunch bot_description rviz.launch
    
4) To Visualize in Gazebo
    roslaunch bot_description spawn.launch

5) For differential Drive plugin and teleop for moving the robot
   roslaunch bot_description control.launch 
   rosrun teleop_twist_keyboard teleop_twist_keyboard.py

Question 2

2)  pakage - bot_world
		-worlds
		-launch
		
   To launch the gazebo World ( not same in the question)
		- roslaunch bot_world gazebo_world.launch
			
		
Question 3
  
  0 to 120 degree range laser scan  /scan ( changes in Gazebo plugin)
   To Visualize in Gazebo
    roslaunch bot_description spawn.launch

Question 4
 
  roslaunch bot_description gazebo.launch
  roslaunch bot_description naviation.launch 
  Rviz
 
![Robot Path](https://github.com/EdwinGeorge1/Ogmen/blob/master/DALL%C2%B7E%202024-07-30%2022.12.43%20-%20A%20clear%20and%20simple%20diagram%20showing%20the%20path%20of%20a%20robot%20moving%20through%20five%20waypoints.%20The%20waypoints%20are%20labeled%20with%20their%20coordinates%20and%20orientation.webp)










  
