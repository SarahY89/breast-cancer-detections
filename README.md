# BREAST CANCER DIESEASE EARLY DETECTION USING DEEP LEARNING 
EARLY DETECTION OF BREAST CANCER USING CONVOLUTIONAL NEURAL NETWORK
Breast cancer is the most common form of cancer in women, and invasive ductal carcinoma (IDC) is the most common form of breast cancer. Accurately identifying and categorizing breast cancer subtypes is an important clinical task, and automated methods can be used to save time and reduce error.

The goal of this script is to identify IDC when it is present in otherwise unlabeled histopathology images. The dataset consists of approximately five thousand 50x50 pixel RGB digital images of H&E-stained breast histopathology samples that are labeled as either IDC or non-IDC. These numpy arrays are small patches that were extracted from digital images of breast tissue samples. The breast tissue contains many cells but only some of them are cancerous. Patches that are labeled "1" contain cells that are characteristic of invasive ductal carcinoma.

The code is divided into sections:

# BASIC EDA
DATA AUGUMENTATION
![image](https://github.com/SarahY89/breast-cancer-detections/assets/92030964/7f65a016-6f8c-4c85-bc73-165190c3101b)

A graphical Representation of the breast cancer image.
From the diagram the images recorded to be cancerous is 50.3% and the the non cancerous cell to be 49.7%
Data Augmentation will be performed on the cancerous image since we want to build a modle which can easily detect cancerous cell in any form 
![image](https://github.com/SarahY89/breast-cancer-detections/assets/92030964/39683234-0849-43b4-bc77-aca170ba352d)

The image above shows detailed information on augmented MRI images of cancerous cells in the breast.
This algorithm will help in getting a strong detection rate whenever in most critical cases we get images as such being captured by the MRI scans

A pie chart illustrating the nature of the dataset after augmentation
![image](https://github.com/SarahY89/breast-cancer-detections/assets/92030964/54c4be6c-1586-41dd-8bd5-1d48e3b1038c)


# Model Building
![image](https://github.com/SarahY89/breast-cancer-detections/assets/92030964/aeda938a-0d14-4162-9e6c-f459202b5dda)

The cnn model being trained with 20 epoch 
![image](https://github.com/SarahY89/breast-cancer-detections/assets/92030964/01ad41a8-4c3c-4c4c-8e87-90ccc284fe15)


# MODEL EVALUATION
![image](https://github.com/SarahY89/breast-cancer-detections/assets/92030964/63d243dd-048f-483c-ab5e-77f8089dcee5)

after the model is being trained , the detection rate is given as 0.77 which is 77% not bad 


# CONVOLUTIONAL MODEL WITH LAYERS
MODEL WITH LAYERS 35

![image](https://github.com/SarahY89/breast-cancer-detections/assets/92030964/3a1a0c97-efa4-480a-9145-eade4a109398)


