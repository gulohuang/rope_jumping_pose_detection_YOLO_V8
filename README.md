# rope_jumping_pose_detection_YOLO_V8
When I was coaching my son on rope jumping and found that he always tripped on his left foot. So I took this video and applied pose detection to trouble shoot the problem. <br>
The root cause is quite simple, as shown in the video, his right elbow and right arm were often higher than his left side, resulted unbalanced swinging of the rope. <br>
The rope was moving in upper-left and botten-right direction and tripped on left foot.

![](https://github.com/gulohuang/rope_jumping_pose_detection_YOLO_V8/blob/main/rope_jumping_tripped.gif)

## Frame before he tripped.
![](https://github.com/gulohuang/rope_jumping_pose_detection_YOLO_V8/blob/main/rope_jumping_tripped_frame_before_tripped.jpg)

YOLOv8x-pose-p6 was used for the pose detection.
video to gif using MoviePy.
