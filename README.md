# Development of a predictive Machine Learning model for PCOS screening

Welcome to the repository of our final project for the MEDI504B course at the University of British Columbia! 

The goal of this project is to develop and validate a predictive diagnostic model using machine learning algorithms to help non-physicians predict the need for South Asian patients to undergo further testing based on their clinical history in order to diagnose polycystic ovary syndrome. Prediction models developed using logistic regression, elastic net and random forest were compared based on their ability to identify all potential PCOS cases (i.e. sensitivity) that need to be referred for further confirmatory testing. Prediction models based on patient history were also be compared to models developed using information obtained through clinical examination, blood tests and transvaginal ultrasound for overall accuracy (i.e. F1 score and area under the receiver operating characteristic curve) to understand the benefit of additional information for diagnostic prediction. Finally, we explored the variable importance to gain insights into the most relevant discriminating features for PCOS in a South Asian population.

If you want to learn more about our work, please check the Final Report pdf in this repository. 

## Structure 
- `Analysis/` Folder containing the R code that was used for the project. Two main Rmd files are present here: one for the Exploratory Data Analysis (EDA), and another one for the creation and comparison of models (PCOS_modeling)
- `Data/` Folder containing the original data in an excel file and the cleaned data that we used for the project. 
- `Final_report.pdf` File containing the report of the project with a broader description of our goals, the interpretation of our results, and their discussion. 

## Authoring
This work was done by Erick Navarro and Timo Tolppa. 

## Data source
The data used to develop and validate the predictive diagnostic model was obtained from publicly available data collected across 10 hospitals in the state of Kerala in India. This data is freely available in [Kaggle](https://www.kaggle.com/datasets/prasoonkottarathil/polycystic-ovary-syndrome-pcos).

