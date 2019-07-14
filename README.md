Kickstarter Title Analysis

The aim of this project is to look at the Kickstarter database in kaggle, found at:

https://www.kaggle.com/kemical/kickstarter-projects

with the goal of identifying patterns in titles and whether or not these can be used to 
predict success of a project or guess at the category of the project. 

The methodology will rely on using bag of words vectorizing of the project titles and one
hot encoding the catogory and sub-category columns. The columns related to the amounts
raised will be used for exploratory analysis, however there will not be an attempt to
predict the values.

Packages to be used:

numpy
pandas
scikit-learn
standard python library