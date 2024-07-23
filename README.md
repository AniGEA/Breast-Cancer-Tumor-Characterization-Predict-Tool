![P (3)](https://github.com/user-attachments/assets/f49ff719-4ad9-47e9-aff1-ce9f7ae2e75e)


**Introduction**
The objective of this project is to analyze the breast cancer dataset supplied by the University of Wisconsin, Madison, and identify a suitable machine learning algorithm to predict diagnoses based on pre-recorded data. The attributes of this dataset are computed from digitized images of fine needle aspirates (FNA) of breast masses. The dataset was donated to the University of Wisconsin in 1995.

**Key Attributes**
+ Diagnosis: (M = malignant, B = benign) - This is our target variable.
+ Radius: Mean of distances from center to points on the perimeter
+ Texture: Standard deviation of gray-scale values
+ Perimeter
+ Area
+ Smoothness: Local variation in radius lengths
+ Compactness: Perimeter² / area - 1.0
+ Concavity: Severity of concave portions of the contour
+ Concave points: Number of concave portions of the contour
+ Symmetry
+ Fractal dimension: "Coastline approximation" - 1
  
Note: The ID column is excluded from the analysis as it is used only for identification.

**Breast Cancer Overview**
According to the American Cancer Society, breast cancer occurs when cells in the breast grow uncontrollably. These cells often form a tumor that can be detected via an x-ray or felt as a lump. The tumor is considered malignant (cancerous) if the cells can invade surrounding tissues or spread to other parts of the body. While breast cancer primarily affects women, men can also develop the disease.

**Signs and Symptoms**
The most common symptom of breast cancer is a new lump or mass. A painless, hard mass with irregular edges is more likely to be cancerous, although breast cancers can also be tender, soft, or rounded, and can even be painful. It is crucial to have any new breast mass or lump or any change in the breast checked by a healthcare provider experienced in diagnosing breast diseases.

**Dataset Application**
The dataset contains diagnoses of lumps and masses found in patients, classifying them as either malignant (denoted by 'M') or benign (denoted by 'B'). This project will use these classifications to train and evaluate machine learning models, aiming to accurately predict the diagnosis based on the provided attributes.

**Model Performance**
In this project, various machine learning algorithms were evaluated, including:
+ **Neural Network Model: Achieved an accuracy of 99%.**
+ **Support Vector Machine (SVM) Model: Achieved an accuracy of 97%.**
For the SVM model, we explored several less optimal versions before finalizing the optimized version that delivered the best performance.
