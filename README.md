# Chickoo Counting using MobileNet

- I have developed a model for detecting chickoo fruit using MobileNet pretrained model
- First, I collected chickoo fruit and labled the image using lxml
- Then I trained the data on [ssd_mobilenet_v2_fpnlite_640x640_coco17_tpu-8](http://download.tensorflow.org/models/object_detection/tf2/20200711/ssd_mobilenet_v2_fpnlite_640x640_coco17_tpu-8.tar.gz) pretrained model
- While training we save the checkpoints and from that latest checkpoint we can detect and count chickoo fruits

## Preview of object detection and counting
  ![image](https://github.com/Harshith1234567/ChickooCount/assets/53342028/a8e2832d-c89f-47a0-8200-e75330c3caaf)


## Important Data Regarding the project

[Image dataset](https://drive.google.com/file/d/1HS0Xo2he28iFAKGdNGnMeDPNKQMkl_nC/view?usp=sharing)

[Trained model](https://drive.google.com/file/d/1Qh61c83atZcvykmk1Ar3OXB7O839zM4s/view?usp=sharing)


