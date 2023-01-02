# APL405: Machine Learning for Mechanics (Winter semester 2023)

![image](https://user-images.githubusercontent.com/109568856/210075809-15d5fc35-bdc0-453d-a163-cfd4b4d2ce6e.png)

## Course Info

**Credit:** 3 units (2-0-2) <br> 
**Pre-requisites:** APL101/MTL106/MTL108, COL106 <br><br>

**Instructors:** [Rajdip Nayek](https://sites.google.com/view/rajdip-nayek/) (rajdipn@am.iitd.ac.in) <br> <br>

**TA 1:** Tapas (amz218313@am.iitd.ac.in) <br> 
**TA 2:** Navaneeth (amz208527@am.iitd.ac.in) <br>
**TA 3:** Tushar (amz218561@am.iitd.ac.in) <br>
**TA 4:** Sahil (amz228088@am.iitd.ac.in) <br><br>

**Class timings:** Mon, Thu & Fri (11:00 to 11:50 AM) at LHC517 <br><br>

**Practical Session:** Fri (3:15 to 5:15 PM) at two labs LH503 and LH502 <br> <br>

**Office hours (TA)**: By email appointment <br> 
**Office hours (Instructor)**: By email appointment <br><br>

**Intended audience:** BTech students in Applied Mechanics, Materials, Mechanical and Civil Engineering disciplines.<br>


**NOTE**-For *all course related emails*, please put **APL405** in the subject line <br>

## Table of Contents
- [Course Content](#course-content)
- [Course Structure](#course-structure)
- [Lecture Schedule](#lecture-schedule)
- [Practical Schedule](#practical-schedule)
- [Homework Schedule](#homework-schedule)
- [Course References](#course-references)
- [Grading](#grading)
- [Project](#project)

## Course Content
This is an introductory course to statistical machine learning for students with some background in calculus, linear algebra and statistics. The course is focusing on supervised learning, i.e, classification and regression. The course will cover a range of methods used in machine learning and data science, including:
- Linear regression
- Classification via logistic regression and k-nearest neighbour
- Linear discriminant analysis
- Regression and classification trees
- Bagging and boosting
- Neural networks and deep learning
- Gaussian processes
- Principal component analysis
- k-means clustering

These methods will be studied from various applications throughout the course. The course also covers important practical considerations such as cross-validation, model selection and the bias-variance trade-off. The course includes theory (e.g., derivations and proofs) as well as practice (notably the lab and the course project). The practical part will be implemented using Python.

## Course Structure
* Introduction 
* Supervised Learning 
* k-NN and Decision Trees 
* Linear Regression and Logistic regression 
* Polynomial regression
* Support vector machine (SVM) 
* Bias-Variance decomposition
* Building blocks of an ML algorithm

<!--
  * Principles of Parametric modelling
  * Loss function vs likelihood based models
  * Regularization
  * Parameter optimization
  * Hyperparameter optimization
  * Practical aspects
    * One-hot encoding
    * Binning
    * Input normalization
    * Three sets: Train, test, validation
    * Model performance assessment: 
      * Confusion matrix
      * Precision
      * Accuracy
-->
  
* Bayesian Approach and Gaussian Process  
* Neural Networks (NN)

<!--
  * Feedforward NN
  * Training a neural network using back propagation
-->

* Ensemble algorithms

<!--
  * Bagging
  * Boosting
  * Random Forest
-->

* Unsupervised Learning (Representation Learning and Dimensionality Reduction)

<!--
  * PCA
  * Kernel PCA
  * ICA
  * k-means clustering
  * EM algorithm
-->

## Lecture Schedule

|Module#| Main Topic | Sub Topics|Lecture Notes| 
|:----------:|:----------------------------: |:------------------:|:-------------:|
|Module 00| Introduction | | [Lecture 1]  |
|Module 01| A Preliminary Approach <br> to Supervised Learning| Background <br> k-Nearest Neighbours <br> Decision Trees | [Lecture 2] <br> [Lecture 3] <br> [Lecture 4]| 
|Module 02| Basic Parametric Models | Linear regression <br> Logistic Regression <br> Regularization | [Lecture 5] <br> [Lecture 6] <br> [Lecture 7]| 
|Module 03| Evaluating Performance | Bias-variance decomposition | [Lecture 8] |
|Module 04| Learning Parametric Models | Loss functions and likelihood-based models <br> Parameter Optimization | [Lecture 9] <br> [Lecture 10] 



## Practical Schedule

|Week# | Topics| Practical Questions| 
|:------:|:---------:|:--------:|
| Week 1 | Probability refresher | [Practical 1](Practicals/Practical_1.pdf) | 
| Week 2 | k-Nearest Neighbours  | [Practical 2](Practicals/Practical_2.pdf) | 
| Week 3 | Decision Trees        | [Practical 3](Practicals/Practical_3.pdf) | 


## Homework Schedule
A total of 4 homeworks would be given, and must be submitted within 2 weeks of posting

|HW# | Questions| 
|:------:|:---------:|
| HW1 |  [Homework 1](Homeworks/HW_1.pdf) | 
| HW2 |  [Homework 2](Homeworks/HW_2.pdf) | 
| HW3 |  [Homework 3](Homeworks/HW_3.pdf) | 
| HW4 |  [Homework 4](Homeworks/HW_4.pdf) | 


## Course References
This course is not based on any particular textbook. However, the course materials have been prepared using the following four references:
* Mathematics for Machine Learning [[free pdf](https://mml-book.github.io/book/mml-book.pdf)]
* Christopher Bishop, *"Pattern Recognition and Machine Learning"*, Springer, 2006.
* Andriy Burkov, *"The Hundred Page Machine Learning Book"*, 2019 [[free pdf](http://ema.cri-info.cm/wp-content/uploads/2019/07/2019BurkovTheHundred-pageMachineLearning.pdf)].
*  Andreas Lindholm et. al., *"Machine Learning: A First Course for Engineers and Scientists"*, Cambridge University Press, 2022 [[free pdf](http://smlbook.org/book/sml-book-draft-latest.pdf)]
* Brunton, Steven L., and J. Nathan Kutz. Data-driven science and engineering: Machine learning, dynamical systems, and control. Cambridge University Press, 2022.


## Grading  

|Component|Scores| 
|:---|:-----:|
|**Practical Exam** | 10 |
|**Practical Attendance**| 5 |
|**Homework**  | 10 |
|**Project**    | 20 |
|**Minor #1**   | 15 | 
|**Minor #2**   | 15 | 
|**Major**      | 25 |
|**Total**      | 100| 

- Students are highly encouraged to attend all classes, but there is no marks on lecture attendance. **You still have to mark your attendance on Timble. If the combined lecture-plus-practical attendance is below 75% of the total, one grade would be lowered.**
- There would a practical exam conducted towards the end of the semester.
- Homeworks must be submitted within a week of posting. A penalty of 50% of the mark of the respective homework would be deducted if submitted after the deadline. Any submissions two days after the deadline would not be accepted. 

## Project 

A maximum of *two students per project* is allowed

Choose from any one of the catergory of projects you like. Each catergory has different maximum attainable marks.

* Option A (Literature survey) [**15/20 marks**]:
  * Pick a problem that interests you within the domain of civil and/or mechanical engineering
  * Search the literature for machine learning approaches to tackle this problem
  * Survey and discuss the relative strengths of each approach

* Option B (Empirical evaluation) [**17.5/20 marks**]:
  * Pick a problem that interests you within the domain of civil and/or mechanical engineering
  * Implement and experiment with several machine learning techniques to tackle this problem
  
* Option C (Algorithm design) [**20/20 marks**]:
  * Identify a problem within the domain of civil and/or mechanical engineering for which there are no satisfying approaches
  * Develop a new machine learning technique to tackle this problem
  * Analyze theoretically and/or empirically the performance of your technique

- Project proposal must be submitted by Feb 12th (11:59 pm) (**10% of total project marks**)
- Mid-semester project report must be submitted by Mar 26th (11:59 pm) (**25% of total project marks**)
- Final project report plus a link to a recorded video presentation must be submitted by Apr 27th (11:59 pm) (**(40% +25%) of total project marks**)
- Any delay in submission of the above will be penalized by 1 mark per hour after the deadline has passed!! 

Please follow this [link](Project/project.pdf) for more details on the project.
