# Jackal_tutorial

# Jackal_Install

  sudo apt-get install ros-melodic-jackal-simulator ros-melodic-jackal-desktop ros-melodic-jackal-navigation

# Jackal_Navigating with Jackal

  roslaunch jackal_gazebo jackal_world.launch
  
  - 추천
  
    roslaunch jackal_gazebo jackal_world.launch config:=front_laser

# Jackal_Navigation without a map

  - To launch the navigation demo, run:
  
    - roslaunch jackal_navigation odom_navigation_demo.launch
    
  - To visualize with the suggested rviz configuration launch:
  
    - roslaunch jackal_viz view_robot.launch config:=navigation

  - Launch Rviz
    
     - roslaunch jackal_viz view_robot.launch

# Jackal Run
- roslaunch jackal_gazebo jackal_world.launch config:=front_laser
- roslaunch jackal_navigation odom_navigation_demo.launch
- roslaunch jackal_viz view_robot.launch config:=navigation
