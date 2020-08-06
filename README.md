# Face Mask Detection ![](https://visitor-badge.laobi.icu/badge?page_id=akash720.face-mask-detection.readme)
Detecting face masks using deep learning 

### Description
This project aims at using transfer learning on pretrained model for detecting face with masks on them. The model used is ResNet50 which is available in PyTorch. To test the model, first we find ROI in the image which is **face** . Then we pass this ROI to our model to detect if face is covered with mask or not.

### Dependencies
* PyTorch
* OpenCV

### Dataset
The dataset used in this project can be found here - https://github.com/prajnasb/observations with some of my own images and their augmented images.

### Future Work
There's always room for improvement. In this project, we can further detect if the faces are fully covered by mask or not. It is beneficial to do so because improper use of mask may decrease it's efficiency.
