nao_moveit_config
====================


URDF and Textures used
======================

This moveit package is based on a textured nao :
https://github.com/vrabaud/nao_meshes_generator

The urdf used for the generation of the configuration file is embedded in this package. It's the same that the one in nao_description : https://github.com/keulYSMB/nao_robot/tree/devel/nao_description/urdf/naov4_generated_urdf

How to use it
=============

Without robot
-------------
You can run this moveit package either unconnected to any robot or attached to a robot -real or simulated):
For a standalone execution :
roslaunch nao_moveit_config demo.launch

On a real nao
--------------
To launch it on a real nao : 
roslaunch nao_dcm_bringup nao_dcm_H25_bringup_remote.launch << launch nao_bringup
roslaunch nao_moveit_config moveit_planner.launch

On a simulated nao (in gazebo)
-----------------------------
To launch it on a gazebo simulated nao (in gazebo):
roslaunch nao_dcm_gazebo nao_dcm_gazebo_H25.launch
roslaunch nao_moveit_config moveit_planner.launch

This is based on the work of Konstantinos Chatzilygeroudis: https://github.com/costashatz/nao_dcm.

TODO : 
------
Create our own nao_driver/nao_bringup to use moveit with ALMotion

