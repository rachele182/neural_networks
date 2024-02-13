### <font color="green"> <span style="font-size:larger;"> Convolutional Neural Networks Project </font> </span>
<font color="green">**Authors**:</font>  Rachele Nebbia Colomba, Alessandro Gentili, Giorgio Simonini  
<font color="green">**Title**: Abnormality Detection in Mammography using Deep Neural Networks </font> 

This repository contains the code and of results obtained on mammography classification using **Convolutional Neural Network (CNN)** developed during Master Course at the Department of Engineering, Universita´di Pisa.  
The Neural Networks were designed using TensorFlow on _Keras_ environment.  
The data-set used in our project is **CBIS DDSM**, a Curated Breast Imaging Subsetof Digital Database for Screening Mammography.  
It represents a collection of images from two classes of breast abnormalities: masses and calcifications.  
Class labels are assigned according to the following mapping:  
1. Baseline patch (benign tissue patch adiacent to the abnormality)
2. Benign Mass
2. Malignant Mass
3. Benign Calcification
4. Malignant Calcification

Below an histogram representing the data-set distribution according to the described classes:

<img src="https://github.com/rachele182/Master-Thesis/assets/75611841/e5707776-c1b3-46db-b5bc-41e4127572b3" width="385">

The work is organized two main sections:  

&#x1F538; **binary classification**: to classify abnormalities between mass and calcification
  - from scratch CNN,
  - pre-trained CNN,
  - two-channel CNN using baseline patches (to pair in the NN bening tissue with corrispondent malign one)

&#x1F538; **four classes classification**: to discriminate also between benign and malignant types of abnormalities
  - from scratch CNN,
  - pre-trained CNN,
  - ensemble of previous CNNs

For each classification the convolutational neural network is designed, trained and evaluated in terms of _Accuracy_, _Confusion Matrices_, _Roc_Curves_.  
To have an explanation of the files, and how to run those, please refere to the _contents.md_ file inside the folders. 


