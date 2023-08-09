# BREAST CANCER DIESEASE EARLY DETECTION USING DEEP LEARNING 
EARLY DETECTION OF BREAST CANCER USING CONVOLUTIONAL NEURAL NETWORK
Breast cancer is the most common form of cancer in women, and invasive ductal carcinoma (IDC) is the most common form of breast cancer. Accurately identifying and categorizing breast cancer subtypes is an important clinical task, and automated methods can be used to save time and reduce error.

The goal of this script is to identify IDC when it is present in otherwise unlabeled histopathology images. The dataset consists of approximately five thousand 50x50 pixel RGB digital images of H&E-stained breast histopathology samples that are labeled as either IDC or non-IDC. These numpy arrays are small patches that were extracted from digital images of breast tissue samples. The breast tissue contains many cells but only some of them are cancerous. Patches that are labeled "1" contain cells that are characteristic of invasive ductal carcinoma.

The code is divided into sections:

# BASIC EDA


# DATA AUGUMENTATION
![image](https://github.com/SarahY89/breast-cancer-detections/assets/92030964/7f65a016-6f8c-4c85-bc73-165190c3101b)

A graphical Representation of the breast cancer image.
From the diagram the images recorded to be cancerous is 50.3% and the the non cancerous cell to be 49.7%
Data Augmentation will be performed on the cancerous image since we want to build a modle which can easily detect cancerous cell in any form 
![image](https://github.com/SarahY89/breast-cancer-detections/assets/92030964/39683234-0849-43b4-bc77-aca170ba352d)

The image above shows detailed information on augmented MRI images of cancerous cells in the breast.
This algorithm will help in getting a strong detection rate whenever in most critical cases we get images as such being captured by the MRI scans

# CLASSIFICATION


# MODEL EVALUATION


# MODEL WITH LAYERS 


# CONVOLUTIONAL MODEL WITH LAYERS


# TRANSFERRED LEARNING (VGG 19)


# VGG 19 MODEL EVALUATION


# CONFUSION METRICS

