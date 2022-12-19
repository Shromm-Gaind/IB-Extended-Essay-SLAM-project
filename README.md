# Code written for IB Extended Essay on to what extent is sensor fusion SLAM better than passive slam algorthims at autonomous navigation

This repository was designed for analyzing data from LIDAR, ZED camera, IMU and also has modules for sensor fusion with EKF and PF based on ROS

This research is dataset based. I would suggest creating your robot and getting your own dataset

The main packages:
- racecar_description - it is for rendering the dimensional model of the car in RViz
- sensor_fusion - it is for fusing data from different sensors.
    - /sensor_fusion/scripts/ExtendedKalmanFilter/ - sensor fusion with Extended Kalman Filter
    - /sensor_fusion/scripts/ParticalFilter/ - sensor fusion with Particle Filter
    - other modules - data processing, error calculation, plotting data
