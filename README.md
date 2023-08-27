# YOLO-Underhood
In this repo , I will display you the underhood of YOLO algorithm it could be useful for making your object detection more precise and flexible.

Let's breakdown the steps: 
* 1. Your Deep-CNN yolo models take image as input and give you the emedding as output
* 2. We will now take this embedding and convert it to the best bounding box,scores and class name using some of our custom functions.

## Yolo filter boxes : It returns the filter boxes above the threshold from all H_image*W_image*anchor_box , IoU : It is a function used  in non-max suppression to remove boudning box above the IoU threshold.
![](https://github.com/Utshav-paudel/YOLO-Underhood/blob/2f3d8d689d127dcac43dd20cae44f3ca67f10ab3/Image/Yolo%20(1).png)
## Non-Max suppression : It select the most confidence bounding boxes among all the boxes.
![](https://github.com/Utshav-paudel/YOLO-Underhood/blob/2f3d8d689d127dcac43dd20cae44f3ca67f10ab3/Image/Yolo%20(2).png)
## Converting yolo model encoding to the bounding box, scores and class
![](https://github.com/Utshav-paudel/YOLO-Underhood/blob/2f3d8d689d127dcac43dd20cae44f3ca67f10ab3/Image/Yolo%20(3).png)
## Putting all together : Using above function to detect object from the image using pretrained model.
![](https://github.com/Utshav-paudel/YOLO-Underhood/blob/2f3d8d689d127dcac43dd20cae44f3ca67f10ab3/Image/Yolo%20(4).png)
