# Project 2. Mask Detection

### Project description
Object detection problem with transfer learning of the two popular models: Faster R-CNN and YOLOv8. The dataset is hardly imbalanced (3% and 18% for the minor classes against the 79% of the major class).

### The case    

* object detection with Faster R-CNN
* object detection with YOLO version 8
* work with hardly imbalanced data
* calculation of the mAP metric over a dataset
* visualisation of the images with bounding boxes
* visualization of the training process

**Skillfactory requirements:**  
* Data are loaded with a DataLoader
* A pretrained model is used, the choice of the model is explained
* Detectores from the R-CNN and YOLO families are used 
* The training is made with the training sample
* Average precision on the validation sample for the two detectors is > 0.85
* The results are visualized
* The code is readable and understandable, comments are added

### The data
The project is based on the Kaggle [Face Mask Detection](https://www.kaggle.com/datasets/andrewmvd/face-mask-detection) dataset. Three classes are presented: with mask (79%), without mask (18%), mask weared incorrectly (3%).
