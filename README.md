# Project 2020 - Fundamentals for Data Analysis

* **Author:** John Paul Lee
* **Github:** JPLee01
* **Email:** G00387906@gmit.ie
* **Created:** 30-12-2020, **Last update:** 08-01-2021
------------------------------------------------------------------------------------------------
**Programming for Data Analysis:** 

This Jupyter Notebook has been created to perform and explain simple linear regression using Python on the *powerproduction* data set.

**Lecturer:** Dr. Ian McLoughlin

The Project instructions can be found at [here](https://github.com/JPLee01/Fundamentals_of_Data_Analysis-Project_2020/blob/main/Project%20Instructions.pdf)

**Table of Contents**
------------------------------------------------------------------------------------------------

[Project 2020 - Fundamentals for Data Analysis](#Project-2020-Fundamentals-for-Data-Analysis)

[1. Introduction](#1-introduction)

[2. Project Repository](#2-project-repository)

[3. Powerproduction Data Set](#3-Powerproduction-Data_set)

[4. Problem Statement](#4-Problem-Statement)

[5. User Guide](#5-User-Guide)

  [5.1 Downloading the Repository](#5.1-Downloading-the-Repository)

  [5.2  Running the Program](#5.2-Running-the-Program)

  [5.3  Libraries](#5.3-Libraries)

[6. Summary, Conclusion and Future Analysis of the Powerproduction Data set](#6.-Summary,-Conclusion-and-Future-Analysis-of-the-Powerproduction-Data_set)

[7. References](#7-References)

[8. Bibliography](#8-Bibliography)

## 1 Introduction
------------------------------------------------------------------------------------------------
As part of the Project for the Fundamentals for Data Analysis module a Jupyter Notebook has been created to perform and explain simple linear regression using Python on the *powerproduction* data set. This notebook will investigate the application of linear and non-linear regression on the data set in the form of simple linear and polynomial regression. While also investigating the use of machine learning in the form of PolynomialFeatures on the data set. This analysis will be conducted through a Jupyter Notebook which will contain markdown text, images, Python code and Plots. 

## 2 Project Repository
------------------------------------------------------------------------------------------------
The Project Repository is the source where all the work associated with
the project will be stored. It contains the following files and can be
located [here](https://github.com/JPLee01/Fundamentals_of_Data_Analysis-Project_2020):

  **File**    |     **Description**
  ---------   |   --------------------------------------------------------
  .gitignore | A Text File explicitly explaining to Git which files or folders to ignore in the Assignment
  Project Instructions.pdf | A PDF copy of the Poject Instructions
  LICENSE     |    MIT License for the project
  Fundamentals of Data Analysis - Project 2020.ipynb | Jupyter Notebook created to perform and explain simple linear regression using Python on the *powerproduction* data set.
  README.md   |    This file; A Description of the project and instructions

## 3  Powerproduction Data Set
------------------------------------------------------------------------------------------------
 The *powerproduction* data set is a data set to simulate a real world issue the student may face in their career as a data analysis. The *powerproduction* data set was created by the lecturer to assess the students ability to perform and explain simple linear regression using Python.

## 4 Problem Statement
------------------------------------------------------------------------------------------------
As part of the project, the student was given a set of instructions which can be viewed [here](https://github.com/JPLee01/Fundamentals_of_Data_Analysis-Project_2020/blob/main/Project%20Instructions.pdf). As seen, within the instructions a problem statement was printed. It stated that XXXX. Specifically, the instruction state the project should:
* Performing simple linear regression on the *powerproduction* data set.
* An explanation of your regression and an analysis of its accuracy.
* Research and investigation into other types of regression on the *powerproduction* data set and an analysis of its accuracy.

## 5 User Guide
------------------------------------------------------------------------------------------------
This section will describe the steps required to download and run the files in the repository.

### 5.1 Downloading the Repository
The repository is stored at the following: https://github.com/JPLee01/Fundamentals_of_Data_Analysis-Project_2020)

To download the repository, do the following:
1.  Click on the above link to open the repository
2.  Once in the repository, click on the green “clone or download” button on the right side of the screen.
3.  Select "Download ZIP". This will open a prompt allowing you to save the file to a desired location on your computer.
4.  Navigate to where  the ZIP files are located on your computer and extract the compressed (.zip) files.

### 5.2 Running the Program
Once the repository has been downloaded, you will need to ensure that you are running it in the correct environment. It should be noted that this repository has been written using Python 3.8.2 and consequently it will require a Python version of 3.7 at a minimum to run as designed. The repository also requires a number of external Python libraries [seen below](#5.3-Libaries) to execute correctly. Once the correct version of Python has been installed complete with necessary libraries and the ZIP has been downloaded and extracted the user can run the program. The running of any of the programs from the command line can be executed as follows:
1.  Open a command prompt (cmd) or equivalent on your computer.([Cmdr](https://cmder.net) is recommended for Windows computers, Mac Computers via the terminal)
2.  Navigate to the desired location through the use of the change directory (cd) command.
3. Run Jupyter Notebook by typing the following at the command prompt (do not close the command prompt window throughout):
```
jupyter notebook
```
4. A notebook server should automatically launch in your default web browser (URL should be http://localhost:8888). If this does not happen, read the command prompt output. You can copy and paste the above URL into your web browser to access Jupyter Notebook.
6. Using the menu on the left side of the page, double click the jupyter notebook file:
```
Fundamentals of Data Analysis - Project 2020.ipynb
```
7. The notebook should open in a new tab. You can run each cell with the keyboard shortcut SHIFT+ENTER, alternatively use the "play" button on the menu bar. Please note that certain cells must be run before others e.g. the cells importing the various Python libraries. You may find it convenient to use the "Run all Cells" option in the "Run" dropdown menu.

### 5.3 Libraries
The following Python libraries were used in the writing of the projects code and are required to successfully run the programs:
* [Numpy](https://www.numpy.org/) - Used for mathematical functions in the [Fundamentals of Data Analysis - Project 2020.ipynb](https://github.com/JPLee01/Fundamentals_of_Data_Analysis-Project_2020/blob/main/Fundamentals%20of%20Data%20Analysis%20-%20Project%202020.ipynb) notebook.
* [Pandas](https://pandas.pydata.org/) - Used for import, management, data manipulation and analysis in the [Fundamentals of Data Analysis - Project 2020.ipynb](https://github.com/JPLee01/Fundamentals_of_Data_Analysis-Project_2020/blob/main/Fundamentals%20of%20Data%20Analysis%20-%20Project%202020.ipynb) notebook.
* [Matplotlib.pyplot](https://matplotlib.org/tutorials/introductory/pyplot.html) - Used for the manipulation of elements and the creation of certain plots graphs, plots and charts within the [Fundamentals of Data Analysis - Project 2020.ipynb](https://github.com/JPLee01/Fundamentals_of_Data_Analysis-Project_2020/blob/main/Fundamentals%20of%20Data%20Analysis%20-%20Project%202020.ipynb) notebook.
* [Seaborn](https://seaborn.pydata.org/) - Used for the creation and manipulation of all plots in the [Fundamentals of Data Analysis - Project 2020.ipynb](https://github.com/JPLee01/Fundamentals_of_Data_Analysis-Project_2020/blob/main/Fundamentals%20of%20Data%20Analysis%20-%20Project%202020.ipynb) notebook. (Seaborn allows for the extetion of the functionality of Matplotlib).
* [sklearn](https://scikit-learn.org/stable/) - Used to implement machine learning on the data set within the [Fundamentals of Data Analysis - Project 2020.ipynb](https://github.com/JPLee01/Fundamentals_of_Data_Analysis-Project_2020/blob/main/Fundamentals%20of%20Data%20Analysis%20-%20Project%202020.ipynb) notebook.

## 6 Summary, Conclusion and Future Analysis of the Powerproduction Data Set
------------------------------------------------------------------------------------------------
In summary the author was asked to create a jupyter notebook to perform and explain simple linear regression of the *powerproduction* data set. The author also in their analysis investigated performing non-linear regression in the form of polynomial regression on the data set. The author then analysed and compared both regressions for accuracy to the data set. Finally the author investigated the use of machine learning in the form of PolynomialFeatures on the data set, including the possibility to predict the power output based on a speed value entered by the user.

In conclusion the author is of the opinion that the project was a very worthwile and rewarding experience. The project required the author to conduct extensive research into the field of regression. While this at times pushed the author outside their comfort zome, it allowed the author to gain an experience and an appreciation of an area they were not farmiliar with prior to the project. This the author feels can only benefit them as they continue thier studies. 

In terms of future analysis of the data set the possibilities are limitless. The data set itself could be investigated using other forms of regression such as lasso regression and bayesian linear regression. The possibilities of lurking variables and residuals within the data set could also be explored. The author also in their research identified some areas which could benefit from further exploratory analysis and alluded to them within the jupyter notebook. The author would also feel that the machine learning example demonstrated in the jupyter notebook could certainly benefit from further analysis.

## 7 References
------------------------------------------------------------------------------------------------
References will be indicated numerically throughout the Jupyter Notebook and will be listed in full at the end.

## 8 Bibliography
------------------------------------------------------------------------------------------------
Within the course of this project the following sources were used for research purposes:

* Aayushi Johari - Linear Regression Algorithm From Scratch In Python, <https://medium.com/edureka/linear-regression-in-python-e66f869cb6ce>

* Adi Bronshtein - Simple and Multiple Linear Regression in Python, <https://towardsdatascience.com/simple-and-multiple-linear-regression-in-python-c928425168f9>

* Aidan Wilson - Simple Linear Regression in Python (From Scratch), <https://towardsdatascience.com/simple-linear-regression-in-python-numpy-only-130a988c0212>

* Animesh Agarwal - Linear Regression using Python, <https://towardsdatascience.com/linear-regression-using-python-b136c91bf0a2>

* Anglea Shi - Polynomial Regression with Scikit learn: What You Should Know, <https://towardsdatascience.com/polynomial-regression-with-scikit-learn-what-you-should-know-bed9d3296f2>

* Geeks for Geeks - Linear Regression (Python Implementation), <https://www.geeksforgeeks.org/linear-regression-python-implementation/>

* Jim Frost - Guidelines for Removing and Handling Outliers in Data, <https://statisticsbyjim.com/basics/remove-outliers/>

* Jermey Jordan - Preparing data for a machine learning model, <https://www.jeremyjordan.me/preparing-data-for-a-machine-learning-model/>

* Kahn Academy - Identifying outliers with the 1.5xIQR rule, <https://www.khanacademy.org/math/statistics-probability/summarizing-quantitative-data/box-whisker-plots/a/identifying-outliers-iqr-rule>

* Kaushik Katari - Simple Linear Regression Model using Python: Machine Learning, <https://towardsdatascience.com/simple-linear-regression-model-using-python-machine-learning-eab7924d18b4>

* Machine Learning Mastery - How to Use Polynomial Feature Transforms for Machine Learning, <https://machinelearningmastery.com/polynomial-features-transforms-for-machine-learning/>

* Machine Learning Mastery -  Linear Regression for Machine Learning, <https://machinelearningmastery.com/linear-regression-for-machine-learning/>

* Mirko Stojiljković - Linear Regression in Python, <https://realpython.com/linear-regression-in-python/#simple-linear-regression>

* Minitab - Example of Nonlinear Regression, <https://support.minitab.com/en-us/minitab/18/help-and-how-to/modeling-statistics/regression/how-to/nonlinear-regression/before-you-start/example/>

* Pavan Vadapalli - 6 Types of Regression Models in Machine Learning You Should Know About, <https://www.upgrad.com/blog/types-of-regression-models-in-machine-learning/>

* PHP regression class - What is Polynomial Regression?, <http://polynomialregression.drque.net/math.html>

* Pranav Gupta - Linear Regression in Python with Pandas & Scikit-Learn, <https://becominghuman.ai/linear-regression-in-python-with-pandas-scikit-learn-72574a2ec1a5>

* Pratik Shukla - Linear Regression From Scratch, <https://medium.com/@shuklapratik22/linear-regression-from-scratch-a3d21eff4e7c>

* PythonProgramming.net - Regression - How to program the Best Fit Line, <https://pythonprogramming.net/how-to-program-best-fit-line-machine-learning-tutorial/>

* Ritika Singh - Exploratory Data Analysis(EDA) in Python!, <https://www.analyticsvidhya.com/blog/2020/08/exploratory-data-analysiseda-from-scratch-in-python/>

* Scikit-learn Maual Version 0.24.0 - 1.1. Linear Models, <https://scikit-learn.org/stable/modules/linear_model.html#polynomial-regression-extending-linear-models-with-basis-functions>

* Shane Lynn - Python Pandas read_csv – Load Data from CSV Files, <https://www.shanelynn.ie/python-pandas-read_csv-load-data-from-csv-files/>

* Shane Lynn - Using iloc, loc, & ix to select rows and columns in Pandas DataFrames, <https://www.shanelynn.ie/select-pandas-dataframe-rows-and-columns-using-iloc-loc-and-ix/>

* Stack Overflow - Code for best fit straight line of a scatter plot in python, <https://stackoverflow.com/questions/22239691/code-for-best-fit-straight-line-of-a-scatter-plot-in-python>

* Stack Exchange - Polynomial regression using scikit-learn, <https://stats.stackexchange.com/questions/58739/polynomial-regression-using-scikit-learn>

* Stephanie Glen - Residual Values (Residuals) in Regression Analysis, <https://www.statisticshowto.com/residual/>

* Sunil Ray - 7 Regression Techniques you should know!, <https://www.analyticsvidhya.com/blog/2015/08/comprehensive-guide-regression/>

* Tomi Mester - Linear Regression in Python using numpy + polyfit (with code base), <https://data36.com/linear-regression-in-python-numpy-polyfit/>

* University of Canterbury Statistical Consulting Unit - Outliers: why do they occur and how to deal with them, <https://ucscu.wordpress.com/2015/07/16/outliers-why-do-they-occur-and-how-to-deal-with-them/>

* Yufeng - Extract Rows/Columns from A Dataframe in Python & R, <https://towardsdatascience.com/extract-rows-columns-from-a-dataframe-in-python-r-678e5b6743d6>