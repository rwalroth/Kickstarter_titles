# Kickstarter Title Analysis

The aim of this project is to look at the Kickstarter database in kaggle, found at:

https://www.kaggle.com/kemical/kickstarter-projects

(data not included in repo)
The goal is identifying patterns in titles and whether or not these can be used to 
predict success of a project or guess at the category of the project. 

## Libraries used

numpy
pandas
scikit-learn
standard python library

## Motivation

This project aims to help project creators set themselves up for success by using existing data to refine their approach. 

## Files

README.md - this file
Kickstarter_Title_analysis.ipynb - Jupyter notebook of the analysis.
Kickstarter_Title_analysis.html - html version for ease of viewing 

## Results

This was a very nice dataset to work with, only having three nan values to get rid of. In terms of answering the questions stated in the beginning, the first concerned how setting a goal for a project would affect the outcome. It was immediately obvious that all the numeric data is strongly right skewed. For the goal column, there were almost no succesful projects with goals above $200,000 dollars. For predicting the category of a project based off of its name, the answer turned out to be extremely varied between categories with Journalism being the hardest to predict while Music was much easier. Finally, the LSA greatly improved the ability of a simple RFC to predict the outcome of a project

## Acknowledgements

Thanks to Mickael Mouille for assembling this dataset

## License

Published under CC BY-NC-SA 4.0 License, copyright 2019 by Richard Walroth