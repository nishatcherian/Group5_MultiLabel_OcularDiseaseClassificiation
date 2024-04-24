# Group5_OcularDiseaseClassification

## Overview
This repository contains files related to the collaborative project on Ocular Diseases classification. The project involves contributions from 4 contributors: Ranga Rohit Nallamolu, Prathyusha Reddy Nandikonda, Nisha Thankam cherian, and Aishwarya More.

### Dataset Link
 https://studentuml-my.sharepoint.com/:f:/g/personal/nishathankam_cherian_student_uml_edu/EmLbJviOed1KqmFiPc2g8I4BkGKK0lzLCjkI92d3VSc3fA?e=6gBAb9

 This sharepoint link contains full_df.csv which is the metadata and folder preprocessed_images.
 Images from preprocessed_images folder was split to be used for model training and testing.
 The dataset source is Kaggle [https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k/data]
 The input image is classified into classes which are : Normal, Diabetes, Glaucoma, Cataract, Age-related Macular Degeneration, Hypertension, Pathological Myopia, and Other diseases/abnormalities

### Files
ResNet_Multilabel.ipynb - This file contains the implementation of ResNet for classifying ocular diseases based on fundus image dataset.
VGGNet_Multilabel.ipynb - This file contains the implementation of VGGNet for classifying ocular diseases based on fundus image dataset.
Inception_v3.ipynb - This file contains the implementation of InceptionNet for classifying ocular diseases based on fundus image dataset.
DenseNet-121.ipynb - This file contains the implementation of DenseNet for classifying ocular diseases based on fundus image dataset.
Ocular_Disease_Model_Comparison.ipynb - This file is a integration of all the models mentioned above and comparison of all their results.

### Requirements :
1.Before running the code, you'll need to install several libraries:
  Install Torch, NumPy, Pandas, Torchvision, TensorFlow, scikit-learn, scikit-image, imageio, Seaborn, Pillow, glob, shutil, and   Matplotlib.
2.Please update the dataset path in the code before execution to ensure correct file retrieval.

### How to Run:

Visit the GitHub Repository:
 Go to the GitHub repository containing the .ipynb file you want to run.

Open in Colab:
 You can click on the "Open in Colab" badge (if available) to directly open and run the notebook in Google Colab. This option allows you to run the notebook without downloading it.

Download and Run Locally:
Click on the .ipynb file to view its contents.
Click the "Raw" button to view the raw content of the file.
Right-click and save the page as an .ipynb file.
Open the downloaded .ipynb file with Jupyter Notebook or Jupyter Lab on your local machine to run it.
Please update the dataset path in the code before execution to ensure correct file retrieval.

### Division of work:

Aishwarya More : 

         Data Preprocessing : Optimize metadata to obtain multiple target labels
         Median frequency balancing
         Custom dataset for data preparation and transformation
         DenseNet model implementation
         Training and validation loss and accuracy
         graphs for DenseNet
         Code documentation

Nisha Thankam Cherian:

         InceptionNet model implementation
         Training and validation loss and accuracy
         graphs for InceptionNet
         Function to evaluate model performance on 
         test data
         Confusion Matrix Heatmap
         Division of work report
         Code documentation


Prathyusha Reddy Nandikonda:

         VGGNet model implementation
         Training and validation loss and accuracy
         graphs for VGGNet
         Integrate all models into single file for model comparison
         Obtain model comparison graphs
         Code documentation
         Tried doing model optimization using different regularization techniques and optimizers

Ranga Rohit Nallamolu:

         ResNet model implementation
         Training and validation loss and accuracy
         graphs for ResNet
         Exploratory Data Analysis
         Train-test split, load dataset into memory, 
         Train and test set sample image visualizations
         Code documentation
         Readme File

### Contributors
Ranga Rohit Nallamolu
Prathyusha Reddy Nandikonda
Nisha Thankam cherian
Aishwarya More