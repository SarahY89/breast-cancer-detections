# breast-cancer-detections
EARLY DETECTION OF BREAST CANCER USING CONVOLUTIONAL NEURAL NETWORK
Breast cancer is the most common form of cancer in women, and invasive ductal carcinoma (IDC) is the most common form of breast cancer. Accurately identifying and categorizing breast cancer subtypes is an important clinical task, and automated methods can be used to save time and reduce error.

The goal of this script is to identify IDC when it is present in otherwise unlabeled histopathology images. The dataset consists of approximately five thousand 50x50 pixel RGB digital images of H&E-stained breast histopathology samples that are labeled as either IDC or non-IDC. These numpy arrays are small patches that were extracted from digital images of breast tissue samples. The breast tissue contains many cells but only some of them are cancerous. Patches that are labeled "1" contain cells that are characteristic of invasive ductal carcinoma.

The code is divided into sections:

BASIC EDA,

DATA AUGUMENTATION,

CLASSIFICATION,

MODEL EVALUATION,

MODEL WITH LAYERS ,

CONVOLUTIONAL MODEL WITH LAYERS,

TRANSFERRED LEARNING (VGG 19),

VGG 19 MODEL EVALUATION,

CONFUSION METRICS

