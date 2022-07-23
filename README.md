# ROS Packages for Conarobot MR1D

## 1. Package mr1d_description

> 功能：对MR1D进行运动学建模，并输出其模型描述urdf文件。<br>
> 启动：roslaunch mr1d_description mr1d_display.launch

## 2. Package mr1d_control

> 功能：配置生成MR1D的运动控制器及rqt窗口配置文件。<br>
> 启动：roslaunch mr1d_control mr1d_control.launch

## 3. Package mr1d_gazebo

> 功能：在gazebo中利用mr1d_control功能包对MR1D进行运动仿真，其中基于sdf版本的存在问题（已弃用）。<br>
> 启动：roslaunch mr1d_gazebo mr1d_gazebo.launch

## 4. Package Dependency: Package pegasus_gazebo_plugins

> 功能：用以解决urdf模型描述文件中不支持闭链的问题，插件内容不完整，编译存在问题（已弃用）。
