# Pipeless Chemical Plant

Project group WS-2018/2019 - TU Dortmund

ROS package for a pipeless chemical plant set up with four stations, controlling at most two robots that are used to transport the chemicals from one station to another.

The aim of the group was to integrate the available model of the Plant from C# to ROS Library. For simplicity of handing over the work from one semster group to another, python was used as the preferred programing language.

## Dependencies

 - [python_qt_binding](https://github.com/ros-visualization/python_qt_binding)
 - OpenCV
 - [image_proc](https://github.com/ros-perception/image_pipeline)
 - [create_autonomy](https://github.com/AutonomyLab/create_autonomy)

## pipeless_plant_app

 - GUI made for the project using Qt.
 - Auto Demo for the presentation

## pipeless_plant_bringup

 - Bring Up all the nodes for the project
 - Camera, Robot, PLC Controller and RVIZ

## pipeless_plant_navigation

 - Launch move_base and map_server for robot motion.

## pipeless_plant_plc_controller

 - PLC Controller for maneuvering the actuators in the plant.
