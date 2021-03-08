# Classification-Company_Data

### Table of Contents
1. [Installation](#installation)
2. [Project Overview](#project)
3. [File Descriptions](#files)
4. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

All the librarires required to run the code are mentioned in [requirements.txt](https://github.com/rahul385/Classification-Company_Data/blob/master/requirements.txt).

To install Run: `pip install -r requirements.txt`

## Project Overview<a name="project"></a>

The objective of this project is to train a machine learning model to classify new instances to a target class, based on the input features of a company's classified data. I have used K Means algorithm for this project.

## File Descriptions <a name="files"></a>

* `CompanyData.ipynb` : The jupyter notebook [CompanyData.ipynb](https://github.com/rahul385/Classification-Company_Data/blob/master/CompanyData.ipynb) includes data exploration, code, machine learning model and visualizations. I used the K Means algorithm to train the model and found the best accuracy for K=23.

* `CompanyData_Profile_Report.html` : Profiling report of the data set

* `Classified Data.csv` : csv file contaning company's classified data

* Visualizations: Includes all plots generated from the training data
   * `ErrorRate_Vs_Kvalue.png` : Error rate with different K values

## Screenshots

  ***Error Rate and K value***
  
![Screenshot 1](https://github.com/rahul385/Classification-Company_Data/blob/master/Visualizations/ErrorRate_Vs_Kvalue.png)

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Author: Rahul Gupta Copyright 2020

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
