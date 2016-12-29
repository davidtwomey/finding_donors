#Project: Finding Donors for CharityML
##Project Overview
In this project, many supervised learning algorithms available in sklearn are used, and also provides for a method of evaluating just how each model works and performs on a certain type of data.
##Description
Supervised learning techniques and an analytical mind are to be applied on data collected for the U.S. census to help CharityML (a fictitious charity organization) identify people most likely to donate to their cause. First, data is explored to learn how the census data is recorded. Next, a series of transformations and preprocessing techniques are applied to manipulate the data into a work. Several supervised learnering models are applied and the best suited is chosen for the solution. Afterwards,model is optimised and presented it as solution to CharityML.
##Data
The modified census dataset consists of approximately 32,000 data points, with each datapoint having 13 features. This dataset is a modified version of the dataset published in the paper "Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid", by Ron Kohavi. You may find this paper online, with the original dataset hosted on UCI.

##Features

- age: Age
- workclass: Working Class (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked)
education_level: Level of Education (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool)
- education-num: Education Years Completed
- marital-status: Marital status (Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse)
- occupation: Work Occupation (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces)
relationship: Relationship Status (Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried)
- race: Race (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
- sex: Sex (Female, Male)
- capital-gain: Monetary Capital Gains
- capital-loss: Monetary Capital Losses
- hours-per-week: Average Hours Per Week Worked
- native-country: Native Country (United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands)

##Target Variable
- income: Income Class (<=50K, >50K)

##Software and Libraries

This project uses the following software and Python libraries:

- Python 2.7
- NumPy
- pandas
- scikit-learn
- matplotlib
- Jupyter Notebook.

Files

- finding_donor.ipynb: This is the main file of the project
- census.csv: The project dataset.
- visuals.py: This Python script provides supplementary visualizations for the project.

Run

In a terminal or command window, navigate to the top-level project directory boston_housing/ (that contains this file) and run one of the following commands:

jupyter notebook finding_donor.ipynb

This will open the jupyter Notebook software and project file in browser.
