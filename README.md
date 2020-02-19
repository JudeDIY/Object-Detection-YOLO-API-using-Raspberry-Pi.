# Object-Detection-YOLO-API-using-Raspberry-Pi.

This project is about detecting objects in an around you. This is powered by YOLO and raspberry pi. These object detection is used to analyze the photo and throws the result to the user.

ISO File:
https://drive.google.com/drive/folders/1g0RadTgJ1YhrSGR-t9rKFNx6MT9T-6Gd?usp=sharing


cd darknet
./darknet detector test cfg/voc.data cfg/tiny-yolo-voc.cfg tiny-yolo-voc.weights camera/cam.jpg
  

cd darknet/camera
raspistill -o cam.jpg
