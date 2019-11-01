# Parkinsons-PredictiveModel-Using-Spiral-Drawings
Image Classification project  to predict Parkinson's Disease on images of spiral drawings

Current accuracy score: 95% - 10/31/2019

Uses Keras for image processing and CNN for feature extractions

DATASET: https://archive.ics.uci.edu/ml/datasets/Parkinson+Disease+Spiral+Drawings+Using+Digitized+Graphics+Tablet

The dataset is composed of very little amount of images so to avoid underfitting, I created a scipt on using keras to create 20 images of 1 picture
in different rotations and sizes. After doing this for every picture in the original dataset, my new dataset was composed of 2000+ images. 1500+ on the training set, and 650+ on the testing set.
*The script is not included in the notebook file.*
