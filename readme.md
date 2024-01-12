# ILCC_ROS  

ILCC’s ROS package

## Subscribed topics  

/point_cloud_topic

/image_topic

## Published topics

### Registration Results

/visualization_marker_array  
/points_corners  
/points_segs  
/points_raw  

## Usage

### Installation

`mkdir catkin_ws/src/my_pkg`  
`cd catkin_ws/srcmy_pkg`  
`git clone https://github.com/hai12hai12/lidar.git`  
`cd catkin_ws`
`catkin_make`

### Explanation of files

load: ROS Signal Reception and File Storage.  
Registion:File Registration for Alignment.  
Visualization:Visualization of Alignment Results.  

### Process

1.1.Roslaunch 2.launch is ready to receive signals for the release of the package, press the spacebar to store the subscribed messages as a file.  
2.The project subscribes to ponitcloud2 and image messages. Messages can be released by playing back the rosbag we provide.  
3.Roslaunch 3.launch for point cloud registration via ILCC.  
4.Roslaunch 4.launch to visualize the registration results. Visualize the results：  
