# APL405: Machine Learning for Mechanics (Winter semester 2023)

![image](https://user-images.githubusercontent.com/109568856/210075809-15d5fc35-bdc0-453d-a163-cfd4b4d2ce6e.png)

## Course Info

**Credit:** 3 units (2-0-2) <br> 
**Pre-requisites:** APL101/MTL106/MTL108, COL106 <br><br>

**Instructors:** [Rajdip Nayek](https://sites.google.com/view/rajdip-nayek/) (rajdipn@am.iitd.ac.in) <br> <br>

**Class timings:** Tue, Thu & Fri (11:00 to 11:50 AM) at LHC517 <br><br>

**Practical Session:** Fri (3:15 to 5:15 PM) at two labs LH503 and LH502 <br> <br>

**Attendance and Marks:** [Check here](https://docs.google.com/spreadsheets/d/1cNLiHFvedAHg2fuzllDPBvBgMpPTKr7R/edit#gid=221773594)

**Office hours (TA)**: By email appointment <br> 
**Office hours (Instructor)**: By email appointment (Room B24, Block 4) <br><br>

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
- Regression and classification trees
- Bagging and boosting
- Neural networks and deep learning
- Principal component analysis
- k-means clustering

These methods will be studied from various applications throughout the course. The course also covers important practical considerations such as cross-validation, model selection and the bias-variance trade-off. The course includes theory (e.g., derivations and proofs) as well as practice (notably the lab and the course project). The practical part will be implemented using Python.

## Course Structure
* Introduction 
* Supervised Learning 
* k-NN and Decision Trees 
* Linear Regression and Logistic regression 
* Polynomial regression
* Bias-Variance decomposition
* Loss function vs likelihood based models
* Regularization
* Parameter optimization
* Three sets: Train, test, validation
* Neural Networks (NN)
* Support vector machine (SVM) 
* Ensemble algorithms
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
|:----------:|:------------------------------:|:------------------:|:-----------------:|
|Module 00| Introduction | | [Lecture 1](Lectures/Lecture1.pdf)  |
|Module 01| A Preliminary Approach <br> to Supervised Learning| Background <br> k-Nearest Neighbours <br> Decision Trees | [Lecture 2](Lectures/Lecture2.pdf) <br> [Lecture 3](Lectures/Lecture3.pdf) <br> [Lecture 4](Lectures/Lecture4.pdf)| 
|Module 02| Basic Parametric Models | Linear regression <br> Logistic Regression <br> Regularization | [Lecture 5](Lectures/Lecture5.pdf) <br> [Lecture 6](Lectures/Lecture6.pdf) <br> [Lecture 7](Lectures/Lecture7.pdf)| 
|Module 03| Evaluating Performance | Cross-validation <br> Training error-generalization gap <br> Bias-variance decomposition | [Lecture 8](Lectures/Lecture8.pdf) <br> [Lecture 9](Lectures/Lecture9.pdf) <br> [Lecture 10](Lectures/Lecture10.pdf)|
|Module 04| Learning Parametric Models | Loss functions <br> Parameter Optimization | [Lecture 11a](Lectures/Lecture11.pdf) &nbsp; [Lecture 11b](Lectures/Lecture11_2.pdf) <br>  [Lecture 12](Lectures/Lecture12.pdf)
|Module 05| Neural Networks | Feedforward neural network <br> Backpropagation <br> Convolutional Neural Network | [Lecture 13](Lectures/Lecture13.pdf) <br>  [Lecture 14](Lectures/Lecture14.pdf) <br>  [Lecture 15](Lectures/Lecture15.pdf)
|Module 06| Kernel Methods | Kernel Ridge Regression <br> Theory of kernels <br> Support Vector Classification | [Lecture 16](Lectures/Lecture16.pdf)  <br>  [Lecture 17](Lectures/Lecture17.pdf) <br>  [Lecture 18](Lectures/Lecture18.pdf)
|Module 07| Ensemble Methods | Bagging <br> Random Forests <br> Boosting | [Lecture 19](Lectures/Lecture19.pdf)  <br>  [Lecture 20](Lectures/Lecture20.pdf) <br>  [Lecture 21](Lectures/Lecture21.pdf)
|Module 09| Generative Models & <br> Unsupervised Learning  | Gaussian mixture models  <br> Gaussian mixture models (with EM) <br> k-means clustering <br> PCA | [Lecture 22](Lectures/Lecture22.pdf)  <br>  [Lecture 23](Lectures/Lecture23.pdf) <br>  [Lecture 24](Lectures/Lecture24.pdf) <br>  [Lecture 25](Lectures/Lecture25.pdf)



## Practical Schedule

|Week# | Topics| Practical Questions | Notes | 
|:------:|:---------:|:--------:|:-------:|
| Week 1 | Probability refresher | [Practical 1](Practicals/Practical_1.pdf) | [Notes](Practicals/Probability_refresher_updated.pdf) |
| Week 2 | k-Nearest Neighbours  | [Practical 2](Practicals/Practical_2.pdf) | |
| Week 3 | Decision Trees        | [Practical 3](https://colab.research.google.com/drive/15wcB0EsaIQz5N39lSCgD4yBR4KTnUQ9t?usp=sharing) | [Dataset](Practicals/Datasets/spring_stiffness_classify.h5) | 
| Week 4 | Linear Regression     | [Practical 4](https://colab.research.google.com/drive/1SSpo6U-yALWmJlRnk787ntphnCLNJdcz?usp=sharing) | |
| Week 5 | Logistic Regression   | [Practical 5](https://colab.research.google.com/drive/15vqeGXY1MfRkASo8jCMvbBeGkMmU7GRA?usp=sharing) | [Dataset](Practicals/Datasets/cancer.csv) | 
| Week 6 | Cross-validation & Bias-variance trade-off  | [Practical 6](https://colab.research.google.com/drive/13aViGO7WHNP6wzBKWtzNJI4iQwmoXZ9F?usp=sharing) | [Dataset](Practicals/Datasets/cancer.csv) | 
| Week 7 | Introduction to PyTorch for Neural Nets | [Practical 7](https://colab.research.google.com/drive/1POGb8tZGDawVLZTfoPUitchtVpxvFwgg?usp=sharing)| | 
| Week 8 | Support Vector Machine | [Practical 8](https://colab.research.google.com/drive/18-t0OXCsH0E2sCtgvEqDmizuGAy5yuZY?usp=sharing)| | 
| Week 9 | Boosting | [Practical 9](https://colab.research.google.com/drive/1T5FhhRLGqVsdAbnVY3R16hYN8qSJkbm2?usp=sharing)| [Dataset](Practicals/Datasets/damage.csv)| 



## Homework Schedule
A total of three homeworks would be given

|HW# | Questions| Dataset | Solutions |
|:------:|:---------:|:--------:|:---------:|
| HW1 |  [Homework 1](Homeworks/HW1.pdf) | [Datafiles](Homeworks/mnistData.mat) | [Solution](Homeworks/HW1sol.pdf)|
| HW2 |  [Homework 2](Homeworks/HW2.pdf) | | [Solution](Homeworks/HW2sol.pdf)|
| HW3 |  [Homework 3](Homeworks/HW3.pdf) | [Datafiles](https://drive.google.com/file/d/1a8ZTb2gswnOnEw_IJMuUWsqoUgMgxwte/view?usp=sharing) <br> [Template](https://colab.research.google.com/drive/1tuCsaljFLtdzr6AxNK83e6-alNj4wdJP?usp=sharing)| [Solution](Homeworks/HW3sol.pdf)|


## Course References

* Christopher Bishop, *"Pattern Recognition and Machine Learning"*, Springer, 2006.
* Andriy Burkov, *"The Hundred Page Machine Learning Book"*, 2019 [[free pdf](http://ema.cri-info.cm/wp-content/uploads/2019/07/2019BurkovTheHundred-pageMachineLearning.pdf)].
*  Andreas Lindholm et. al., *"Machine Learning: A First Course for Engineers and Scientists"*, Cambridge University Press, 2022 [[free pdf](http://smlbook.org/book/sml-book-draft-latest.pdf)]
* Brunton, Steven L., and J. Nathan Kutz. *"Data-driven science and engineering: Machine learning, dynamical systems, and control"*. Cambridge University Press, 2022.


## Grading  

|Component|Scores| 
|:---|:-----:|
|**Practical Exam** | 10 |
|**Class Attendance**| 5 |
|**Homework**   | 10 |
|**Project**    | 20 |
|**Minor #1**   | 15 | 
|**Minor #2**   | 15 | 
|**Major**      | 25 |
|**Total**      | 100| 

- Students are highly encouraged to attend all classes, but there are no marks on lecture attendance. **You still have to mark your attendance on Timble. If the combined lecture-plus-practical attendance is below 75% of the total, one grade will be lowered.**
- A penalty of 50% of the mark of the respective homework would be deducted if submitted after the deadline. Any submissions two days after the deadline will not be accepted. 

## Exams

|Component| Solution |
|:-----:|:-----:|
|**Minor #1**   | [Solution](Exams/Minor1_soln.pdf) | 
|**Minor #2**   | [Solution](Exams/Minor2_soln.pdf) | 
|**Major**      | [Solution](Exams/Major_soln.pdf) | 


## Project 

A maximum of *two students per project* is allowed

 Project proposal must be submitted by Feb 12th (11:59 pm) (**10% of total project marks**)
- Mid-semester project report must be submitted by Apr 9th (11:59 pm) (**25% of total project marks**)
- Final project report plus a link to a recorded video presentation must be submitted by Apr 27th (11:59 pm) (**(30% +35%) of total project marks**)
- Any delay in submission of the above will be penalized by 1 mark per hour after the deadline has passed!! 

Please follow this [link](Project/project.pdf) for more details on the project.
