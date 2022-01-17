# Signature_Verification - Siamese_Network
Defining the Question:

a) **Specifying the Data Analytic Question**

The main objective in this study is to build a model that, once trained on relevant data, can verify if a signature is genuine or forged.

b) **Defining the Metrics for success**

To satisfy the objective of this study, we will build a model using Siaseme Convolutional Neural Network (sometimes called a twin neural network). Siamese network is a type of deep learning network that uses two or more identical subnetworks that have the same architecture and share the same parameters and weights. Siaseme networks are typically used in tasks that involve finding the relationship between two comparable things; and their shared weights mean that there are fewer parameters to learn during training and they can produce good results with a relatively small amount of training data. As such, we consider Siaseme CNN appropraite for this study.

A threshhold on the Euclidean distance between the signatures wil be used to determine if a signature is forged or genuine, and we aim at achieving a model accuracy of at least 80%.

c) **Understanding the context**

With the mass digitization of activities in the world today, it makes it necessary to also revolutionalize the verification of signatures, which has mainly relied on human- manual effort in the past.

By definition, a signature is an identification mark that a person appends on documents or texts. It remains one of the most popular and commonly accepted biometric hallmarks that has been used since the ancient times for verifying different entities related to human beings; documents, forms, bank cheques etc. Therefore, signature verification is a critical task and many efforts have been made to remove the uncertainty involved in the manual authentication procedure, which makes signature verification an important research line in the field of machine learning and pattern recognition.

Since signature is the primary mechanism both for authentication and authorization in legal transactions, the need for efficient automated solutions for signature verification has increased. Unlike a password, PIN, or key cards – identification data that can be forgotten, lost, stolen or shared – the captured values of the handwritten signature are unique to an individual and virtually impossible to duplicate. Signature verification is natural and intuitive. The primary advantages that automated signature verification has is efficiency and aleviation of the human error. With signatures being widely accepted as the common method of identity verification, we regard this study relevant in serving solutions to current problems of identifcation.


d) **Recording the Experimental Design**

Steps implemented are as follows:


1.) Business Understanding

2.) Reading and previewing the data

3.) Data preprocessing

4.) Modelling

6.) Challenging the solution

7.) Conclusion/recommendations


e) **Relevance of the data**

The dataset utilized in this study consist of train and test directories, each with image folders of forged and genuine signatures. The data was sourced from Kaggle.


**Contributors**
1. Patrick Munyao
2. Eunice Gathoni
