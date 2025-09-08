# mnist-sklearn
A Python project that trains and evaluates machine learning models on the MNIST handwritten digit dataset using scikit-learn **(KNeighborsClassifier)** .

This project demonstrates:

1.Loading and preprocessing the  **MNIST dataset**

2.Hyperparameter tuning with  **GridSearchCV**

3.Model evaluation using  **cross-validation, precision, recall, and confusion matrix**

4.Saving and loading trained models with  **joblib**

## Requirments 

- Python 3.10.x 
- Dependencies listed in `requirements.txt`:

## How to run 
### 1. Create a virtual environment (Python 3.10.x)
```bash python.exe -m venv venv ``` 
### 2. Activate the virtual environment (Windows)
``` .\venv\Scripts\activate ``` 
### 3. Install dependencies
``` pip install -r requirements.txt ``` 
### 4. Run the training script
``` jupyter notebook Training.ipynb ``` 

## To test the model
**Open the prediction notebook**
``` jupyter notebook Prediction.ipynb ``` 
## Model PreTrain
- https://drive.google.com/file/d/1f3lWElUTtKNCoXelp1W7TliVfSdb7taw/view?usp=sharing
# Source
## 1. Dataset 
The MNIST dataset is fetched via [OpenML](https://www.openml.org/d/554) using `sklearn.datasets.fetch_openml`.
## 2. Libary
  - scikit-learn
  - matplotlib
  - numpy
  - pandas
## Acknowledgements
This project was inspired by the book:
- *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow* by Aurélien Géron
