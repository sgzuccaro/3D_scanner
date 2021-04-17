# 3D_scanner

A 3d scanner for indoor/outdoor spacial mapping.

## Ideas
- Lidar scans need to be undistorted to remove movement influence
- Use Rtabmap to build a point cloud from lidar data
- Rtabmap can except external Odom, for this use Orbslam3. This will allow stereo vision + IMU 
