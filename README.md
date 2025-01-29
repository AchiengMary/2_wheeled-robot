#2-Wheeled Robot Simulation (ROS 2 & Webots)

This project sets up a basic 2-wheeled robot in Webots and integrates it with ROS 2 for simulation and control. It includes:

    A URDF model of the robot
    Webots world file
    ROS2 package for launching the simulation

2-wheeled-robot/
│── src/                      # Source files for the ROS 2 package  
│── urdf/                     # Robot description (URDF/Xacro)  
│── worlds/                   # Webots world files  
│── launch/                   # ROS 2 launch files  
│── CMakeLists.txt             # CMake build file  
│── package.xml                # ROS 2 package manifest  
│── README.md                  # Project documentation  

Future Improvements

    Adding sensor support (LIDAR, IMU, Camera)
    Enhancing robot control

Contributors

    Achieng Mary – achieng75mary@gmail.com
