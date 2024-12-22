# Introduction to Predicting Complications for Myocardial Infarction Patients
In this project, I implemented various machine learning algorithms to find patterns between medical data and two complications (pulmonary edema and relapse of myocardial infarction) for patients who recently suffered a myocardial infarction. The machine learning process is identical for the analyses of the two complications. Data can be found in the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/579/myocardial+infarction+complications). The `data/` folder contains a `.csv` file with descriptions of each feature. The Jupyter notebooks for the project can be found in `src/`, where the `[complication] EDA.ipynb` files contain the exploratory data analysis, and the `[complication] ML.ipynb` files contain the rest of the ML pipeline for that complication. The `report` folder contains a PDF describing the goals, methods, and results of the project. All figures from the report can be found in `figures/`. This project created 25 trained models for each complication (50 total, 10 total for each of 5 classification methods). For each complication, the trained model with the best $f_1$-score for each classification method can be found in `results/`. 

## Prerequisites
To recreate the conda environment, you can use the `MIcomplications.yml` file with the following lines:

`conda env create -n MIcomplications -f MIcomplications.yml`

`conda activate MIcomplications`

This conda environment includes the prerequisite installations to access the dataset in the Jupyter notebook through the UCI Machine Learning Repository, so no data downloads are required.

You should now be able to run the four Jupyter notebooks in `src/`. 

## Author
Roshan Parikh (roshan@brown.edu), Brown University Data Science Institute

## License
This project is licensed under the MIT license.
