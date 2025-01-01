
# Data Science Pipeline

A machine learning model pipeline implementation to predict whether an item is recommended by a customer based on their review. The data includes numerical, categorical, and text data. 

There are 8 features for to use to predict whether a customer recommends or does not recommend a product. The Recommended IND column gives whether a customer recommends the product where 1 is recommended and a 0 is not recommended. This is the model's target/

The features can be summarized as the following:

- Clothing ID: Integer Categorical variable that refers to the specific piece being reviewed.
Age: Positive Integer variable of the reviewers age.
- Title: String variable for the title of the review.
- Review Text: String variable for the review body.
- Positive Feedback Count: Positive Integer documenting the number of other customers who found this review positive.
- Division Name: Categorical name of the product high level division.
- Department Name: Categorical name of the product department name.
- Class Name: Categorical name of the product class name.

The target:
- Recommended IND: Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended.



## Tech Stack

**Spacy:** Spacy is an opensource advanced python module for natural language processing, It supports multiple languages

**Scikit-learn:** Scikit-learn is an open-source Python library that implements a range of machine learning, pre-processing, cross-validation, and visualization algorithms using a unified interface. It is an open-source machine-learning library that provides a plethora of tools for various machine-learning tasks such as Classification, Regression, Clustering, and many more

**Pandas** a fast, powerful, flexible and easy to use open source data analysis and manipulation tool, built on top of the Python programming language.




## Steps
1- Data Exploration\
2- Splitting Numerical, Categorical, and Text Data\
3- Building Pipeline

 - Defining pipelines for each features group
 - Combine Feature Engineering Pipelines

 4- Training Pipeline\
 5- Evaluate Model\
 6- Fine-Tuning Pipeline\
 7- Further model evaluation


 ### Files
 `starter.ipynb` The notebook file\
 `/data/reviews.csv` The dataset 





