# Unity Robotics Hub

This is a central repository for tools, tutorials, resources, and documentation for robotic simulation in Unity.

If you have questions please feel free to contact us [here](mailto:unity-robotics@unity3d.com).

## Unity Robotics Tutorials

### Repos
- [TCP Endpoint ROS Package](https://github.com/Unity-Technologies/ROS_TCP_Endpoint)
- [TCP Connection Unity Scripts](https://github.com/Unity-Technologies/ROS-TCP-Connector)
- [URDF Importer](https://github.cds.internal.unity3d.com/unity/URDF-Importer)

### Prerequisites
- Knowlege of [ROS](https://www.ros.org/) and a working [ROS environment](https://www.ros.org/install/)
	- This tutorial was made using ROS Melodic and Python 2.
- Unity 2020.2 or newer

### Tutorials
- [C# ROS Message Class Generation](tutorials/unity_ros_message_generation/message_generation_tutorial.md)
- [ROS-Unity Integration](tutorials/ros_unity_integration/README.md)
- [URDF Importer](tutorials/urdf_importer/urdf_tutorial.md)
- [Pick and Place End-to-End](tutorials/pick_and_place/README.md)

### ROS Packages

`Robotics Demo` with example implementations of:

- Launch File
- Custom Message Types
- Custom Service
- Publisher Script
- Service Script
- TCP Endpoint Script


### unity_scripts
---

Example scripts on how to implement a ROS Publisher, Subscriber, or Service.

- RosPublishExample.cs
	- Publishes the position of a gameobject every 0.5 seconds.

- RosServiceExample.cs
	- Each time service is called return a destination position for a game object to move towards.

- RosSubscriberExample.cs
	- Subscribes to a topic that accepts color messages and uses them to change the color of a game object in the Unity scene.