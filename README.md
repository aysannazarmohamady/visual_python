# visual python (Introduction and method of using)


***1.what is visual python?***


Visual Python (VPython) is a 3D graphics module for the Python programming language. 

It was originated by David Scherer in 2000 and is designed to make it easy for users to create navigable 3D displays and animations, even for those with limited programming experience. VPython is an open source project that was started for students who struggle with coding during Python classes for data science. 

It aims to provide a GUI-based Python code generator for Google Colab as an extension.


Visual Python is a programming language that allows users to create and manipulate visualizations of data using Python. It provides a set of libraries and tools that make it easier to create interactive visualizations and graphical user interfaces. By using Visual Python, users can represent complex data sets through visualizations such as graphs, charts, and diagrams. These visualizations can help in understanding patterns, trends, and relationships within the data.


![image](https://github.com/aysannazarmohamady/visual_python/assets/30371881/e4986167-88f8-4d8a-8ee1-7e4edd6a01e0)



***2.How to use Visual Python?***


Visual Python can be used in Google Colab (Is a cloud-based platform that allows users to write and execute Python code in a web browser. It provides a convenient environment for data analysis and machine learning tasks.) by installing the necessary libraries and importing them into the notebook. Once Visual Python is set up, users can create visualizations using the available functions and methods.


**2.1 To perform a complete data mining process using Visual Python, users can follow the following steps:**


- Data Collection: Gather the relevant data from various sources such as databases, websites, or files.

- Data Preprocessing: Clean and prepare the data for analysis by handling missing values, removing duplicates, and transforming data into a suitable format.

- Exploratory Data Analysis: Visualize and explore the data to gain insights and understand its characteristics. Use Visual Python to create visualizations that reveal patterns, trends, and correlations in the data.

- Feature Selection: Identify the most relevant features or variables that contribute to the predictive power of the data. This can be done using statistical methods or machine learning algorithms.

- Model Building: Develop a predictive model using machine learning algorithms. Visual Python can be used to visualize the performance of different models and evaluate their accuracy.

- Model Evaluation: Assess the performance of the model using evaluation metrics such as accuracy, precision, recall, and F1 score. Visualize the results using Visual Python to better understand the model's strengths and weaknesses.

- Model Deployment: Deploy the trained model to make predictions on new, unseen data. Visual Python can be used to create visualizations that showcase the model's predictions in real-time.

By following these steps and utilizing the capabilities of Visual Python, users can effectively perform a complete data mining process. It is important to make informed decisions throughout the process and leverage the power of visualization to gain meaningful insights from the data.

***3.How to install Visual Python as an extension***



**3.1 Requirements**

Visual Python is an extension to Jupyter Lab, Jupyter Notebook and Google Colab. 

You must have one of these environment installed already.

- Python version 3.x
- Jupyter Lab(<=3.6.3) or Jupyter Notebook or Google Colab environment

**3.2 Getting started with Jupyter Lab**

- 3.2.1 Install package from PyPI
```
pip install jupyterlab-visualpython
```
- 3.2.2 Activate Visual Python on Jupyter Lab
 Click orange square button on the right side of the Jupyter Lab menu.


**3.3 Getting started with Jupyter Notebook**
 
- 3.3.1. Install package from
```
pip install visualpython
```

- 3.3.2 Enable the package
```
visualpy install
```

- 3.3.3 Activate Visual Python on Jupyter Notebook

   Click orange square button on the right side of the Jupyter Notebook menu.

**3.4 Getting started with Google Colab**

3.4.1. Install package from Chrome Web Store

Install [Visual Python for Colab](https://chrome.google.com/webstore/detail/visual-python-for-colab/ccmkpknjfagaldcgidgcipbpdipfopob)  from chrome web store


3.4.2. Open Google Colab

   Open Google Colab

4.4.3. Activate 'Visual Python for Colab' by clicking icon

   Click orange square button on the top-right bar of the chrome browser.
   
![image](https://github.com/aysannazarmohamady/visual_python/assets/30371881/bcf25fc1-a4d1-41da-ad20-55ea0e5395e2)



***4.How do I do a complete data mining process with it?***

To perform a complete data mining process using Visual Python, we can follow the steps below:

**4.1 Import the necessary libraries:** Apart from Visual Python, we might need other libraries such as Pandas for data manipulation and NumPy for numerical calculations. We can import these libraries using the import statement.
```
import pandas as pd
import numpy as np
from vpython import *
```

**4.2 Load the dataset:** We need to load the dataset into a Pandas DataFrame using the appropriate function (read_csv(), read_excel(), etc.). For example:
```
data = pd.read
```



