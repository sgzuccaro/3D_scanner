# Handheld 3D Scanner

A 3d scanner for indoor/outdoor spacial mapping.

## Ideas
- Lidar scans need to be undistorted to remove movement influence
- Use Rtabmap to build a point cloud from lidar data
- Rtabmap can except external Odom, for this use Orbslam3. This will allow stereo (better then rgbd) vision + IMU 





## References 
Intel D415 camera parameters:

https://impulsiverobotics.com/2018/04/ros-enabled-omnidirectional-robot/



Rotating 2d lidar aggressive pose estimation

https://bitbucket.org/castacks/lidar_eskf/src/master/


Rtabmap paper

https://introlab.3it.usherbrooke.ca/mediawiki-introlab/images/7/7a/Labbe18JFR_preprint.pdf


Orb slam vs rtabmap paper

https://hal.archives-ouvertes.fr/hal-02343341/document

Stereo better then rgbd or mono for orb slam


Laser distortion compensation

http://wiki.ros.org/laser_assembler






Setup

Configure orb slam for ros:

https://roboticsknowledgebase.com/wiki/state-estimation/orb-slam2-setup/


Ros wrappers
For orbslams

https://github.com/thien94/orb_slam3_ros_wrapper

http://wiki.ros.org/orb_slam2_ros


Similar products

Stencil: very similar with open source software:
https://youtu.be/p43xFhePRLs


How to build a 3D spinning lidar paper

https://www.tu-chemnitz.de/etit/proaut/publications/taros16.pdf

