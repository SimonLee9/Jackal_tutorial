# Jackal_tutorial

# Jackal_Install

  sudo apt-get install ros-melodic-jackal-simulator ros-melodic-jackal-desktop ros-melodic-jackal-navigation

# Jackal_Navigating with Jackal (navigation without a map)

  roslaunch jackal_gazebo jackal_world.launch
  
  - 추천
  
  roslaunch jackal_gazebo jackal_world.launch config:=front_laser
