# Brain Tumor Diagnosis using Deep Learning

**Dataset used:** https://figshare.com/articles/brain_tumor_dataset/1512427

**Model used:** AlexNet

**Trained on:** Google Collab


## Problem Statement

Building a deep learning model which can identify which kind of tumor exists in the brain.
The model is supposed to classify between: Meningloma, Glioma and Pitutary Tumors.

## Dataset

Form the dataset mentioned above, we are using 2440 images as training set and rest 660 images as validation set. The dataset consists of 708 images for Meningloma,
1146 images for Glioma and 915 images for Pitutary Tumor. Also, the images are of three different views: Sagittal, Axial and Coronal. We have to train a model that
can detect tumors accurately despite the views.

## Solution

Our model is an implementation of AlexNet with 3 convolutoin layers and then 3 fully connected layers, as mentioned below:

![Alexnet Model used](https://github.com/namanbansalcodes/Brain-Tumor-Diagnosis-using-Deep-Learning/blob/master/TIP%20model.JPG?raw=true)!


## How to run

Tensorflow, Numpy, h5py, Matplotlib.pyplot, os and cv2

1. Download the dataset to your google drive, unzip all folders and store them in one folder. (you can do this easily using https://www.multcloud.com/)
2. Open the notebook in Google Collab.
3. Mount Google Drive.
4. Do ya thing!
5. Hit me up on namanbansalcodes@gmail.com, let's talk.

OR

1. Add my pickle file to your drive using this link: https://drive.google.com/file/d/1IKvwqGRjZajEf78I41j2VOdv_ztsQl6R/view?usp=sharing
2. Open the notebook in Google Collab.
3. Mount google drive and run the block that says load pickle file.
4. Do ya thing!
5. Enlighten me please.

## Conclusion

When trained on 20 epochs with a batch size of 32, the training accuracy is 0.93 based on Sparse_Categorical_CrossEntropy loss function and
the model achieves a validation accuracy of 0.89 and a loss of around 0.23.

Please help me imporve the results.
