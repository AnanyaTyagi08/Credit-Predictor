# Credit Predictor Model

This exploration of a credit prediction model coincides with a paper outlining the details of this project. This readme contains the summary. For additional detail it is highly reccomended you read through the project report. 

## Description

**From Report**
> This paper delves into problems in the financial field. A common issue faced by financial institutions, such as banks, is the question of return on investment and risk. A task that these institutions often carry out is lending money out to individuals in ways such as through a line of credit. However, not every individual can be granted a loan since there is no certainty that all borrowers will repay. In fact, some individuals’ financial histories may clearly indicate that extending credit to them would likely result in a loss. As a result, banks must accurately determine whether individuals have good or bad credit risks to see if they can lend to them with a certain guarantee that they will not lose their money. This prediction task is of utmost importance for financial institutions, as it directly impacts their profitability and sustainability. Given this importance and our group's inherent interest in the financial field, we began investigating this issue. So we began by analyzing a dataset collected from German individuals.

## Summary

| Sction                     | Outline |
|----------------------------|---------|
| Contribution               | Our project provides a broader comparative analysis through the use of multiple models. We do not rely havily on resampling as previous papers do, instead aknoledging, integrationg, and anlysising the impact of the imbalanced dataset.   |
| Exploratory Data Analysis  | We conducted standard cleaning such as dropping null data, checking for outliers, encoding categorical features, and feature scaling.    |
| Methods                    | The models we tests were Logistic Regression, Random Forests, Support Vector Machines (SVM), and K-Nearest Neighbors (kNN). In the paper, we outlined Implementation details, Evaluation metrics, and results for each model with supporting graphics.    |
| Results                    | The Logistic Regression model achieved an accuracy of 80.5% and the Random Forest Classifier achieved an accuracy of 81.5%. The SVM model performed with an accuracy of 77.5%. The kNN model achieved an accuracy of 75.0%. |

## Usage

To use the models and explore the code you may open the [Statlog(German_Credit)CS375_Final.ipynb file](https://github.com/AnanyaTyagi08/Credit-Predictor/blob/120fbaac3621ed88f58c3bbd89f4f2cb15e86c92/Statlog(German_Credit)CS375_Final.ipynb) in google collab or any other platforms that allow you to host and run Jupyter Notebooks. 