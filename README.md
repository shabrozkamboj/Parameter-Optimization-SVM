# Parameter-Optimization-SVM
## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository.

[Online Shoppers Purchasing Intention Dataset Data Set](https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset)

| Number of Instances:  | 12330 |
|-----------------------|--------|
| Number of Attributes: | 18     |

## About SVM and Parameter Optimization

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning. 

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

## Final Result Table

| Sample  | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| -----   | ------------- | ----------- | ------- | ------------ |
| 1	| 0.64 | linear	| 1.36 | 0.16 |
| 2	| 0.62 | linear |	0.45 | 1.37 |
| 3 | 0.70 | linear	| 9.08 | 8.58 |
| 4	| 0.62 | linear	| 2.31 | 3.66 |
| 5	| 0.64 | linear |	8.30 | 0.92 |
| 6	| 0.64 | linear |	9.25 | 3.43 |
| 7	| 0.61 | linear |	5.11 | 7.37 |
| 8 |	0.54 | poly |	6.95 | 3.99 |
| 9	| 0.61 | linear | 4.36 | 5.71 |
| 10 | 0.64 |	linear | 9.77 |	5.54 |

## Results

The best parameters of SVC for the given dataset are:
- Kernel : Linear
- Nu : 9.08  
- Epsilon : 8.58   

The above parameter gave a maximum accuracy of 0.70.

## Convergence Graph
![graph](https://github.com/ree553/Parameter-Optimization-SVM/blob/main/output.png?raw=true)

## Submission by :
Shabroz Kaur<br>
102017152<br>
CS7
