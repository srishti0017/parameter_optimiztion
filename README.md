# Project Title

Support Vector Machine
Support Vector Machines (SVMs) are a type of supervised learning algorithm used for classification and regression analysis. They are based on the idea of finding the best decision boundary that separates the data into different classes.

In SVM, we create a hyperplane that maximizes the margin between two classes. The margin is defined as the distance between the hyperplane and the closest points from each class, known as support vectors. The optimal hyperplane is the one that maximizes the margin.

SVM can be used for both linear and nonlinear classification. In the case of linear classification, the hyperplane is a straight line, while in the case of nonlinear classification, we use a technique called kernel trick to transform the input space into a higher dimensional space where a linear hyperplane can be used to separate the data.

SVMs have several advantages over other classification algorithms, including their ability to handle high-dimensional data, work well with both linear and nonlinear data, and their ability to handle large datasets. They also have a solid theoretical foundation and are effective in practice.

# Datasets
https://archive.ics.uci.edu/ml/machine-learning-databases/statlog/australian/australian.dat

# Table
| Sample | Accuracy | Kernel | Nu  |   |
|--------|----------|--------|-----|---|
| 1      | 0.652173 | rbf    | 0.5 |   |
| 2      | 0.657004 | rbf    | 0.5 |   |
| 3      | 0.676329 | poly   | 0.5 |   |
| 4      | 0.681159 | poly   | 0.5 |   |
| 5      | 0.671497 | poly   | 0.5 |   |
| 6      | 0.657004 | poly   | 0.5 |   |
| 7      | 0.661835 | poly   | 0.5 |   |
| 8      | 0.661835 | poly   | 0.5 |   |
| 9      | 0.642512 | rbf    | 0.5 |   |
| 10     | 0.652173 | poly   | 0.5 |   |

Best accuracy sample: Sample 4, Accuracy = 0.6811594202898551
# Graph
![image](https://user-images.githubusercontent.com/115053826/233177238-89f34182-bb20-42e7-8fda-796f3537f54e.png)
