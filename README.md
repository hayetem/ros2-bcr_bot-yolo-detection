# ROS2 bcr_bot yolo detection

This is a ROS 2 project that combines the [bcr_bot](https://github.com/blackcoffeerobotics/bcr_bot.git) navigation stack with YOLO object detection using the [ros2-yolov8-template](https://github.com/Victor-Boyd/ros2-yolov8-template.git) as a base.

## Project Overview

This package integrates a mobile robot simulation and navigation setup (bcr_bot) with a real-time object detection pipeline based on YOLOv8.

### Key Features

- Enabled cameras on the `bcr_bot` to support detection
- Integrated YOLOv8-based object detection in ROS 2
- Modified and customized `package.xml` and `CMakeLists.txt` in `template_recognition` and `yolov8_template_msgs` packages
- Adapted Python code to work with a custom camera stream and added required dependencies
- Supports custom-trained YOLOv8 models

## Credits

This project is based on:

- [blackcoffeerobotics/bcr_bot](https://github.com/blackcoffeerobotics/bcr_bot) (Apache 2.0 License)
- [Victor-Boyd/ros2-yolov8-template](https://github.com/Victor-Boyd/ros2-yolov8-template) (MIT License)

Please refer to their repositories for more details. All licenses are respected and preserved.

## License

This project contains components under both the MIT and Apache 2.0 licenses. See the `LICENSE` files in their respective directories for details.

---

### How to Build

```bash
cd ~/ros2_ws
colcon build
