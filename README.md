# Face Distance Measurement 

![Face distance Measurement](./img/distance.png)

As you can see in the image we'll try to tell the distance of our face from the camera using computer vision, using the openCV library.
## Libraries 
1. openCV
2. cvzone (<u>optional: it already has some pre-build classes to detect the face and calculate the distance between two point, stack images together etc.</u>)
3. Numpy

## Approach 
![](img/formula.png)
Here we have used the concept of basic pinhole camera to first find the focal length of the our webcam first then use it to find the depth in quetion.<br>
And we've used <u>*our eyes*</u> as reference because even though the face features vary from person to person but the distance between the eyes is almost same at about 6.3cm avg for both men and women.

# DynamicTextReader 
