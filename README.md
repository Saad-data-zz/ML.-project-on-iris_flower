# ML.-project-on-iris_flower
code with complete comment
P#1 
IRIS-Flower-classification

This Project is using completed by the application of machine learning with python programming.
It focuses on IRIS flower classification using Machine Learning with scikit tools.
first, we have IRIS.CSV the data we used for the machine learning model. 
We used following libraries in the project for different purposes.
Pandas for data science/data analysis and machine learning tasks.
Numpy for the effective storage and data matric, array and mathematical operations.
Matplotlib. Pyplot creates a figure, creates a plotting area in a figure.
Seaborn provides a high-level interface for drawing attractive and informative graphics
1.	We used iris.csv as mentioned before and we open the csv with pandas to look into the data by using some function.
2.	For further scrutiny we use head() and tail() function for data formatting for csv file.
3.	Using the plt.figure() function draw the figure for the iris flower species. And define the %age of Setosa, versicolor and Virginica Species in the data.  
4.	Used matplotlib.pyplot for box figure of Sepal.width and Sepal.Lenght 
5.	Used histogram figure for sepal and petal, length, width.
6.	Another ply figure data representation by plot in which x=species is vertical axis’s and y is horizontal axis’s. Violin plot is use here to observe the distribution of numeric data.
7.	Net used the sns.pairplot which is pairwise relationship in dataset.
8.	We have heat Maps plt.gcf which gives us the current figure. 
9.	After this all-data visualization. We reshape the sepal (length and width)
10.	We plot the scatter plot using the sepal parameters length and width. The reason for plotting the scatter plot here is to determine whether two variables have a relationship or correlation.
Implementation of Machine Learning 
Using Scikit Learn for statistical analysis and apply some ML models for analysis
Scikit Learn is the library of machine learning using python. Basically, used for statistical analysis including classification, regression, clustering, and dimensionality reduction.
To apply the Machine Learning there are some basic steps we must follow before applying the choosing and applying model.
Step#1: Prepare the data and print the shape of data.
Step#2: Split the data in two parts one for training and one for the test. (25% set for test)
Then split data return in 2D numpy array.
For validation for we use head() function to see the data.
Step#3: Choosing Model according to data and output required. 
We used different model under supervised and unsupervised leaning to see the accuracy.
Algorithm used for predicting and get accuracy are -
a)	Using logistic Regression which fall under the supervised learning (all the data used is labelled)
b)	Using Confusion Matrix (fall under supervised learning) in statistical classification and machine learning it is known as error matric. The purpose of using it here is to know error made by classifier and calculate different parameters for model such as accuracy.
c)	Support vector (SVM)is used which is also fall under the supervised machine learning. The purpose of use of SVM here is check the accuracy.
d)	Using KNN neighbors algorithm is fall under the supervised learning.
e)	Using gaussian NB is also supervised learning uses the label data. Tells the dimension data.
f)	Using the decision tree algorithm (under the supervised learning) uses a tree-like model set of decisions that lead the user to the answer.

Step#4 
We do the train test split and make the index with the pandas and arrange all the models and the accuracy results in the higher to low order. 
We are maked accuracy and prediction in Iris project through Iris Dataset.
![image](https://user-images.githubusercontent.com/87109729/173429358-58efb44f-d09f-47c3-b6f4-a4106b72322c.png)
