# YOLO-version-2-Face-detection
# Face detection based on YOLO darknet
This face detection system has been tested on Nvidia GTX1060, Ubuntu 16.04, CUDA 8, OpenCV 3.1.

The model yolo-face_final.weights is provided through dropbox link:


sudo make
./darknet yolo demo cfg/yolo-face.cfg yolo-face_final.weights
