# Titanic-Disaster-Classification
This is the repository for the source code of the titanic disaster prediction and analysis using statistical and machine learning methods project found on https://www.kaggle.com/competitions/titanic You can find a notebook here as well https://www.kaggle.com/code/alinaageichik/eda-ml-models-and-ensemble  
## Dependencies (Anaconda):  

Scikit-learn 1.1.0 (`conda install -c conda-forge scikit-learn`)  

Scipy 1.8.1 (`conda install -c conda-forge scipy`)  

Numpy 1.23.1 (`conda install -c conda-forge numpy`)  

Matplotlib 3.5.2 (`conda install -c conda-forge matplotlib`)  

Seaborn 0.11.2 (`conda install -c conda-forge seaborn`)  

Pandas 1.4.3 (`conda install -c conda-forge pandas`)    

This project is implemented using Python 3.8.5.

## Results:  

| Model | Accuracy (%) | 
| --- | --- |  
| Random Forest | 88.01 |
| Perceptron | 71.79 |  
| Support Vector Machines | 81.38 | 
| Linear Support Vector Machines | 80.25 | 
| K-Nearest-Neighbours | 83.36 | 
| Stochastic Gradient Descent | 79.69 | 
| Decision Tree | 99.44 | 
| Gaussian Naive Bayes | 78.42 | 
| Logistic Regression | 80.39 |
| Ensemble (LR + DT + SGD + KNN + RF ) | 91.68 |

Prediction (submission) accuracy in Kaggle is 77.27%.
