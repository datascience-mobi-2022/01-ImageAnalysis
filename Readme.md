Project 01: Biomedical Image Analysis
============================================================

Supervisor: 

* PD Dr. Karl Rohr (k.rohr@uni-heidelberg.de)
* Christian Ritter (christian.ritter@bioquant.uni-heidelberg.de)
* Carola Krug      (carola.krug@bioquant.uni-heidelberg.de)
* Leonid Kostrykin (leonid.kostrykin@bioquant.uni-heidelberg.de)




## Introduction

Image analysis methods are important to extract relevant information from biomedical image data.
Typically, a large amount of data needs to be analyzed to draw statistically significant conclusions.
Manual analysis of the image data is tedious, time-consuming, and subjective.
Thus, computer-based image analysis is needed, which enables fast, reproducible, and accurate automated analysis of the data.

To extract information from the image data, methods for different image analysis tasks are required. Typical tasks are image preprocessing, feature extraction, segmentation, object recognition, tracking, and image registration. The projects within the topic "Biomedical Image Analysis" comprise different image analysis tasks using different methods and image modalities. The image analysis methods will be implemented in Python using existing libraries (e.g., NumPy, Scikit-learn). 


## Objective

#### Human Face, Digit, and Fashion Recognition
The objective of projects 1, 2, and 3 is to implement and evaluate classification methods for human face, handwritten digit, and fashion recognition using K-nearest neighbors. For all three projects, the first step consists of computing statistical measures for performing data normalization. Second, data dimension reduction should be performed by principal component analysis (PCA) and the results should be visualized. Third, the dataset should be split into training and test datasets in order to perform human face, handwritten digit, or fashion recognition.   

* Project 1: Implementation and evaluation of K-nearest neighbors (KNN) algorithm for human face recognition. 
* Project 2: Implementation and evaluation of K-nearest neighbors (KNN) algorithm for handwritten digit recognition. 
* Project 3: Implementation and evaluation of K-nearest neighbors (KNN) algorithm for fashion recognition. 

#### Cell Nuclei Segmentation
The objective of projects 4 and 5 is to implement and evaluate methods for segmentation of cell nuclei (Otsu thresholding or clustering method). First, an image segmentation method should be implemented. Second, a popular evaluation measure known as "Dice score" should be implemented and tested using synthetically generated images. The methods should be applied to cell nuclei images and the average Dice score should be computed. For Otsu thresholding, the implemented segmentation method should be extended by local thresholding using a sliding window scheme. For the clustering method, the colored images should be converted to different color models and the segmentation results should be compared to the RGB color representation model.  

* Project 4: Implementation and evaluation of Otsu thresholding.
* Project 5: Implementation and evaluation of clustering method.  


## Description of datasets

#### Human Face and Digit Recognition
The Yale Face Database of human faces consists of 165 images from 15 subjects. Per subject exist 11 images with the following facial expressions or configurations: center-light, with glasses, happy, left-light, without glasses, normal, right-light, sad, sleepy, surprised, and wink. The images are grayscale images normalized by size (320×243 pixels) and stored as GIF files.
The datset for digit recognition is from the MNIST database (Modified National Institute of Standards and Technology database) of handwritten digits consisting of a training set (60.000 images) and a test set (10.000 images). The images are size-normalized (28×28 pixels) and centered, and stored as csv (comma-separated values) files. Each line of these files represents an image. The first column represents the label (the digit depicted in the image). 
The fashion-MNIST dataset of Zalando's article images consists of a training set with 60.000 images and a test set of 10.000 images. Each grayscale image has a size of 28x28 pixels and contains a label from ten different classes (e.g., trouser, sandal, sneaker, shirt). The images are size-normalized and centered, and stored as csv files. Each line of these files represents an image and the first column represents the label. 


#### Cell Nuclei Segmentation
The image data for cell nuclei segmentation with Otsu thresholding consists of three different datasets. The first dataset consists of 6 images showing GFP transfected GOWT1 mouse embryonic stem cells. The images have a size of 1024×1024 pixels and show 10–20 cell nuclei per image. The second dataset consists of 18 images of mouse embryonic cells stained with Hoechst. The images have a size of 1344x1024 pixels and include around 60 cell nuclei per image. The third dataset consists of four images with HeLa cells stably expressing H2b-GFP. The images have a size of 1100×700 pixels and show 30–50 cell nuclei per image. 
The dataset for segmentation based on clustering consists of two colour images. The first image has a size of 1024×1024 pixels and consists of fluorescently labeled cell nuclei. The second image has a size of 1200×1200 pixels and shows yeast cells. The clustering method should also be applied and evaluated on one of three datasets used for Otsu thresholding.  


## Literature 

#### Human Face, Digit, and Fashion Recognition
* Gerbrands, J.J. "On the relationships between SVD, KLT and PCA." Pattern Recognition (1981), vol. 14, issues 1-6, pp 375-381
* Belhumeur, P.N., Hespanha, J.P. and Kriegman, D. "Eigenfaces vs. Fisherfaces: Recognition Using Class Specific Linear Projection." IEEE Transactions on Pattern Analysis and Machine Intelligence (1997), vol. 19, pp 711-720.
* Netzer, Y. et al. "Reading Digits in Natural Images with Unsupervised Feature Learning." Proceedings of the Workshop on Neural Information Processing Systems (2011)
* Gareth, J. et al. "An introduction to statistical learning." Springer New York (2013), Chapter 4.4

#### Cell Nuclei Segmentation
* Otsu, N. "A threshold selection method from gray-level histograms." IEEE Transactions on Systems, Man, and Cybernetics 9:1 (1979), pp 62-66.
* Ljosa, V., Sokolnicki, K.L. and Carpenter, A.E. "Annotated high-throughput microscopy image sets for validation." Nature Methods 9:7 (2012), pp 637-637.
* MacKay, D. "An Example Inference Task: Clustering." Information Theory, Inference and Learning Algorithms (2003), Chapter 20


## How to structure your project

### Project proposal

For all projects within the topic "Biomedical Image Analysis" the first task 
is to define a **project proposal**, which should include

* List of planned analysis steps
* Milestones (important achievements)
* Deliverables (result for each milestone)
* Approximate timetable









