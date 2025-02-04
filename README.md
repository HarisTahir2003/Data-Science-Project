# Hi, I'm Haris! 👋

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/) 

# Data Science Project

The Jupyter Notebook 'FinalProject.ipynb' in this repository contains code including cleaning of data, visualization of data and the implementation of a logistic regression model to classify data. The notebooks are structured to provide a comprehensive understanding of these concepts, and include practical implementations, visualizations, and model evaluations. <br> 

The Data-Science-Project folder contains the following files:
- A FinalProject.ipynb file (Jupyter Notebook) that contains all the code including text blocks explaining portions of the code
- three .png files that are screenshots of the plots in the Jupyter Notebook
- A BlogPostLinks.pdf file that contains links to two blogposts. The blogposts are published on medium and explain the findings of the project.
- A Presentation.pdf file that summarizes the findings of the project in a presentation format
- A SurveyResponses.csv file that contains the raw data that was collected from people using Google forms.

  
## Table of Contents

1. [Installation Requirements](#installation-requirements)
2. [Project Structure](#project-structure)
3. [Data](#data)
4. [Screenshots](#screenshots)
 
## Installation Requirements

To run the both the notebooks, you will need the following packages:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install these packages using pip:

```bash
 pip install numpy
```
```bash
 pip install pandas
```
```bash
 pip install matplotlib 
```
```bash
 pip install seaborn 
```
```bash
 pip install scikit-learn
```

After installing the libraries, simply run the 'Imports' code block to enable their usage in the file.

Useful Links for installing Jupyter Notebook:
- https://youtube.com/watch?v=K0B2P1Zpdqs  (MacOS)
- https://www.youtube.com/watch?v=9V7AoX0TvSM (Windows)


## Project Structure

The Jupyter Notebook (KNN.ipynb) is organized into the following sections:
<ul>
<li> Library Imports </li> 
<li> Brief description of the data </li>
<li> Data Cleaning </li>
<li> Dataset Visualization using various graphs </li>
<li> Implementation of a Logistic Regression Machine Learning model along with its evaluation using a classification report </li>   


## Data

The data can be found in the SurveyResponses.csv file.
Here is a description of what each of the columns in the dataset represent:

1. **Timestamp**: The exact timestamp when the respondent submitted the survey.

2. **University**: The name of the university the respondent is enrolled with.

3. **Intended/Current Major**: The respondent's current or intended major field of study.

4. **Plans after degree**: The respondent's plans after completing their degree, such as employment, further education, or self-employment.

5. **Age**: The respondent's age at the time of the survey.

6. **Gender**: The respondent's gender.

7. **Household Monthly Expenses**: The range of the respondent's household monthly expenses, provided as categorical ranges.

8. **Financial Assistance**: Whether the respondent is receiving financial assistance. Values are `Yes`, `No`, or missing if unspecified.

9. **Technical (yes=1, no=0)**: Indicates if the respondent's major is technical (e.g., engineering, computer science). `1` for technical and `0` for non-technical.






## Screenshots
<h3> K-Nearest Neighbour (KNN) </h3>
<h4> 1. This image shows how the value of the Root-Mean-Square-Error changes for increasing values of k. Further explanation of the results of the plot are explained in detail in the Jupyter Notebook. </h4>
<img src="pic11.png" width="450px"> <br> 

<h4> 2. This image shows the trajectory of the actual path of the micro-robot along with the trajectory predicted by the KNN algorithm <strong> implemented from scratch </strong>. You can change the value of 'start_second' in the code to compare the two trajectories for different six-second sets of times.  </h4>
<img src="pic12.png" width="450px"> <br> 

<h4> 3. This image shows the trajectory of the actual path of the micro-robot along with the trajectory predicted by the KNN algorithm <strong> implemented using the scikit-learn library </strong>. You can change the value of 'start_second' in the code to compare the two trajectories for different six-second sets of times.  </h4>
<img src="pic13.png" width="450px"> <br> 

<h3> Regression Tree </h3>
<h4> 1. This image shows how the value of the Root-Mean-Square-Error changes for increasing values of Lookback Size. Further explanation of the results of the plot are explained in detail in the Jupyter Notebook. </h4>
<img src="pic21.png" width="450px"> <br> 

<h4> 2. This image shows the trajectory of the actual path of the micro-robot along with the trajectory predicted by the KNN algorithm implemented using the scikit-learn library. You can change the value of 'start_second' in the code to compare the two trajectories for different six-second sets of times. </h4>
<img src="pic22.png" width="450px"> <br> 

 
## License

[MIT](https://choosealicense.com/licenses/mit/)


