## Carlo Peluso - Portfolio
### Machine Learning / Deep Learning / Data Analysis projects, coding snippets and more.

#### First Person Action Recognition (E. Ilas, C. Peluso, M. Vassallo)
* [Report](https://www.linkedin.com/in/cpeluso/detail/treasury/education:613070153/?entityUrn=urn%3Ali%3Afsd_profileTreasuryMedia%3A(ACoAACTYnZwBjpZIH3qbOmmhp8gjeGX5maT7Bzc%2C1593079189097)&section=education%3A613070153&treasuryCount=2), [presentation slides](https://www.linkedin.com/in/cpeluso/detail/treasury/education:613070153/?entityUrn=urn%3Ali%3Afsd_profileTreasuryMedia%3A(ACoAACTYnZwBjpZIH3qbOmmhp8gjeGX5maT7Bzc%2C1593079052649)&section=education%3A613070153&treasuryCount=2), [code](https://github.com/mldl2020/FirstPersonActionRecognition)

The aim of the project was to implement a **trainable deep neural network model** for **egocentric activity recognition**. 
Firstly we tried to re-implement the **EgoRNN model** and reproduce the original experiments, involving a multiple stage training. Such model adopts a two-stream architecture, relying on spatial attention mechanisms that stimulate the network to attend to regions containing important objects related to the activity under consideration, and on optical flow in order to extract motion features.
In order to better capture spatio-temporal correlations between the two streams, we then transformed the model in a **multiple task single-stream neural network**, forcing it to **learn joint features between the two domains thanks to a self-supervised auxiliary motion segmentation block**.
We then further **enhance the network with an additional self-supervised pretext task that drives the network to better learn temporal correlations** between frames. Multiple experiments are carried out in order to assess the effectiveness of the adopted techniques.

---

#### Machine Learning projects developed for the "Data Science Lab: Process and Methods" course @ Data Science and Engineering Master's Degree at Politecnico di Torino (Grade 29/30):

* [EXAM: Sentiment Analysis on TripAdvisor dataset using Random Forest, Logistic Regressor and LinearSVC](https://github.com/cpeluso/EXAM-TripAdvisor-Sentiment-Analysis/blob/master/EXAM%20-%20TripAdvisor%20Sentiment%20Analysis.ipynb)

Project developed for the winter 2020 exam of the course "Data Science Lab: Process and Methods".
Grade 12/12

* [EXAM: Text classification on BlackLivesMatter tweets dataset using Random Forest, Logistic Regressor, SGD Classifier, SVC and LinearSVC ](https://github.com/cpeluso/EXAM-BlackLivesMatter-Tweets-Classification/blob/master/EXAM-BlackLivesMatter-Tweets-Classification.ipynb)

Project developed for the summer 2020 exam of the course "Data Science Lab: Process and Methods".
Grade 12/12

---

#### Machine Learning projects developed for the "Machine Learning and Deep Learning" course @ Data Science and Engineering Master's Degree at Politecnico di Torino (Grade 27/30):

* [HW1: Wine Classification with the scikit-learn wine dataset using KNN, LinearSVM and RBF Kernel SVM classifiers](https://github.com/cpeluso/HW1-Wine-Classification/blob/master/HW1%20-%20Wine%20Classification.ipynb)

In this homework we will work with the famous **wine dataset** from scikit-learn, from which we will extract a 2D subset, in order to **visualize the different approaches of the KNN, LinearSVM and RBF Kernel SVM classifiers**.<br/>
In particular, the decision boundaries will be analyzed in order to deeply understand which classifier works better than the other for this type of distributions.<br/>
Another goal of this homework is to **visualize the differences produced by a light tuning of the parameters within the same classifier**.


* [HW2: Image Classification with Caltech-101 dataset using trained from scratch and pretrained AlexNet deep model](https://github.com/cpeluso/HW2-Image-Classification/blob/master/HW2%20-%20Image%20Classification.ipynb)

In this homework we will work with the **Caltech-101** dataset from PyTorch, which is composed of 101 categories of images such as animals or common objects.<br/>
The purpose of this homework is to become familiar with the **PyTorch framework**, the **structure of Convolutional Neural Networks** and also to try different approaches for **Image Classification tasks in Deep Learning**, such as:
1. Training from scratch a deep model
2. Use Transfer Learning from pre-trained deep models
3. Use Data Augmentation approach<br/>
The pre-built deep model that will be used is the famous Convolutional Neural Network "**AlexNet**".

* [HW3: Deep Domain Adaptation with PACS dataset constructing a Domain Adversarial Neural Network with pretrained AlexNet layers](https://github.com/cpeluso/HW3-Deep-Domain-Adaptation/blob/master/HW3%20-%20Deep%20Domain%20Adaptation.ipynb)

In this homework we will work with the **PACS dataset**, which is composed of 7 categories of images and 4 different domains (**P**hoto, **A**rt Painting, **C**artoon, **S**ketch).

The purpose of this homework is to build a **Domain Adversarial Neural Network (DANN)** using the pretrained layers of the **AlexNet** in order to achieve **domain adaptation on images belonging to other domains**. <br/> 
> The AlexNet model was chosen for this homework because we will work with **images**, while the original DANN is used to recognize **digits**. <br/>
Moreover, the **source dataset** we will use is the **Photo** domain of the PACS dataset, that contains images from the same domain of the ImageNet dataset (which was used to train the AlexNet).

To do so, I ran different experiments:

* Train the network **without adaptation** on a **source domain** and test on a **target domain**
* Train the network **with adaptation** on a **source domain** and on a **target domain** and test on the latter
* Hyperparameters tuning, training **with** and **without adaptation** first on a **target domain T1** and then on a **target domain T2**, then testing the quality of the network with these parameters on a **target domain T**

Finally, it was possible to infer some **comparisons between the different network performances**, with or without **domain adaptation**.

---

#### Data Extraction, Machine Learning and Deep Learning projects developed for the "Bioinformatics" course @ Data Science and Engineering Master's Degree at Politecnico di Torino:

* [LAB1 - Sequences generation, analysis and consensus region detection](https://github.com/cpeluso/Bioinformatics-LAB1/blob/main/LAB1.ipynb)
* [LAB2 - Sequences global and local alignment using Dynamic Programming approach](https://github.com/cpeluso/Bioinformatics-LAB2/blob/main/LAB2.ipynb)
* [LAB3 - Genes data extraction and manipulation from SAM, BAM, GFF and VCF files](https://github.com/cpeluso/Bioinformatics-LAB3/blob/main/LAB3.ipynb)
* [LAB5 - Feature selection on gene expression data, classification for Luminal A / Luminal B breast cancer subtypes](https://github.com/cpeluso/Bioinformatics-LAB5/blob/main/LAB5.ipynb)
* [LAB6 - Bayesian CNN and standard CNN approaches on Oncogenic dataset](https://github.com/cpeluso/Bioinformatics-LAB6/blob/main/LAB6.ipynb)
* [LAB7 - Fashion MNIST hallucination using DCGAN](https://github.com/cpeluso/Bioinformatics-LAB7/blob/main/LAB7.ipynb)
* [LAB8 - Multi-omics classification: early / late Data Integration and Features Selection](https://github.com/cpeluso/Bioinformatics-LAB8/blob/main/LAB8.ipynb)
* [LAB9 - Autoencoders (standard, with perceptual loss, variational, beta-variational) on Colorectal Histology dataset](https://github.com/cpeluso/Bioinformatics-LAB9/blob/main/LAB9.ipynb)
* [LAB10 - TGAN for generating mRNA data](https://github.com/cpeluso/Bioinformatics-LAB10/blob/main/LAB10.ipynb)
* [Extra 1 - Training from scratch, use as Feature Extractor and fine tune a VGG16 Convolutional Neural Network on Colorectal Cancer Dataset](https://github.com/cpeluso/Bioinformatics-EXTRA1/blob/main/EXTRA1.ipynb)
* [Extra 2 - Bayesian CNN overview](https://github.com/cpeluso/Bioinformatics-EXTRA2/blob/main/EXTRA2.ipynb)

---

#### Hadoop and Spark exercises of the "Distributed Architectures for Big Data processing and analytics" course @ Data Science and Engineering Master's Degree at Politecnico di Torino (Grade 28/30):
* [Hadoop Exercises](https://github.com/cpeluso/Hadoop-Exercises)
* [Spark Exercises](https://github.com/cpeluso/Spark-Exercises)

---

#### Coding snippets:

* [Optical: A Google Calendar Optimizer.](https://github.com/cpeluso/optical) A Calendar optimizer for Google Calendar data using GoogleCalendar API v3 (https://developers.google.com/calendar/quickstart/dotnet) for .NET environments.<br/> The application retrieves the Google Calendar data of N users and finds the time slots available to set up a meeting. 


