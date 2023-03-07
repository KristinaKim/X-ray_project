# X-ray_project

 Problem Statement
 *In this case study, we will assume that you work as a Deep Learning Consultant.**
 *You have been hired by a hospital in downtown Toronto and you have been tasked with automate the process of detecting and classifying chest disease and reducing the cost and time of detection.**
 *The team has collected extensive X-Ray chest data and they approached you to develop a model that could detect and classify the diseases in less than 1 minute.**
 *You have been provided with 133 images that belong to 4 classes:**
    * _Healthy_
    * _Covid-19_
    * _Bacterial Pneumonia_
    * _Viral Pneumonia_
    
     We tried to build a Convolutional Neural Networks (CNNs) along with Transfer Learning methods for detecting and classifying chest diseases from X-rays. 
* Trained CNN models and pre-trained models such as ResNet50, VGG-19, VGG-16 were used to create simple models, with different hyperparameters. We saved the trained models in the HF5 format.
* VGG16 model showed the best result with an accuracy of 82%, with small errors in the classification of pneumonia.
* The worst result was the basic CNN model (2nd version) with an accuracy of 75% with the Adamax optimizer.
* The models were good at defining covid but often misclassified pneumonias.
