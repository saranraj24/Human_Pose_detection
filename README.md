# Introduction:
This is my first try to detect human pose. I have used movenet, an POSE detection model developed by Google. Where it detects 17 keypoints of a human body.
There are two variants available Lightning and Thunder.
- Lightning: Designed for latency-critical applications, running faster than real-time (30+ FPS) on most modern devices
- Thunder: Designed for applications that require high accuracy

# Model path:
https://tfhub.dev/google/movenet/singlepose/lightning/4

# Keypoints:
'nose', 'left_eye', 'right_eye', 'left_ear', 'right_ear', 'left_shoulder', 'right_shoulder', 'left_elbow', 'right_elbow', 'left_wrist', 'right_wrist', 'left_hip', 'right_hip', 'left_knee', 'right_knee', 'left_ankle', 'right_ankle'


# Ref
https://www.tensorflow.org/hub/tutorials/movenet?form=MG0AV3
