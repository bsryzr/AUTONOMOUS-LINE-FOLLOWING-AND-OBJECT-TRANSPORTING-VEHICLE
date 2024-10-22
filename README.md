# AUTONOMOUS-LINE-FOLLOWING-AND-OBJECT-TRANSPORTING-VEHICLE
<img width="173" alt="1 robot" src="https://github.com/user-attachments/assets/fae048df-3f2d-44ec-a959-56701f959bd9">
<img width="117" alt="2robot " src="https://github.com/user-attachments/assets/8a9d77f5-2b4a-46ba-adb6-7ae4ee5cfcee">
<img width="197" alt="3foto" src="https://github.com/user-attachments/assets/49f4882a-cef5-4a2e-99fa-0323ee1be7dd">

This project involved developing an Autonomous Vehicle (AV) capable of following a designated line, detecting and transporting small objects, and avoiding obstacles, all within a 3m x 4m enclosed space. The AV was fully autonomous, operating without any human intervention, and successfully demonstrated key functionalities such as line following, object handling, and obstacle avoidance.

# 1.Key Features and Functionalities:
# Line Following:

The AV was equipped with line-following sensors, which enabled it to detect and follow a predefined path marked by lines on the ground.
The vehicle used infrared (IR) sensors to continuously monitor the line and adjust its direction to stay on track. This ensured precise navigation within the designated area.
# Object Detection and Recognition:
The AV was programmed to identify small objects placed on the path using a combination of ultrasonic sensors and computer vision techniques.
Upon detecting an object, the vehicle stopped and activated its object-handling system to pick up the item.
# Object Manipulation:
A small robotic arm or gripper was integrated into the vehicle, allowing it to pick up, transport, and place objects at a designated location.
The system was capable of grasping objects of various sizes and shapes within predefined limits.
# Obstacle Avoidance:
The AV featured an obstacle detection system using ultrasonic sensors to prevent collisions.
The vehicle dynamically adjusted its path when obstacles were detected, momentarily departing from the line and then returning once the path was clear.
# Autonomous Navigation:
The vehicle’s navigation system combined sensor data to move efficiently within the space, following the line and adjusting its path when necessary for object transportation or obstacle avoidance.
The entire process, from following the line to transporting objects and avoiding obstacles, was performed autonomously with minimal error.

# 2.System Design:
Line-Following Sensors: Infrared (IR) sensors mounted under the vehicle tracked the line on the floor, guiding the vehicle through the set route.

Object Recognition: Using a combination of sensors (ultrasonic and possibly camera-based systems), the AV identified objects for pickup.

Obstacle Avoidance: The vehicle used ultrasonic sensors to detect obstacles in its path, allowing it to stop, avoid collisions, and reroute as necessary.

Object Manipulation: A robotic arm or gripper attached to the vehicle enabled the pickup, secure holding, and placement of objects at specified points.

# 3.Used Technologies:
Line-Following Sensors (IR Sensors)
Object Recognition (Ultrasonic Sensors, Computer Vision)
Autonomous Navigation
Obstacle Avoidance
Object Manipulation (Robotic Arm or Gripper)
# 4.Outcome:
The project successfully demonstrated the AV's ability to autonomously:

Follow a line-based path
Detect and manipulate objects
Avoid obstacles within the environment
