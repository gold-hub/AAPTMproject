# AAPTMproject
There are nine files in the project.
data. csv is the data obtained after encoding the original data for the experimental process. 
PCAtransform.xls is obtained by using principal component analysis method to transform data.csv from 31 dimension characteristic variables into 10 principal components, save as CSV format get PCAtransform. csv. This is a dataset used in the initial version of the paper, but not in this experiment, which will be reflected in the revised version of the paper.
4Classes-ROC-and-AUC-of-ANN-of-AAPTM.ipynb is a python file that uses the designed ANN to predict data.csv and PCAtransform2.csv, leaving PCAtransform.csv. At the same time, it also draws the ROC curve of the four classes and cross-validation of the coded data data.csv.
4Classes-ROC-and-AUC-of-ANN-after-PCA.ipynb is the drawing of the four-class ROC curve and cross-validation of PCAtransform2.csv data after dimension reduction by using the designed ANN.
4Classes-ROC-and-AUC-of-9 ML-of-AAPTM.ipynb is a python file that uses 9 ML models to make predictions for data.csv and PCAtransform2.csv, leaving PCAtransform.csv. At the same time, it also draws the ROC curve of the four classes and cross-validation of the coded data data.csv.
4Classes-ROC-and-AUC-of-9 ML-after-PCA.ipynb is the drawing of four classification ROC curves and cross-validation of PCAtransform2.csv data after dimension reduction by using 9 ML models.
