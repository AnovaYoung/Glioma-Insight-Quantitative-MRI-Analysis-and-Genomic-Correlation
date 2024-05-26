# Glioma Insight: Quantitative MRI Analysis and Genomic Correlation (Ongoing)

**Dataset Overview:**
The dataset consists of brain MRI images from patients diagnosed with lower-grade glioma. These images include manually created segmentation masks that highlight FLAIR abnormalities associated with the glioma. The dataset is derived from a larger collection housed in The Cancer Genome Atlas (TCGA) and has been utilized in research exploring the association between tumor genomic subtypes and morphological features extracted through deep learning algorithms. The MRI images are in `.tif` format, and each image has a corresponding segmentation mask indicating the region of interest (abnormal tissue).

**Project Goals:**
The primary objective of the project is to analyze the MRI images and segmentation masks to extract meaningful information that can potentially be correlated with patient data and genomic subtypes. The analyses include:

1. **Quantitative Analysis:** Calculating the area and estimated volume of the tumors using the segmentation masks.

2. **Feature Extraction:** Deriving shape and texture features from the tumor regions in the MRI images.

3. **Data Visualization:** Creating visual representations of the data for better understanding and communication of the findings.

4. **Statistical Analysis:** Performing statistical tests and correlations between extracted image features and clinical data to identify significant patterns or associations.

5. **Predictive Modeling:** (Potentially) Building predictive models to classify MRIs based on features or predict clinical outcomes.

**Progress So Far:**
I've successfully set up an R environment to handle image data, installed necessary image processing packages (like `EBImage`), and confirmed the ability to read and display MRI images and their associated masks. The next steps include quantitative analysis of the masks, feature extraction from the images.

This project stands at the intersection of image processing, data science, and medical research, aiming to leverage computational techniques to gain insights into medical imaging data and contribute to the understanding of glioma characteristics.
