# CHAT BOT

## ABOUT:<br />
**chat bot establish communication between different users in ROS{i.e talker_a,talker_b,listener_a,listener_b}<br />**

### COMMANDS :
1. **To start the standard publisher node <br />**
	*talker_a*
	> source ./devel/setup.bash <br />
	  rosrun my_robot_controller talker_a <br />
	
	*talker_b*
	> source ./devel/setup.bash <br />
	  rosrun my_robot_controller talker_b <br />
	
2. **To start the standard subscriber node <br />**
	*listener_a*
	> source ./devel/setup.bash <br />
	  rosrun my_robot_controller listener_a <br />
	  
	*listener_b*
	>source ./devel/setup.bash <br />
	 rosrun my_robot_controller listener_b <br />
	<br />
	<br />
	PS:  I don't know why, But each time in new terminal you have to run "source ./devel/setup.bash" before running the nodes. 
