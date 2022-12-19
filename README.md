## 1. Installation
Using the anaconde distribution, the following libraries are used:
- Pandas
- Numpy
- matplotlib
- sklearn
- seaborn

Python Version **3.9.12** is used throughout the project.


## 2. Project Motivation
The project is about a first step analysis on the potential driving factors of alzheimer disease. The three business questions asked are:
1. Which features provided in the dataset have the highest correlation to the alzheimer disease being positive?

2. Which features provided in the dataset have the highest correlation to the alzheimer disease being negative?

3. How well can the variance of having alzheimer disease be explained by the given features?


## 3. File Description
The project is structured as simple as possible with a dataset .csv-file, the actual code in the .ipynb-file and this README md-file.


## 4. Technical Results
After the data cleaning & formating process, descriptive statistics, exploratory data analysis and linear regression were the main methods used for solving the business questions on hand. We found out that tha **clinical dementia rating (CDR)** has by far the highest correlation with the alzheimer disease from all the features available in the dataset. On the other hand, the **minimal mentalstate examination** seems to have the lowest correlation with the alzheimer disease. However, these are just trivial results and the alzheimer disease needs further observations, features and more sophisticated methods to get a deeper understanding of the features shaping its existince.


## 5. Licensing, Authors, Acknowledgments
The source of the data is on kaggle (uploaded by **Baris Dinger**). See also: https://www.kaggle.com/datasets/brsdincer/alzheimer-features

Main credits in form of education and encouragement to publish my first little self-made project on medium goes to the team  over at **Udacity**. Really appreciate the well-designed and lectured **Data Scientist Nano Degree Programm**! I know I am far away from being a data scientist, but this small but somewhat signifant milestone feels like the right direction. Cheers!



**MIT License**

_Copyright (c) [2022]_

_Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:_

_The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software._

_THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE._
