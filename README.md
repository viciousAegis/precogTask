# Indian Judiciary Analyses

## About
This is a project to perform exploratory data analysis on the given dataset, as well as create a classifier for a classification problem.
The work consists of 3 different analysis points, and one classification model.

## Approach
Since the given dataset was very large, firstly, I truncated data into smaller parts based on the needs of my analyses, saved them as datasets on kaggle and then only used the small subsets of data that I extracted. All of these datasets are public and available on Kaggle, and thus can be used to run these jupyter notebooks there.

### Data Analysis
Coming up with analyses was a major part of the project, and afer rejecting over 10 different analysis points, I settled for the following three points based on how interesting the points were, how relevent the analysis would be and how complex the subanalyses could get. The three analysis points I came up with are:
1. **Domestic Violemce Analysis** - In December of 2012, the country was shaken by the horrific case of Nirbhaya. This analysis tries to see if there are any concrete difference in the handling of domestic violemce cases before and after this incident.
2. **Disposition Analysis** - In this Analysis, I try to find correlations between dispositions given out and the genders of the judges, defendants and their advocates to see if any gender bias exists in this case
3. **Literacy Analysis** - It is common belief that higher literacy rates lead to lower rates of crime. We test out this belief in this analysis point

### Classification
I use a dataset of about 150,000 values and try to classify the disposition of a case into either "convicted" or "acquitted" based on various factors detailed in the notebook

## How to run
Since the datasets used in the notebooks are publicly available on kaggle, they can be run on kaggle itself without any problems.
