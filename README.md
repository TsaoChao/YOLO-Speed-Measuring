# YOLO-Speed-Measuring
* the project of IAVI class in ZJU
* tracking the moving object actively and use depth camera to measure the speed(in multi-target and realtime). 
1. Detecting moving pixel in the picture.
2. Using YOLOv3 to detect the object in this area.
3. Using KCF of CSRT algorithm to track the object detected by YOLOv3.
4. Using depth camera(intel realsense D435) to measure the distance between the object and camera and then count the displacement between two frames. 
5. Using the data above to measure the speed of the objects.
