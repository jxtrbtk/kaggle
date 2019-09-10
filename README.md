# Kaggle
Work done for [Kaggle](http://www.kaggle.com) competitions. 

[>>> Kaggle profile](https://www.kaggle.com/jtbontinck)

## APTOS 2019 Blindness Detection
Detect diabetic retinopathy from retina images taken using fundus photography under a variety of imaging condition.
Ingredients : Pre-trained CNNs, Efficient-Net, Ordinal Regression, Pseudo Labelling (semi-supervised learning), Multiple training, Test Time Augmentation, trust your CV !

Public kernels : 
- [CNN/XGB - End-to-end (0.11)](https://www.kaggle.com/jtbontinck/cnn-xgb-end-to-end-0-11) : re-train a pretrained DenseNet 161 on competition data (5 folds), extract features and then use XBG for prediction + TTA (x2)
- [CNN/XGB - End-to-end (1.54)](https://www.kaggle.com/jtbontinck/cnn-xgb-end-to-end-1-54) : re-train a pretrained DenseNet 161 on **extrenal+competition** data, fine tune training on competition data only, extract features for XBG for prediction, blend CNN and XGB results + TTA on CNN (x4) - The final score = 0.910, corresponds to 758/798 leaderboard positions. There is an overlap between the first phase training data and the second one, so I did not select this kernel as a final submission as the CV was not correct, unfortunately)

## LANL-Earthquake-Prediction [>>>](https://github.com/jxtrbtk/kaggle/tree/master/LANL-Earthquake-Prediction)
Forecasting earthquakes for Los Alamos Nationl Laboratory.

I've used this dataset for the capstone project of the IBM Coursera certified specialization "Advanced Data Science with IBM".
All the work has been done following a methodology (the Lightweight IBM Cloud Garage Method for Data Science) and I've published the following parts : 
- Initial Data exploration
- ETL
- Features Engineering
- Model Definition

One of the interest of the project was to use the **Apache Spark** service of the IBM cloud.

The presentation of the capstone project is available on [Youtube](https://youtu.be/okrR7Krd9z4).

