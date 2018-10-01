# video_stream

Publish a video stream (including rtsp, webcams on /dev/video and video files) on a ROS image topic

Requires installation of the [*video_stream_opencv*](http://wiki.ros.org/video_stream_opencv) ROS package:
```
sudo apt-get install ros-kinetic-video-stream-opencv
```

Camera calibration procedure is described [here](http://wiki.ros.org/camera_calibration/Tutorials/MonocularCalibration)
```
rosrun camera_calibration cameracalibrator.py --size 8x6 --square 0.108 image:=/webcam/image_raw camera:=/webcam
```

