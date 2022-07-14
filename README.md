# Distinguish between the presence and absence of cardiac arrhythmia and classify in 16 groups

This database contains 279 attributes, 206 of which are linear valued and the rest are nominal. 
Concerning the study of H. Altay Guvenir: "The aim is to distinguish between the presence and absence of cardiac arrhythmia and to classify it in one of the 16 groups. Class 01 refers to 'normal' ECG classes 02 to 15 refers to different classes of arrhythmia and class 16 refers to the rest of unclassified ones. For the time being, there exists a computer program that makes such a classification. However there are differences between the cardiolog's and the programs classification. Taking the cardiolog's as a gold standard we aim to minimise this difference by means of machine learning tools." 
The names and id numbers of the patients were recently removed from the database. 

# Preprocessing
We use l2 Normalization in our dataset

# Datasize
We split data into 70% train data and 30% test data.

# Model
We have used several models like Multi layer perceptron, Decision Tree, Random Forest, Support Vector Machine(SVM), KNeighborsClassifier.
Among all of these SVM gives the best result with 79.4% of Accuracy.

# Dataset Source:
http://archive.ics.uci.edu/ml/datasets/arrhythmia

# Relevent Pappers
http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=4488483
http://cs229.stanford.edu/proj2014/Vasu%20Gupta,%20Sharan%20Srinivasan,%20Sneha%20Kudli,%20Prediction%20and%20Classification%20of%20Cardiac%20Arrhythmia.pdf

# Authors
<a href="https://github.com/Chahes" target='_blank'>Chahes Chopra</a>, <a href="https://github.com/19shubham" target='_blank'>Shubham Jaroli</a>, <a href="https://github.com/shivam04" target='_blank'>Shivam Sinha</a>
