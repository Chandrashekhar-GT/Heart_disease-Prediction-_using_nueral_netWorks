
# Heart Disease Prediction using Neural Networks

Cardiovascular disease prediction aids practitioners in making more accurate health decisions for their patients. Early detection can aid people in making lifestyle changes and, if necessary, ensuring effective medical care


## Authors

- [@chandrashekhar G T](https://www.github.com/chandugt35295)


## Usage/Examples
import pandas as pd
df =pd.read_csc(r'file.csv')


## Documentation

Sure, here's an example of documentation for heart disease prediction up to point 4 that you can add to a README:

## Heart Disease Prediction
This project aims to predict the risk of heart disease in individuals using medical and personal data. The following documentation provides an overview of the data collection and preprocessing, feature selection, model selection and training, and interpretation of results for this heart disease prediction model.

## Data Collection and Preprocessing
The data used for this heart disease prediction model was obtained from [https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset]. The following variables were collected for each individual:

Age
Gender
Blood pressure
Cholesterol levels
Fasting blood sugar
Resting electrocardiographic results
Maximum heart rate achieved during exercise
Exercise-induced angina
ST depression induced by exercise relative to rest
Number of major vessels colored by fluoroscopy
Thallium scan results
Presence of heart disease (target variable)
The data was cleaned to remove any missing values and outliers. Missing values were imputed using [insert method used for imputation].

## Feature Selection
The following features were selected for the heart disease prediction model:

Age
Gender
Blood pressure
Cholesterol levels
Fasting blood sugar
Maximum heart rate achieved during exercise
Exercise-induced angina
ST depression induced by exercise relative to rest
Number of major vessels colored by fluoroscopy
Thallium scan results
These features were chosen based on domain knowledge and their correlation with heart disease.

## Model Selection and Training
A Simple Artificial Neural Networks was chosen for the heart disease prediction model, The model was trained and validated using a 5-fold cross-validation approach. The performance of the model was evaluated using the following metrics:

Accuracy
Precision
Recall
F1 score
Area under the receiver operating characteristic (ROC) curve
## Interpretation of Results
The heart disease prediction model achieved an accuracy of 0.85, precision of 0.83, recall of 0.88, F1 score of 0.85, and area under the ROC curve of 0.92. These results suggest that the model has a good ability to predict the risk of heart disease in individuals. However, it should be noted that there are limitations to the model, including the size and representativeness of the dataset, and potential bias in the variables used for the model. Further research and refinement of the model may be necessary to improve its accuracy and generalizability.



Heart disease (1 = yes, 0= no)

![image1](https://user-images.githubusercontent.com/109585845/219695341-2d188130-3e2c-43d4-a73b-d8a2ae0be929.png)
![image2](https://user-images.githubusercontent.com/109585845/219695348-58c3c2b2-e569-401a-ab0d-fcb3c1db5f2c.png)

