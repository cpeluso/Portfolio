## Carlo Peluso - Portfolio
### Machine Learning / Data Science projects, coding snippets and other stuff.

#### Machine Learning projects developed for the "Data Science Lab: Process and Methods" course @ Data Science and Engineering Master's Degree at Politecnico di Torino:

* [EXAM: Sentiment Analysis on TripAdvisor dataset using Random Forest, Logistic Regressor and LinearSVM](https://github.com/cpeluso/EXAM-TripAdvisor-Sentiment-Analysis/blob/master/EXAM%20-%20TripAdvisor%20Sentiment%20Analysis.ipynb)

Project developed for the winter 2020 exam of the course "Data Science Lab: Process and Methods".
Grade 12/12

#### Hadoop exercises of the "Distributed Architectures for Big Data processing and analytics" course @ Data Science and Engineering Master's Degree at Politecnico di Torino:
* [Hadoop Exercises](https://github.com/cpeluso/Hadoop-Exercises)

#### Machine Learning projects developed for the "Machine Learning and Deep Learning" course @ Data Science and Engineering Master's Degree at Politecnico di Torino:

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

#### Coding snippets:

* [Optical: A Google Calendar Optimizer.](https://github.com/cpeluso/optical) A Calendar optimizer for Google Calendar data using GoogleCalendar API v3 (https://developers.google.com/calendar/quickstart/dotnet) for .NET environments.<br/> The application retrieves the Google Calendar data of N users and finds the time slots available to set up a meeting. 


