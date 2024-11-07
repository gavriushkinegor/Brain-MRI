"""
This project achieved classifying brain MRA data within 4 classes: glioma, healthy, meningioma, pituitary.

Data pipelines were created to split the data into training, validation, and test sets. PyTorch was used to download a ResNet15 model with pretrained weights. The fully connected (FC) layer of the model was modified and trained specifically for these 4 classes using the images in the dataset.

The dataset can be loaded from [here](https://www.kaggle.com/datasets/rm1000/brain-tumor-mri-scans).
it can be then placed in "/raw_data" folder and the notebook will run as expected
"""
