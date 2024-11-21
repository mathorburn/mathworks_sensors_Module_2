%% Description of scripts in Module 2

1. angular_position.slx - Simulink model for estimating angular position from Accelerometer and Gyroscope of iOS device. (Since Simulink support for iOS devices couldn't be configured, this is not simulatable at this time)

2. camera_lidar_sensor_fusion.mlx - MATLAB script for and finding the distance of an object by combining camera and lidar sensor data. The point cloud and image are obtained from a matrix file in Lidar toolbox.

3. estimate_mobile_orientation_IMU_filter.mlx - MATLAB script to estimate orientation of a mobile phone from its Accelerometer and Gyroscope readings acquired by connecting to MATLAB mobile app.

4. intro_MatchedFilter_KalmanFilter.mlx - MATLAB script introducing the concepts of Matched filter and Kalman filter with an example each.

5. sensor_acquisition.mlx - MATLAB script showing:
	* Desktop MATLAB connection to iOS/Android device
	* Acquiring sensor data from device
	* Plotting the values over time