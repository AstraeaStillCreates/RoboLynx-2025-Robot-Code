# RoboLynx-2025-Robot-Code

This is the FRC team #9151 RoboLynx's code repository for the 2025 Robotics Competition. The name for the 2025 Competition is REEFSCAPE.
This project is built using the WPILib library and is designed to control a robot with swerve drive capabilities and vision processing using Limelight. 
The main components of the code include:

Main.java: The entry point for the robot application, initializing the robot using the WPILib framework.

Configs.java: Defines configuration settings for the robot's swerve modules, including motor control and feedback sensor settings.

LimelightHelpers.java: Provides utilities for interacting with the Limelight vision system, including methods to retrieve pose estimations and target tracking data.

RobotContainer.java: Manages the robot's subsystems, commands, and button mappings. 
This class sets up the default command for driving and configures button bindings for operator control.

Robot.java: The core robot class that extends WPILib's TimedRobot, handling the initialization and periodic tasks for different robot modes (autonomous, teleop, test).

Constants.java: Contains global constants used throughout the robot code, such as drive parameters, chassis configuration, and CAN IDs for motor controllers.
