# CSC311 Project

Source code that we have built upon can be found [here](https://www.cs.toronto.edu/~rahulgk/courses/csc311_f22/index.html#project).

The data files are pushed to the repository for convenience.


----



# The Problem to Solve
We are trying to solve a problem of matrix completion, a unsupervised learning task. The row represents a student entity, while each column represents a question entity. More specifically, ach entry $(i, j)$ of the matrix corresponds to whether a student $i$ can correctly answer a question $j$ or not (so it takes value either $0$ or $1$). 

A figure that summarizes the context is shown below.

![alt text](https://github.com/haojunqiu/csc311-project/blob/main/img/problem_setup.png)


# Neural Network Architecture

Here is a sketch for the architecture of the neural networks (corresponds to the first 3 methods written in the [final_report.pdf](https://github.com/haojunqiu/csc311-project/blob/main/final_report.pdf)).The meaning of the notations are listed in the report as well (right below where this figure locates).
![alt text](https://github.com/haojunqiu/csc311-project/blob/main/img/nn.png)


# Results
The accuracy we achived on the private dataset is shown below (a systematic study of all methods).
![alt text](https://github.com/haojunqiu/csc311-project/blob/main/img/results.png)

On the preserved dataset for compeition, on [Kaggle](https://www.kaggle.com/competitions/csc311-fall-2022), our team achives **top-3** accuracy among 25 teams.
