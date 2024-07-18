# MATH 373: Intro to Machine Learning

## James D. Wilson

**Email**: jdwilson4@usfca.edu

**Class Time**: MWF 10:30 - 11:35 in LS 210

**Office Hours**: MW 1:30 - 3:00 in Harney 107B

**Book**: [Intro to Statistical Learning (ISL)](http://www-bcf.usc.edu/~gareth/ISL/) by Gareth James, Daniela Witten, Trevor Hastie and Robert Tibshirani

**Syllabus**: [Link](https://github.com/jdwilson4/Intro-to-Machine-Learning/blob/master/Syllabus_ML_2018.pdf)

## Course Learning Outcomes

By the end of this course, you will be able to implement and mathematically justify the following concepts and methodologies of statistical machine learning

**Basic Statistical Concepts**

- The learning problem
- Training vs. testing
- Resampling and cross validation
- Model assessment

**Supervised Learning**

- Regression: principal components regression, Lasso, Ridge regression, Elastic net
- Classification: k-Nearest Neighbors, Linear and Quadratic Discriminant analysis, logistic regression, naive Bayes classifiers, support vector machines
- Tree-based methods: decision trees for regression and classification, bagging, random forests, boosting
- Introduction to neural networks (if time permits)

**Unsupervised Learning**

- Clustering: k-means, hierarchical clustering, spectral clustering
- Goodness of fit and method assessment
- Biclustering


## Course Overview

### Assessment

This course will be assessed according to the following.

- **Homework Assignments** (35%) For each assignment, you will be required to upload a .pdf file to the Canvas site that contains your R code, any analyses, and any visualization used to answer the questions on the assignment. This .pdf file must be a result of compiling R code in RStudio using the knitr package. These must be submitted before the deadline set on github.
- **Case Studies** (35%) There will be several in- and out- of class case studies throughout the class. These are to be completed using RStudio.
- **Final Exam** (30%) The final exam will be comprehensive and cover all material provided in class.

### Schedule

Overall, this course will be split into three main parts: (1) regression, (2) classification, and (3) unsupervised learning and clustering. 

**Introduction**

| Topic | Reading | Assignment | Due Date | In Class Code |
|:--|:--|:--|:--|:--|
|[Introduction](https://github.com/jdwilson4/Intro-to-Machine-Learning/blob/master/Lectures/Lecture%201%20Introduction.pdf)| Ch.1, Section 2.1 ISL | [Homework 0](https://github.com/jdwilson4/Intro-to-Machine-Learning/blob/master/Assignments/Homework0.pdf) | Wednesday, Jan 31st | |

**Regression**

| Topic | Reading | Assignment | Due Date | In Class Code |
|:--|:--|:--|:--|:--|
|[Components of Regression](https://github.com/jdwilson4/Intro-to-Machine-Learning/blob/master/Lectures/Lecture%202%20Regression.pdf)| Section 2.2, Section 3.1 - 3.3, Section 5.1 of ISL | | | [Section 3.3 ISL](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20Seventh%20Printing.pdf) |
|[Shrinkage Methods](https://github.com/jdwilson4/Intro-to-Machine-Learning/blob/master/Lectures/Lecture%203%20Shrinkage%20Methods.pdf) | Section 6.2 of ISL | | | [Shrinkage Code](https://github.com/jdwilson4/Intro-to-Machine-Learning/blob/master/Code_Demonstrations/Shrinkage.pdf)|
|[Principal Components Regression](https://github.com/jdwilson4/Intro-to-Machine-Learning/blob/master/Lectures/Lecture%204%20Principal%20Components.pdf) | 6.3.1 of ISL; [A Tutorial on PCA](https://arxiv.org/pdf/1404.1100.pdf) | [Homework 1](https://github.com/jdwilson4/Intro-to-Machine-Learning/blob/master/Assignments/Homework1.pdf) | Wednesday, Feb 14th| [PCA Code](https://github.com/jdwilson4/Intro-to-Machine-Learning/blob/master/Code_Demonstrations/Principal_Components.pdf) |


**Classification**

| Topic | Reading | Assignment | Due Date | In Class Code |
|:--|:--|:--|:--|:--|
|[Components of Classification](https://github.com/jdwilson4/Intro-to-Machine-Learning/blob/master/Lectures/Lecture%205%20Classification.pdf)| Section 4.1 - 4.3 of ISL | [Homework 2](https://github.com/jdwilson4/Intro-to-Machine-Learning/blob/master/Assignments/Homework2.pdf)| Friday, March 2nd| |
|[kNN and Bayes Classifiers](https://github.com/jdwilson4/Intro-to-Machine-Learning/blob/master/Lectures/Lecture%206%20Classification%20Methods%20I.pdf)| Section 2.2.3, Section 4.4 of ISL | | | |
|[LDA, QDA, and Logistic Regression](https://github.com/jdwilson4/Intro-to-Machine-Learning/blob/master/Lectures/Lecture%207%20Classification%20Methods%20II.pdf)| Section 4.3, Section 4.5 of ISL | [Homework 3](https://github.com/jdwilson4/Intro-to-Machine-Learning/blob/master/Assignments/Homework3.pdf)| Monday, April 2nd| [Classification Code](https://github.com/jdwilson4/Intro-to-Machine-Learning/blob/master/Code_Demonstrations/Classfication.pdf)|



**Tree-based Methods**

| Topic | Reading | Assignment | Due Date | In Class Code |
|:--|:--|:--|:--|:--|
|[Trees, Bagging, and Random Forests](https://github.com/jdwilson4/Intro-to-Machine-Learning/blob/master/Lectures/Lecture%208%20Tree-Based%20Methods.pdf) | Sections 8.1 and 8.2 of ISL | | | [Ensemble Methods Code](https://github.com/jdwilson4/Intro-to-Machine-Learning/blob/master/Code_Demonstrations/Decision_Trees.pdf)|
|[Boosting](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20First%20Printing.pdf) | Section 8.2 and 8.3 of ISL | | | |

**Unsupervised Learning**

| Topic | Reading | Assignment | Due Date | In Class Code |
|:--|:--|:--|:--|:--|
|[k-Means and Hierarchical Clustering](https://github.com/jdwilson4/Intro-to-Machine-Learning/blob/master/Lectures/Lecture%209%20Unsupervised%20Learning.pdf)| Section 10.1 - 10.3 of ISL | | | |
|[Graphs and Community Detection](https://github.com/jdwilson4/Intro-to-Machine-Learning/blob/master/Lectures/Lecture%2010%20Graphs%20and%20Community%20Detection.pdf)| | | | |

**Intro to Neural Networks and Deep Learning**

| Topic | Reading | Assignment | Due Date | In Class Code |
|:--|:--|:--|:--|:--|

### Case Studies
| Case Study | Date |
|:--- | :---  |
|[Spam Detection and Naive Bayes](https://github.com/jdwilson4/Intro-to-Machine-Learning/blob/master/Case%20Studies/Naive_Bayes_Case_Study.pdf)| February 23rd|
|[Ensemble Methods](https://github.com/jdwilson4/Intro-to-Machine-Learning/blob/master/Case%20Studies/Ensemble_Methods_Case_Study.pdf)| April 1st |
### Important Dates

- Friday, January 26th - Last day to add the class
- Friday, February 9th - Census date. Last day to withdraw with tuition reversal
- Monday, February 19th - Presidents' Day (**no class**)
- Monday, March 12th - Friday, March 16th - Spring break! (**no class**)
- Friday, March 30th - Easter holiday (**no class**)
- Wednesday, May 9th - Last day of class!
- Monday, May 14th - Final exam (10:00 AM - 12:00 PM)
