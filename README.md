# viam-yahboom-transbot-ros

## TODO

Use generic config

## Published topics
 * /contour_moments/parameter_updates [dynamic_reconfigure/Config] 1 publisher
 * /contour_moments/image/theora [theora_image_transport/Packet] 1 publisher
 * /contour_moments/image/compressed [sensor_msgs/CompressedImage] 1 publisher
 * /control_mode [std_msgs/Int32] 1 publisher
 * /edge_detection/image/compressedDepth/parameter_descriptions [dynamic_reconfigure/ConfigDescription] 1 publisher
 * /image_msg [transbot_msgs/Image_Msg] 2 publishers
 * /edition [transbot_msgs/Edition] 1 publisher
 * /tf [tf2_msgs/TFMessage] 5 publishers
 * /imu/data_raw [sensor_msgs/Imu] 1 publisher
 * /PWMServo [transbot_msgs/PWMServo] 3 publishers
 * /odom [nav_msgs/Odometry] 1 publisher
 * /contour_moments/image/compressedDepth [sensor_msgs/CompressedImage] 1 publisher
 * /PatrolWarning [transbot_msgs/PatrolWarning] 2 publishers
 * /contour_moments/image/compressedDepth/parameter_updates [dynamic_reconfigure/Config] 1 publisher
 * /edge_detection/image/compressedDepth [sensor_msgs/CompressedImage] 1 publisher
 * /transbot_node/parameter_descriptions [dynamic_reconfigure/ConfigDescription] 1 publisher
 * /imu_filter_madgwick/parameter_updates [dynamic_reconfigure/Config] 1 publisher
 * /contour_moments/image/compressed/parameter_descriptions [dynamic_reconfigure/ConfigDescription] 1 publisher
 * /Graphics_topic [transbot_msgs/General] 2 publishers
 * /colorTracker [transbot_msgs/General] 2 publishers
 * /contour_moments/image/theora/parameter_descriptions [dynamic_reconfigure/ConfigDescription] 1 publisher
 * /transbot/get_vel [geometry_msgs/Twist] 1 publisher
 * /contour_moments/moments [opencv_apps/MomentArrayStamped] 1 publisher
 * /contour_moments/image/theora/parameter_updates [dynamic_reconfigure/Config] 1 publisher
 * /TransbotPatrol/parameter_descriptions [dynamic_reconfigure/ConfigDescription] 1 publisher
 * /edge_detection/image/compressed [sensor_msgs/CompressedImage] 1 publisher
 * /tf_static [tf2_msgs/TFMessage] 1 publisher
 * /Autopilot [transbot_msgs/General] 2 publishers
 * /edge_detection/image/compressed/parameter_descriptions [dynamic_reconfigure/ConfigDescription] 1 publisher
 * /edge_detection/image/compressedDepth/parameter_updates [dynamic_reconfigure/Config] 1 publisher
 * /diagnostics [diagnostic_msgs/DiagnosticArray] 2 publishers
 * /cmd_vel [geometry_msgs/Twist] 3 publishers
 * /image [sensor_msgs/Image] 1 publisher
 * /edge_detection/image [sensor_msgs/Image] 1 publisher
 * /edge_detection/parameter_descriptions [dynamic_reconfigure/ConfigDescription] 1 publisher
 * /Adjust [transbot_msgs/Adjust] 1 publisher
 * /TransbotPatrol/parameter_updates [dynamic_reconfigure/Config] 1 publisher
 * /voltage [transbot_msgs/Battery] 1 publisher
 * /rosout [rosgraph_msgs/Log] 18 publishers
 * /joint_states [sensor_msgs/JointState] 1 publisher
 * /imu/data [sensor_msgs/Imu] 1 publisher
 * /transbot_node/parameter_updates [dynamic_reconfigure/Config] 1 publisher
 * /odom_raw [nav_msgs/Odometry] 1 publisher
 * /rosout_agg [rosgraph_msgs/Log] 1 publisher
 * /contour_moments/parameter_descriptions [dynamic_reconfigure/ConfigDescription] 1 publisher
 * /JoyState [transbot_msgs/JoyState] 1 publisher
 * /TargetAngle [transbot_msgs/Arm] 3 publishers
 * /contour_moments/image/compressed/parameter_updates [dynamic_reconfigure/Config] 1 publisher
 * /imu_filter_madgwick/parameter_descriptions [dynamic_reconfigure/ConfigDescription] 1 publisher
 * /edge_detection/image/theora/parameter_updates [dynamic_reconfigure/Config] 1 publisher
 * /contour_moments/image [sensor_msgs/Image] 1 publisher
 * /edge_detection/image/compressed/parameter_updates [dynamic_reconfigure/Config] 1 publisher
 * /edge_detection/parameter_updates [dynamic_reconfigure/Config] 1 publisher
 * /edge_detection/image/theora/parameter_descriptions [dynamic_reconfigure/ConfigDescription] 1 publisher
 * /joy [sensor_msgs/Joy] 1 publisher
 * /move_base/cancel [actionlib_msgs/GoalID] 3 publishers
 * /transbot/imu [sensor_msgs/Imu] 1 publisher
 * /edge_detection/image/theora [theora_image_transport/Packet] 1 publisher
 * /Current_point [transbot_msgs/Position] 2 publishers
 * /contour_moments/image/compressedDepth/parameter_descriptions [dynamic_reconfigure/ConfigDescription] 1 publisher

## Subscribed topics
 * /control_mode [std_msgs/Int32] 1 subscriber
 * /image_msg [transbot_msgs/Image_Msg] 1 subscriber
 * /edition [transbot_msgs/Edition] 1 subscriber
 * /tf [tf2_msgs/TFMessage] 2 subscribers
 * /imu/data_raw [sensor_msgs/Imu] 1 subscriber
 * /PWMServo [transbot_msgs/PWMServo] 1 subscriber
 * /scan [sensor_msgs/LaserScan] 1 subscriber
 * /transbot/get_vel [geometry_msgs/Twist] 1 subscriber
 * /set_pose [geometry_msgs/PoseWithCovarianceStamped] 1 subscriber
 * /TransbotPatrol/parameter_descriptions [dynamic_reconfigure/ConfigDescription] 1 subscriber
 * /tf_static [tf2_msgs/TFMessage] 2 subscribers
 * /PatrolWarning [transbot_msgs/PatrolWarning] 1 subscriber
 * /cmd_vel [geometry_msgs/Twist] 1 subscriber
 * /Adjust [transbot_msgs/Adjust] 1 subscriber
 * /TransbotPatrol/parameter_updates [dynamic_reconfigure/Config] 1 subscriber
 * /voltage [transbot_msgs/Battery] 1 subscriber
 * /rosout [rosgraph_msgs/Log] 1 subscriber
 * /joint_states [sensor_msgs/JointState] 1 subscriber
 * /imu/data [sensor_msgs/Imu] 1 subscriber
 * /joy/set_feedback [sensor_msgs/JoyFeedbackArray] 1 subscriber
 * /odom_raw [nav_msgs/Odometry] 1 subscriber
 * /JoyState [transbot_msgs/JoyState] 2 subscribers
 * /TargetAngle [transbot_msgs/Arm] 1 subscriber
 * /joy [sensor_msgs/Joy] 1 subscriber
 * /transbot/imu [sensor_msgs/Imu] 1 subscriber

