# ECE4200_Machine Learning Kaggle_Top2 Model
## Kaggle Leaderboard Rank: TOP 2  
Kaggle Leaderboard: https://www.kaggle.com/c/font-recognition/leaderboard  
  ![image](https://github.com/legendgp7/Font_Kaggle/blob/main/readme_img/Rank.png)
## Competition Description and Dataset
Overview: https://www.kaggle.com/c/font-recognition/overview  
Dataset: https://www.kaggle.com/c/font-recognition/data

## Jupyter Notebook & Short Report
The Jupyter notebook for the best model with the optimal data augment method is shown below:  
https://github.com/legendgp7/Font_Kaggle/blob/main/ECE4200_best_model_pg477.ipynb  
More details and corresponding discussion are available in the following short report:  
https://github.com/legendgp7/Font_Kaggle/blob/main/ECE4200_report_pg477.pdf

## Toolkits and Deployment

- Model:
  - [x] **XGBoost (best model - Accuracy: 94.88%)**
  - [x] Shallow Convolution Neural Network (Accuracy: 73.56%)
  - [x] 50-layer Residual Network (Accuracy: 83.73%)
  - [x] Mutiple Layer Proceptron (Accuracy: 63.82%)
  - [x] PCA + KNN (Accuracy: 64.74%)
  - [x] Logistic Regression (Accuracy: 46.40%)
  - [x] Naive Bayes (Accuracy: 33.02%)

- Data Augment :
  - [x] **Rotation + flip + contrast adjustment (best combination - Accuracy for XGBoost: 94.88%)**
  - [x] No data augmentation (baseline - Accuracy for XGBoost: 92.64%)
  - [x] Rotation + flip (Accuracy for XGBoost: 94.36%)
  - [x] Gaussian (Accuracy for XGBoost: 94.20%)
  - [x] Contrast adjustment (Accuracy for XGBoost: 93.93%)
  - [x] Rotation + flip + Gaussian (Accuracy for XGBoost: 94.74%)
  - [x] Contrast adjustment + Gaussian (Accuracy for XGBoost: 94.68%)
  - [x] Rotation + flip + Gaussian + contrast adjustment (Accuracy for XGBoost: 94.81%)
  
