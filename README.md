# Introduction to Predicting Pulmonary Edema for Myocardial Infarction Patients
In this project, I implemented various machine learning algorithms to find patterns between medical data and pulmonary edema for patients who recently suffered a myocardial infarction. Data can be found in the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/579/myocardial+infarction+complications). The `data/` folder contains a `.csv` file with descriptions of each feature. The Jupyter notebook for the project can be found in `src/`, where the `pulmonary edema EDA.ipynb` file contains the exploratory data analysis, and the `pulmonary edema ML.ipynb` file contains the rest of the ML pipeline. The `report` folder contains a PDF describing the goals, methods, and results of the project. All figures from the report can be found in `figures/`. This project created 25 trained models, all of which can be found in `results/`. 

## Prerequisites
To recreate the conda environment, you can use the `MIcomplications.yml` file with the following lines:

`conda env create -n MIcomplications -f MIcomplications.yml`

`conda activate MIcomplications`

This conda environment includes the prerequisite installations to access the dataset in the Jupyter notebook through the UCI Machine Learning Repository, so no data downloads are required.

You should now be able to run the two Jupyter notebooks in `src/`. 

## Author
Roshan Parikh (roshan@brown.edu), Brown University Data Science Institute

## License
This project is licensed under the MIT license.
