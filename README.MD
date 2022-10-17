# Face Recognition USing Eigen Values

In this project, we use the PCA(Principal Component Analysis) method to recognize various faces.

## Table of contents
* [Problem Statement](#problem-statement)
* [Background](#background)
* [Dataset](#dataset)
* [Technologies](#technologies)
* [Files and Folders](#files-and-folders)
* [Future Extensions](#future-extensions)

## Problem Statement
Face recognition is a method of identifying or verifying the identity of an individual using their face. The objective of this project is to recognize a face from a pool of known faces.

## Background
The Face recognition method involves two major tasks as Principal Component Analysis and Pattern Recognition Task. The PCA use the largest eigenvalues and its eigenvectors to build the principal eigen faces. Every new testing image is being projected onto the eigen space(collection of eigen faces) and compared with all the eigen faces. The best fit with the face shows that the image is a known face or else unknown. We keep a threshold for the comparison.

## Dataset
[AT&T Database of Faces](https://www.kaggle.com/datasets/kasikrit/att-database-of-faces/download?datasetVersionNumber=2) (size 4MB). The details about the information are in the README file of the database.

## Technologies
The project uses Python >= 3.5

Other technologies used
* Google Colab / Jupyter Notebook
* OpenCV
* Pillow
* Matplotlib
* Numpy

## Files and Folders
`FaceRecognition.ipynb`: The main file containing the code.<br>
`Faces_Dataset`: The database of faces extracted.<br>
`requirements.txt`: The dependencies for the code. They have to be preinstalled.<br>
`Report.pdf`: The understanding of the algorithm and results of the project.

## Future Extensions
The project can be extended by able to detect the new image if it comes repeatedly. This can be done by storing the new image in the pool of eigen faces(eigen space).