# AMMI-2023-Computer-Vision-Labs-part-2
In this project, we will work with Detectron2 for Image segmentation and Key points estimation

In the first lab, we run a pre-trained model and use it on a set of images of our choice. We use the Mask R-CNN model with a ResNet-50-FPN backbone pre-trained on the COCO dataset for the tasks of object detection and instance segmentation. The dataset used is COCO dataset with ~120k images annotated with bounding boxes and object segmentation masks for 80 object categories. We test the model on some images downloaded online to check the performance. This is the link to the Jupyter Notebook: https://drive.google.com/file/d/1TQshwgbn1LVPKbD0DsJpyVf-XjMRHADr/view?usp=sharing

In the second lab, We use a dataset of nuts which has 3 classes: date, fig, and hazelnut, and which is annotated with instance masks (credit for the dataset to @Tony607)
You can dowload the dataset from: https://github.com/gkioxari/aims2020_visualrecognition/releases/download/v1.0/nuts.zip.
We train the model with two initialization schemes: With an existing model pre-trained on the COCO dataset, available in detectron2's model zoo and With ImageNet weights. 
We then compare the results of the two Initialization technique and found that the Initialization with the existing model pre-trained on the COCO dataset was the best.
This is the link to the Jupyter notebook: https://drive.google.com/file/d/1y_Ga6nZIcNt5vmiRP1C04JjNX6LboIbK/view?usp=sharing

In the third lab, we build an object tracker on images and videos using a small video clip of 41 frames from: https://github.com/gkioxari/aims2020_visualrecognition/releases/download/v1.0/videoclip.zip
Considering two types of matching scores: One where we consider that the predictions belong to the same object category and the second where we consider that the predictions belong to the same object category AND if their bounding box overlap is high.
This is the link to the jupyter notebook: https://drive.google.com/file/d/1dt1lp1i7An5f5sbD__X7zyQdlTL4u886/view?usp=sharing

