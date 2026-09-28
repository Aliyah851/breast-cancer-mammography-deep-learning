# Deep Learning for Breast Cancer Detection in Mammography

The project contains two deep-learning pipelines:

1. **Mass Classification**: convolutional neural networks (CNNs) are used to classify pre-localized mammographic mass lesions as benign or malignant.
2. **Malignant Lesion Localization**: a U-Net segmentation model is used to predict the location of malignant mass lesions within full mammograms.

## Dataset

This project uses the **Curated Breast Imaging Subset of the Digital Database for Screening Mammography (CBIS-DDSM)**.

CBIS-DDSM contains:

- Full mammogram images
- Cropped mass images
- ROI segmentation masks
- Pathology labels
- Mammography metadata

The original dataset is provided by **The Cancer Imaging Archive (TCIA)**:

https://www.cancerimagingarchive.net/collection/cbis-ddsm/

For this implementation, the JPEG-formatted version of CBIS-DDSM can be downloaded from Kaggle:

https://www.kaggle.com/datasets/awsaf49/cbis-ddsm-breast-cancer-image-dataset

The Kaggle distribution contains the `csv` and `jpeg` folders used by this notebook.

The dataset itself is not included in this GitHub repository because of its size.
