**Real-Time Lane Detection**:

Real-Time Lane Detection using OpenCV

**Overview:**

This project is a real-time lane detection system designed to assist autonomous driving or driver-assistance systems by identifying road lanes accurately.

It leverages the YOLOv5 object detection model combined with OpenCV, Python, and optionally a Flask web app and SQL database for real-time visualization and analytics logging.

**Features:**

1.Real-time video stream processing

2.Lane detection using YOLOv5

3.Annotated lane boundaries

4.FPS (frames per second) monitoring

5.Logging detection data to SQL database

**Technologies used:**

**Python:**

1.Main language used to write detection, training, and preprocessing scripts

2.Huge ecosystem (PyTorch, OpenCV, etc.)

3.Readability and fast prototyping

4.Easy integration with databases and real-time systems

**YOLOV5:**
1.Real-time Object Detection Model

2.Purpose: Detects lane markings as object classes in each frame.

3.Key Features:

    a.Extremely fast and accurate object detection

    b..Can be trained on a custom dataset (e.g., annotated lane markings)

4.Written in PyTorch and maintained by Ultralytics

5.Why Used: Ideal for real-time applications like lane detection in ADAS due to low latency and high FPS.

**OpenCv:**

1.Image/Video Processing Library

2.Captures real-time video from webcam or files

3.Processes frames (resize, color space conversion)

**Pytorch:**

1.Backbone framework used by YOLOv5 for model building and training.

2.Dynamic computation graph (flexibility during training)

3.Easier to debug than TensorFlow

4.Optimized GPU support for fast training/inference

**Numpy:**

1.Scientific Computing Library

2.Handles matrix operations, coordinates of lanes, and image array manipulation.

3.Efficient and optimized operations on large arrays and images.
