# 3 DOF Servoing Simulation Project
Welcome to the 3 DOF Servoing Simulation project! This project focuses on simulating the servoing behavior of a robotic arm with three degrees of freedom (DOF) using MoveIt for motion planning and Gazebo with RViz for simulation visualization.

# Introduction
The goal of this project is to develop a simulation environment that allows for accurate planning and simulation of the servoing process. Servoing refers to the process of continuously adjusting the position and orientation of a robot's end-effector to track a desired target. In this project, we specifically focus on a robotic arm with three DOF, meaning it has three joints that control its movement.

# Technologies Used
To achieve our objectives, we utilize two main technologies: Solidworks, MoveIt and Gazebo with RViz. Let's take a closer look at each of them:

# MoveIt

![moveit_plugins](https://github.com/TXWISSRX/3DOF-Servoing-/assets/119014917/7c2d30ef-b8f2-44f2-9ce4-04f864a551cc)

MoveIt is a widely-used software framework for motion planning, kinematics, and control of robotic systems. It provides an easy-to-use interface for defining robot models, specifying goals, and generating smooth and collision-free trajectories for the robot to follow. In our project, we leverage MoveIt's capabilities to plan the poses of our 3 DOF robotic arm.

![Screenshot 2023-05-30 193758](https://github.com/TXWISSRX/3DOF-Servoing-/assets/119014917/b439c8d6-d415-4d5b-aa3d-83c2c0f21882)


# Gazebo with RViz

![Screenshot 2023-06-09 222803](https://github.com/TXWISSRX/3DOF-Servoing-/assets/119014917/129c52b3-1bfc-4f93-8313-37f9fd4c9f45)

Gazebo is a powerful physics-based robot simulator that allows us to create realistic environments and simulate the behavior of robots in a virtual world. It provides accurate physics simulations, sensor integration, and real-time rendering.



![Screenshot 2023-06-09 222832](https://github.com/TXWISSRX/3DOF-Servoing-/assets/119014917/b4522115-2b62-43c1-85cb-2728babb9c02)

RViz, on the other hand, is a 3D visualization tool commonly used in robotics to display sensor data, robot models, and other relevant information. Together, Gazebo and RViz enable us to visualize and simulate the servoing process of our robotic arm.

# Workflow
![Screenshot 2023-06-09 222921](https://github.com/TXWISSRX/3DOF-Servoing-/assets/119014917/df7842ea-3695-498d-826b-c935507c3459)

Here's a brief overview of the workflow we follow in this project:

## Modeling the Robotic Arm: 
We define the geometry and kinematics of our 3 DOF robotic arm, specifying its joint types, limits, and physical properties.

## Motion Planning with MoveIt: 
Using MoveIt, we plan the poses and trajectories that our robotic arm needs to follow to track the desired target. MoveIt takes into account collision avoidance and joint constraints during the planning process.

## Simulation in Gazebo: 
With the planned trajectories, we simulate the servoing behavior of the robotic arm in Gazebo. Gazebo provides a physics-based simulation environment, enabling us to observe how the arm's movements correspond to the desired target tracking.

##  Visualization with RViz: 
We utilize RViz to visualize the simulated robotic arm, the target object, and any relevant sensor data. RViz provides an interactive 3D visualization interface, allowing us to analyze and debug the servoing behavior.

# Getting Started
To get started with the project, please refer to the project's documentation. 


# Conclusion
The 3 DOF Servoing Simulation project combines the power of MoveIt, Gazebo, and RViz to provide a comprehensive simulation environment for studying and optimizing the servoing behavior of a robotic arm. By accurately planning poses and simulating the servoing process, we can evaluate the performance of our control algorithms and improve the efficiency and accuracy of our robotic systems.

