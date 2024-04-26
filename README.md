# Prediction-of-Meningioma-Grade
This is a coursework which aim is to predict grade of meningioma patients from radiomic features extracted from MRI scan

## Introduction
- Meningioma is the most common primary brain tumour, and, according to the World Health Organisation criteria, it can be classified as grade I, II or III. Grade I is benign, grade II is atypical, and grade III is anaplastic.
- This coursework aims to utilise machine learning to predict the grade of meningioma based on radiomics features.
- The radiomics features are extracted from pre-operative MRI scans (MRIs were collected from The Cancer Imaging Archive (TCIA), a publicly available dataset at https://www.cancerimagingarchive.net/collection/meningioma-seg-class/ under the restricted license agreement).
- The dataset comprises a cohort of 94 patients diagnosed with meningioma between 2010 and 2019. Grade I and Grade II meningiomas were identified according to the 2016 WHO classification guidelines, and Grade III cases were excluded due to their rare occurrence.
- The column named "Target" specifies the meningioma grade. The remaining columns represent radiomics features extracted from the MRI scans.



## Outline of the python codes

- Preliminary Data Analysis
- Data Standardization
- Feature Selection
- Model Training and Evaluation
- Hyperparameter Tuning
- Model Re-evaluation
- Comparing Models

## Conclusion

- We utilised machine learning to predict the grade of meningioma based on radiomics features.
- Three classification models; SVM, logistic regression, and random forest classifiers were developed.
- Of the three models, logistic regression model gives the best performance in terms of the metrics evaluated.
