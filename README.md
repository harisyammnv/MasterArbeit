# Master Thesis 
**Topic - Development of Robust Machine Learning Algorithms to deal with Noise and Skewness in very Large Datasets**

## Introduction
This Repository contains exemplary Notebooks where I had applied similar methods to the real datasets i have worked with in my thesis. These notebooks illustrate how important it is to deal with skewness and noise in datasets.

## Dealing with Noise and Skewness in the data
**Imbalanced Learning in the presence of annotation noise can be dealt in 2 ways as follows:**

**Method-1 : Noise Models Using Neural Networks with Noise Treatment Layers**
![Network Architecture](https://github.com/harisyammnv/MasterArbeit/blob/master/Noise_models.png)

**Method-2: Denoising Auto encoder + MLP with Noise Treatment Layer**
![dnn result](https://github.com/harisyammnv/MasterArbeit/blob/master/dnn_auto.PNG)

## Exemplary Results
- Imbalanced Learning in Small Datasets
  - [Diabetes Dataset Notebook](https://github.com/harisyammnv/MasterArbeit/blob/master/Imbalanced_learning_and_noise_layer_Diabetes_dataset.ipynb)
  - **Best Result:**![Best Result](https://github.com/harisyammnv/MasterArbeit/blob/master/RF_diabetes.png)
 
- Imbalanced Learning in Medium Size Datasets
  - [Credit Card Notebook](https://github.com/harisyammnv/MasterArbeit/blob/master/Imbalanced_learning_and_noise_layer_Credit_Card_Dataset_V2.ipynb)
  - **Best Result:**![Best Result](https://github.com/harisyammnv/MasterArbeit/blob/master/XGBoost_credit_card.PNG)
  
- Imbalanced Learning in Large Datasets
  - [Forest CoverType Notebook](https://github.com/harisyammnv/MasterArbeit/blob/master/Imbalanced_learning_and_noise_layer_forest_cover_type_dataset.ipynb)
  - **Results 1:** ![Best Result1](https://github.com/harisyammnv/MasterArbeit/blob/master/cnf_cover_type.png)
  - **Results 2:** ![Best Result2](https://github.com/harisyammnv/MasterArbeit/blob/master/results_cover_typr.png)
  
## Dealing with Noise in the data using Noise Treatment Layers

For the forest covertype dataset these above models are applied and the results are as follows:

**NAR Model Result:** 20% Label Noise treated with 5-layer neural network with simple noise layer
![NAR result](https://github.com/harisyammnv/MasterArbeit/blob/master/cnf_nar_model.png)

**NNAR Model Result:** 20% Label+Feature Noise treated with 5-layer neural network with compound noise layer
![NNAR result](https://github.com/harisyammnv/MasterArbeit/blob/master/cnf_nnar_model.png)


  
 
 
 
 
  
 
 
 
 
