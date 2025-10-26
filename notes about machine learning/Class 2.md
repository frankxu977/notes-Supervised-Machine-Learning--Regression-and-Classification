## Unsupervised learning part 1

Unsupervised learning is a key concept in machine learning that focuses on finding patterns in data without labeled outputs.

Understanding Unsupervised Learning

- In unsupervised learning, data is provided without any associated output labels, such as distinguishing between benign and malignant tumors based solely on features like tumor size and patient age.
- The goal is to ==identify structures or patterns within the data==, allowing the algorithm to ==explore and categorize the information== independently.

Clustering Algorithms

- Clustering is a specific type of unsupervised learning that ==groups unlabeled data into clusters based on similarities.==
- Examples include Google News, which ==clusters related articles based on shared keywords==, and DNA microarray data, where individuals are grouped based on genetic activity without predefined categories. 
- figure out by computer itself 

Applications of Clustering

- Companies can use clustering to ==segment customers into distinct market groups, enhancing service efficiency.==
- The deep learning community has utilized clustering to understand learner motivations, identifying groups focused on skill growth, career development, or staying updated on AI impacts.

In summary, unsupervised learning, particularly through ==clustering algorithms, enables the discovery of meaningful patterns in unlabeled data, with various practical applications across different fields.==




## Unsupervised learning part 2

The content focuses on the concept of unsupervised learning in machine learning, particularly highlighting its definition and types.

Unsupervised Learning Overview

- Unsupervised learning involves data that h==as inputs (x) but lacks output labels (y)==, requiring algorithms to ==identify patterns or structures in the data.==
- Clustering is one example of unsupervised learning, where similar data points are grouped together.

Types of Unsupervised Learning

- ==Anomaly detection is used to identify unusual events==, which is crucial for applications like fraud detection in finance.
- ==Dimensionality reduction allows for the compression of large datasets into smaller ones== while retaining essential information.

Examples of Learning Approaches

- Spam filtering is a supervised learning problem due to labeled data, while clustering can be applied to group news articles.
- Market segmentation can be approached as an unsupervised learning problem, whereas diagnosing diabetes is similar to supervised learning tasks.

The content sets the stage for deeper exploration of anomaly detection and dimensionality reduction in future lessons.


##  Jupyter Notebooks

The course content focuses on introducing learners to supervised and unsupervised learning concepts, along with practical coding experience using Jupyter Notebook.

Jupyter Notebook Environment

- Jupyter Notebook is the primary tool for coding and experimenting in machine learning.
- Optional labs allow learners to ==run provided code without needing to write their own,== ensuring a stress-free learning experience.

Optional and Practice Labs

- Optional labs are designed to be easy and guarantee full marks for participation.
- Practice labs will be introduced later, providing opportunities for learners to write their own code.

Understanding Notebook Structure

- The notebook contains two types of cells: Markdown cells for text and code cells for executing Python code.
- Learners are encouraged to interact with the code, make predictions, and modify it to enhance their understanding of machine learning algorithms.

## Linear regression model part 1

The video lecture introduces the concept of supervised learning, focusing on the Linear Regression Model, which is widely used for predicting numerical values.

Linear Regression Model

- It involves fitting a straight line to data points, such as predicting house prices based on size.
- The model is trained using a dataset that includes both ==input features (house size) and output targets (house price).==

Supervised Learning Overview

- Supervised learning requires ==a **training set** with known outputs to train the model.==
- Linear regression is a type of regression model that predicts continuous values, while classification models predict discrete categories.
- classification model predicts categories ( small number of possible outputs )
- ==m= number of training examples==
- ==(x,y)=single training example== 
- ==add i= ith training example== 

Data Representation

- The dataset is represented in a table format, with ==inputs (features) and outputs (targets).==
- Standard notation is introduced for describing training examples, including ==**input variables (x) and output variables (y).**==

## Linear regression model part 2

This content explains the process of supervised learning, particularly focusing on linear regression.

Understanding Supervised Learning

- Supervised learning involves using a training set that ==includes input features (e.g., size of a house) and output targets (e.g., price of the house).==
- The learning algorithm processes this data to ==produce a function==, denoted as f, which ==predicts output values (y-hat) based on new input values (x).==

Function Representation and Prediction

- The function f can be ==represented mathematically, often as a linear equation: f_w,b(x) = wx + b==, where w and b are parameters that influence predictions.
- ==The model's prediction (y-hat) is an estimate of the actual target value (y)==, which is unknown until the outcome is realized.

Linear Regression Basics

- The content introduces linear regression, specifically univariate linear regression, which uses ==one input variable== (e.g., size of the house) to make predictions.
- It emphasizes the simplicity of ==linear functions as a foundation for understanding more complex models in machine learning.==

Next Steps

- The importance of constructing a cost function is highlighted, as it is crucial for training models in machine learning.
- The content encourages learners to explore an optional lab to practice defining a straight line function in Python.
![[Pasted image 20251019143854.png]]
