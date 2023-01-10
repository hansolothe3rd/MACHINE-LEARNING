# Sloan Digital Sky Survey DR16
## Analyzing Sloan Digital Sky Survey DR16 Data And Making Predictions

**Daniel Barella**:

### Within all of this photometric data, and spectal data, a class object (galaxy, star or quasar object) can be predicted.:

### Data Source:
- https://www.kaggle.com/datasets/muhakabartay/sloan-digital-sky-survey-dr16

### License: 
- Creative Commons Attribution license ([CC-BY](https://creativecommons.org/licenses/by-sa/4.0/))

## To prepare this data, the data was cleaned, and the following processes were performed:

### Exploratory Data Analysis
    - During the exploratory data analysis, a boxplot and histogram was visualized.
    - Also, a heatmap was produced.
    - This helped visualize what was correlated.

 ### Expanatory Data Analysis
    - To visualize the data for explantory purposes, a scatterplot, and a bargraph were created.

## Maching Learning Using the Following Models:
    - KNN
    - RandomForestClassifier
    - PCA

## Results

My final model is the Random Forest Classifier Model. After running a KNN model and the RFC, the RFC was better. After running PCA on both models, the RFC without the PCA still performed better.
I believe this model is ready for production, as it could identify our target with 99% accuracy. This would help astronomers identify the target with speed and accuracy.

## Random Forest Classifier Model

Classification Report for Random Forest Classifier Testing Set

              precision    recall  f1-score   support

           0       0.99      0.99      0.99     12872
           1       0.98      0.94      0.96      2590
           2       1.00      1.00      1.00      9538

    accuracy                           0.99     25000
   macro avg       0.99      0.98      0.98     25000
weighted avg       0.99      0.99      0.99     25000

For any additional questions, 
please contact 
**Daniel Barella**
**hansolothe3rd@hotmail.com**