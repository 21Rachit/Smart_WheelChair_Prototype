# Smart_WheelChair_Prototype
WORKFLOW:

The smart wheelchair will be controlled by the hand gesture movement of the patient so the manual task of rotating it by hand will be reduced. 

The technology used is rfid sensor and accelerometer and other electronic components.

Then we have used object detection algorithm to identify the objects present in front of the webcam attached to the wheelchair. 

We have used tensorflow module and coco dataset to train our model. 

We can also detect the type of object present (like temperature,humidity) using different sensors.

If the object is detected, the wheelchair has to avoid the obstacle and move to the safest path all by itself.

(this we have achieved by using ultrasonic sensors and servo motors attached to raspberry pie since coding in python was easy)

Then final part was locating the position of the patient. This can be done by anyone sitting far away from the hospital using a single click. 

(for this we have used the technology of web automation using uipath tool. It automatically connects to the google map or track patient ip address to collect his address.)
