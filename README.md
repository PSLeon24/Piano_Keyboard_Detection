# Piano_Keyboard_Detection
### Description
The piano keyboard detection is an object detection task that detects keyboard on a piano in pictures or videos. This repository includes a demo for building the keyboard detector using YOLOv5 model and SSD-MobileNet model.

### Models
* <b>YOLOv5 model</b><br>
  to be added!<br>
* <b>SSD model</b><br>
  * <a href="https://github.com/PSLeon24/Piano_Keyboard_Detection/blob/main/SSD-MobileNet/">Go this project</a><br>
  → It is important to structure your directories strictly by following the guidelines well for this model.
 
# Data

### Dataset
We collected 2,605 images from divided in 5 technique related videos and we trained these data.<br>
The class is defined as follow:<br>
* keyboard
 
### Data Collection
We collected data in a variety of ways.<br>
1. We collected 2,605 images from related videos divided in five classes using OpenPose.(fps: 30)<br>

2. We collected about 10 images by searching "playing piano" in google. <br>
#### Data Labeling
##### 1. YOLOv5
We used DarkLabel(Data Labeling Program operating in a Windows environment)
* You can download DarkLabel in Github (https://github.com/darkpgmr/DarkLabel)<br>
* We labeled data following this file. => [DarkLabel.pdf](https://github.com/PSLeon24/Piano_Keyboard_Detection/files/12312493/DarkLabel.pdf) <br>
![label_images](https://github.com/PSLeon24/Piano_Keyboard_Detection/assets/59058869/f3e197ea-039c-4f82-a60c-8f515d4bd32a)
##### 2. SSD-MobileNet
We converted labeled data for YOLOv5 to Pascal VOC data. Then we converted Pascal VOC data to csv files to make tfrecord files.
![ssd](https://github.com/PSLeon24/Piano_Keyboard_Detection/assets/59058869/b9bc7ebc-804f-46fb-8d2e-0428894988cb)
