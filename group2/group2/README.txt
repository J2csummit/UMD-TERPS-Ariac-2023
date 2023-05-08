in 3 different terminals run the following:

ros2 launch ariac_gazebo ariac.launch.py trial_name:=(insert trial name) competitor_pkg:=group2
ros2 launch ariac_moveit_config ariac_robots_moveit.launch.py
ros2 launch group2 competitor.launch.py
