Building of machine learning model
The dataset in “2022_Test_ML.csv” consists of 4 features (s_mt, s_mq, d, h_p) and of 2 objectives (QW, DP). The goal of the task is to build the model which approximates and generalizes QW and DP for arbitrary values of s_mt, s_mq, d, h_p within the range of their variation (Table 1).

s_mt	s_mq	d	h_p
Min	0.8	0.8	1.0	4.0
Max	2.7	2.1	3.0	10.0
Table 1: Ranges of variations for considered features
Requirements for the test task:
1.	The task should be solved with the use of Python in the framework of Jupyter notebook
a.	Analyze data to understand the dataset quality and properties of the target functions
b.	Building the model for target functions. The choice of the regression model could be arbitrary but should be justified
c.	Assess the approximation and generalization errors of the obtained model. Use the coefficient of determination (R2) for the error metrics
d.	Show the dependency of the model approximation and generalization errors from the total number of points in the dataset
#2.	The results should be summarized in the PowerPoint presentation containing the test case description and results
