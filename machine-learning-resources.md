# Resources for Machine Learning
## Table of Contentents
* [Introduction](#introduction)
* [What is Machine Learning?](#what-is-machine-learning)
* [Conceptual Resources](#conceptual-resources)
* [Technical Resources](#technical-resources)
* [Programming Tutorials](#programming-tutorials)
* [Vocab](#vocab)


## Introduction
This document contains a list of resources for learning about Machine Learning and some summary notes. I have also included a list of "buzzwords" that get thrown around a lot with some notes of my opinion about those buzzwords.

## What is Machine Learning?

###  NVIDIA Explains what Machine Learning is
* Blog Post - [What's the Difference Between Artificial Intelligence, Machine Learning, and Deep Learning?](https://blogs.nvidia.com/blog/2016/07/29/whats-difference-artificial-intelligence-machine-learning-deep-learning-ai/)
* Webinar - [Deep Learning Demystified](https://www.youtube.com/watch?v=TRCiS2lnGOk&feature=youtu.be) (23 min)

### Microsoft Azure: Data Science for Beginners Video Series
[The Five Questions Data Science can Answer](https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-data-science-for-beginners-the-5-questions-data-science-answers) (5 min)

1) Is this A or B? - Classification
2) Is this weird? - Anomaly Detection
3) How much/How many? - Regression/Numerical Predictions
4) How is this organized? - Clustering
5) What should I do next? - Reinforcement Learning

[Is Your Data Ready for Data Science](https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-data-science-for-beginners-is-your-data-ready-for-data-science) (5 min) 

* Data Must Be:
  * Relevant
  * Connected
  * Accurate
  * Enough to work with

[Ask a Question You can Answer With Data](https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-data-science-for-beginners-ask-a-question-you-can-answer-with-data) (4 min) 

* Ask a very specific question that can be answered with a name or number
* How you ask a question can give you direction on what algorithm to use

[Predict an Answer with a Simple Model](https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-data-science-for-beginners-predict-an-answer-with-a-simple-model) (8 min)

* Example of summed squared error (SSE) regression to fit parameters to a line

[Copy other People's work to do Data Science](https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-data-science-for-beginners-copy-other-peoples-work-to-do-data-science) (3 min)

* Sales pitch for Microsoft Azure Machine Learning and Cortana Machine Learning Gallery

### Jason Mayers's Slide Deck - [Machine Learning 101](https://docs.google.com/presentation/d/1kSuQyW5DTnkVaZEjGYCkfOxvzCqGEFzWBy4e9Uedd9k/mobilepresent?slide=id.g168a3288f7_0_58)
* Jason is a "Senior Creative Engineer" at Google
* The end of the slide deck is a sales pitch for Google Cloud

## Conceptual Resources
### Brandon Rohrer's Blog - [Data Science and Robots](https://brohrer.github.io/blog.html)
* Blog filled with videos and posts about ML and data science
* Very good conceptual explanations without getting very technical

### 3 Brown 1 Blue - [Neural Network Video Series](https://www.3blue1brown.com/videos/2017/10/9/neural-network)
* Great anamiations and visualizations
* A little technical but not overwhelming
1) [But what *is* a Neural Network?](https://www.youtube.com/watch?v=aircAruvnKk) (19 min)
2) [Gradient Descent, How Neural Networks Learn](https://www.youtube.com/watch?v=IHZwWFHWa-w&t=483s) (21 min)
3) [What is Backpropagation and What is it Actually Doing?](https://www.youtube.com/watch?v=Ilg3gGewQ5U) (14 min)
4) [Backpropagation Calculus](https://www.youtube.com/watch?v=tIeHLnjs5U8) (10 min)

### [DeepLearning.TV](https://www.youtube.com/playlist?list=PLjJh1vlSEYgvZ3ze_4pxKHNh1g5PId36-) - YouTube Channel
* Cartoon animations on the concepts behind artificial neural networks

## Technical Resources
### [University of Utah Introduction To Data Science](http://datasciencecourse.net/2018/) - Course Website
* [Course Syllabus](http://datasciencecourse.net/2018/syllabus/) - The course provides an introduction to a wide varity of topics
    * Introduction to data analysis tools in Python
    * Statistics
    * Popular machine learning models: regression, classification, clustering, dimensionality reduction
    * Data collection and formating
    * Data visualization
    * And much more
* [Lecture Material](https://github.com/datascience-course/2018-datascience-lectures) - Github repository of Jupyter Notebooks
* Everything taught is demonstrated in python

### [Victor Lavrenko](https://www.youtube.com/user/victorlavrenko/playlists?view=1&flow=grid) - YouTube Channel
* Lectures from the University of Edinburgh, UK
* Covers machine learning, natural language processing, web scraping, and search engines
* No code, just theory

### [Mathematicalmonk](https://www.youtube.com/user/mathematicalmonk/playlists?disable_polymer=1) - YouTube Channel
* Math intensive lectures on ML algorithms, information theory, and statistics

### [Ox educ](https://www.youtube.com/watch?v=U1HbB0ATZ_A&list=PLFDbGp5YzjqXQ4oE4w9GVWdiokWB9gEpm) - YouTube Channel
* Math intensive lectures on bayesian statistics

### [AP Monitor](https://apm.byu.edu/) - Course Website
* Course website on dynamic optimization and control from Brigham Young University
* Modeling/optimizing for physical systems

## Programming Tutorials
### Google Developers - [Machine Learning Recipes Tutorial Series (python)](https://www.youtube.com/watch?v=cKxRvEZd3Mw&list=PLOU2XLYxmsIIuiBfYad6rFYQU_jL2ryal)
1) [Hello World](https://www.youtube.com/watch?v=cKxRvEZd3Mw) (7 min)
2) [Visualizing a Decision Tree](https://www.youtube.com/watch?v=tNa99PG8hR8&t=316s) (7 min)
3) [What Makes a Good Feature?](https://www.youtube.com/watch?v=N9fDIAflCMY) (6 min)
4) [Let's Write a Pipline](https://www.youtube.com/watch?v=84gqSbLcBFE&t=162s) (8 min)
5) [Writing Our First Classifier](https://www.youtube.com/watch?v=AoeEHqVSNOw) (9 min)
6) [Train an Image Classifier with TensorFlow for Poets](https://www.youtube.com/watch?v=cSKfRcEDGUs&t=2s) (7 min)
7) [Classifying Handwritten Digits with TF Learn](https://www.youtube.com/watch?v=Gj0iyo265bc&t=320s) (7 min)
8) [Let's Write a Decision Tree Classifier from Scratch](https://www.youtube.com/watch?v=LDRbO9a6XPU&t=3s) (10 min)

## Vocab 
### Artificial Intelligence (AI)
* Computers being programmed to do something "smart"
### Machine Learning (ML)
* Subfield of AI
* Statistical analysis of data, lots and lots of data
  * Can be very simple
    * Example: Plotting points and drawing a line through it
  * Can be very complex
    * Example: **Artificial Neural Networks (ANN)**
* Definitley involves optimization

### Deep Learning (DL)
* Subfield of ML
* An ANN that is many layers "deep" in complexity
* Requires very large data sets and GPUs to "train" the ANN
 
### Big Data
* Three V's: Velocity, Variety, & Volume
  * Velocity: Data coming in at a high rate
  * Varity: Incoming data in different structures
  * Volume: Data is large in size
* Massive amounts of data (like 100s of Terabytes or so)
 
### Cloud Computing
* Outsourcing your computation/hardware to a third party service that you connect to through the internet
  * Amazon Web Services (AWS) - Current dominant cloud provider
  * Microsoft Azure - Closest competitor to AWS
  * IBM and Google Cloud - Trying to catch up to AWS and Azure
* The cloud providers offer many different services that range from storage, to webhosting, to computation and such
* Three main "levels" of service
  * Infrastructure as a Service (IaaS)
  * Platform as a Service (PaaS)
  * Software as a Service (SaaS)
  
### Internet of Things (IoT)
* Connecting things to the internet that normally aren't connected
  * Examples: "Smart" devices - Smart phone, Smart Watch, Smart Home - All are IoT
  * Other Example: fridge, toaster, or car engine being connected to the internet
* Arduinos and Raspberry Pis are good for this
* **Industrial Internet of Things (IIoT)**
  * IoT but for industry applications
  * Example: General Electric is starting to embed its products with sensors that comunicate over an internet connection and sell software to go along with it

### Edge Computing
* Collecting small amounts of data from sensors and performing some computation onsite before sending the data to a larger collection of data for storage or further computation - Usually sent to the cloud

### Hadoop Distributed File System (HDFS)
* Commonly referred to as "Hadoop"
* An opensource database framework designed for storing data across a cluster of machines
  * YARN and HDFS are the core components in the architecture
    * YARN is technical portion of Hadoop to be aware of to better understand the architecture
* HDFS is a distributed file system - The data is distributed across a cluster of machines
  * Good with big data
* There are many appendage-like services that may or may not be installed on top of HDFS and YARN
  * **Apache Spark**
    * It's kind of like a SQL database for HDFS
    * Experience with Apache Spark is considered very valuable
    
### Data Science
* Basic workflow: Data Capture -> Storage -> Processing -> Visualization
  * Data Capture
    * Implementing sensors to collect data - usually IoT
  * Storage
    * Storing data with good practices
    * There might be some quick preprocessing done to format the data
  * Processing
    * May require high performance computing (HPC) practices
        * C, C++, and Fortran are good for HPC applications - Because they are compiled, low level languages
        * R and Matlab are bad for HPC applications - Because they are interpreted, high level languages
        * Python - depends on how you do it
        * Hardware accelerators, like GPUs, are great for HPC applications
        * Any parallelization is great for HPC applications - Implement threading or use libraries such as MPI, CUDA, or BLAS
    * Ideally you would skip the storage step and stream your data into processing as it is captured
  * Visualization
    * Making the processed data in human readable form - charts, graphs, and heat maps
* Any part of the workflow could be considered "Data Science"

### Data Engineering
* Maintaining the infrastructure and architecture of a system for other people to use
* A data engineer is the same thing as an admin (System Admin or Database Admin) but doesn't want to be called an "admin"
