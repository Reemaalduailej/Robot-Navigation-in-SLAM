# Robot Navigation in SLAM using Gmapping

--- 

## Uage of the Project

Consider a home robot vacuum. Without SLAM, it will just move randomly within a room and may not be able to clean the entire floor surface. In addition, this approach uses excessive power, so the battery will run out more quickly. On the other hand, robots with SLAM can use information such as the number of wheel revolutions and data from cameras and other imaging sensors to determine the amount of movement needed. This is called localization. The robot can also simultaneously use the camera and other sensors to create a map of the obstacles in its surroundings and avoid cleaning the same area twice. In this project a TurtleBot3 robot with a lidar sensor has been controlled to create a map using Gmapping packages in ROS which provides laser-based SLAM. This project is a continuum to the repository [Robot Navigation using SLAM in ROS](https://github.com/Reemaalduailej/Robot-Navigation-using-SLAM-in-ROS)

---

## Softwares and Websites Used

- ROS Melodic
- Gazebo
