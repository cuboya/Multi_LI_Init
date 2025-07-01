## Multi-IMU and Single-LiDAR Calibration

This project is modified from [hku-mars/LiDAR_IMU_Init](https://github.com/hku-mars/LiDAR_IMU_Init.git).

### Features

- Supports calibration of multiple IMUs with a single LiDAR
- Outputs individual extrinsic parameters for each IMU relative to the LiDAR

### Launch

Run the calibration using ROS:

```bash
roslaunch lidar_imu_init multi.launch
