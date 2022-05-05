# Infant-Early-Detection
This is a study with NYS Institute of Infant Developmental. The aim was to use machine learning for early identification of infants who would be delayed at 25 months. 

We used ML to predict moderate delay (score <85) on the 25-month Bayley Scales of Infant Development (BSID-II) among 1154 infants (estimated gestational age ≤ 33 wks). 32% (mental) and 42% (motor) of infants were delayed. Random Forest Classifiers were trained on 80% of the dataset and tested on the remainder. Before training the ML model, the Synthetic Minority Oversampling Technique (SMOTE) was applied to create augmented data for the minority (delayed) class. Sparse data due to missed tests and changed data collection protocols across time posed an additional challenge. MissForest, a non-parametric missing value imputation technique based on Random Forest, was used to handle this. Our first model included only at-birth predictors. Aiming to improve model precision, each subsequent model added another post-neonatal predictor (one-month Rapid Neonatal Neurobehavioral Assessment, followed by 16 month BSID-II).

<img src="https://github.com/gozdedemirci/Infant-Early-Detection/blob/main/2.svg">

The study was accepted from 2022 APS Annual Convention in poster session. 


