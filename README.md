# Breast-Cancer-Detection
One very interesting application area of machine learning is in making medical diagnoses. In this project I will train and test a decision tree to detect breast cancer using real world data. I will use the Wisconsin Diagnostic Breast Cancer (WDBC) dataset.
# About the dataset
The dataset consists of 569
samples of biopsied tissue. The tissue for each sample is imaged and 10 characteristics of the nuclei of
cells presenting each image are characterized. These characteristics are
(1) Radius
(2) Texture
(3) Perimeter
(4) Area
(5) Smoothness
(6) Compactness
(7) Concavity
(8) Number of concave portions of contour
(9) Symmetry
(10) Fractal dimension
Each of the 569 samples used in the dataset consists of a feature vector of length 30. The first 10
entries in this feature vector are the mean of the characteristics listed above for each image. The
second 10 are the standard deviation and last 10 are the largest value of each of these characteristics
present in each image. Each sample is also associated with a label. A label of value 1 indicates the
sample was for malignant (cancerous) tissue. A label of value 0 indicates the sample was for benign tissue.
This dataset has already been broken up into training and test sets for you and is available on blackboard.
The names of the files are \trainX.csv", \trainY.csv", \testX.csv" and \testY.csv." The file names ending
in \X.csv" contain feature vectors and those ending in \Y.csv" contain labels. Each file is in comma
separated value format where each row represents a sample.
