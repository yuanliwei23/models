*******************************************************************************
Model Path Description:
```
computer_vision
   |-- classification
       |-- {scene_name}
            |--{scene_name}.om
            |--README.md
   |-- object_detect
   |-- segmentation
```
Scene Name: Om file Name and upper directory name should be scenes to be used.
*******************************************************************************

Original Network Link:
https://github.com/soeaver/caffe-model/blob/master/cls/dpn/deploy_dpn98.prototxt

Pre-trained Model Link:
https://pan.baidu.com/s/1pKHBRlD#list/path=%2F

Input Description:
The input image should be resized to 224*224 pixels, and padding to 256*224 pixels, YUV420SP_U8.

Output Description:
The pre-trained model is trained for image recognition, and its results follow 1000 lables of ImageNet.

Custom Operator:
Custom operator is included or not: No


Tested Version List:
-Atlas 200
