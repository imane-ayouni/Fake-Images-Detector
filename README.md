# Fake-Images-Detector
## Topic:
In this project, I will be going through many real people pictures and fake photoshop made pictures, using dimensionality reduction technique, more specifically PCA, reduce the dimendion of the pictures and then apply classification algorithms on them. The row pictures are downloaded and transformed into arrays, only one color channel is kept with the values at each pixel stored into an array, PCA is then apply twice, first time to reduce the photo matrices into their 3 principal components and second to reduce those 3 components in to one principal components which contains 50% of the information in the picture. Different classification algorithms are then applied on the decomposed matrices to try and predict whether a certain picture is real or fake.

## Models :
- Logistic Regression
- Naive Bayes Classifier
- Decision Tree Classifier
- XGBoost Classifier
- Support Vector Machines
- K Nearest Neighbour


## Evaluation Matrices:
- Accuracy
- F1 score

## Libraries
- os
- numpy
- Pandas
- Sklearn
- MatPlotLib

## Data source
https://www.kaggle.com/datasets/ciplab/real-and-fake-face-detection
