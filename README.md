
# Data Oriented Programming Paradigms Assignment : Life Expectancy Analysis and Prediction

### Introduction
This project was performed by a team of three students as part of the course Data Oriented Programming Paradigms. The aim of this project is to answer the following reasearch questions:
- What is the average human life expectancy in the world?
- How does this differ between low-, medium, and high-income countries?
- How does this differ between male and female?
- What characteristics of countries are predictors for differences in life expectancy?
- What are the countries that have the highest improvement and the lowest improvement in terms of life expectancy at birth?

### Requirements

The requirements.txt file lists all Python libraries that the notebook depends on, and they could be installed using:
```
pip install -r requirements.txt
```

### Folder Structure 
```
DataStewardship1
├── data
│   ├── Data_Dump_Health_Stats_301219_V2
│   │   └── data_health_wb.csv
│   ├── Data_Dump_Worldbank_301219_V2
│   │   └── data_worldbank.csv
│   ├── characteristics_siegl.csv
│   ├── data_sources.txt
│   ├── gni_per_capita.csv
│   ├── income_groups.csv
│   ├── life_expectancy_male_female.csv
│   ├── mergedData.csv
│   ├── preprocessedData.csv
│   ├── metadata.txt
│   └── who_data.csv
├── images
│   ├── life_exp_high_variance.png
│   ├── life_exp_per_gender.png
│   ├── life_exp_per_income.png
│   └── pandasformat.png
├── images
│   ├── metadata.xml
│   └── group30_presentation.pdf
├── LICENSE
├── README.md
├── life_exp_notebook_group_30.ipynb
└── requirements.txt
```
### Data
The folder data includes all the data used to generate the results of this project.
The links to the detailed data sources is included in "data_sources.txt".
The merged data created by the jupyter notebook is saved under "mergedData.csv". 
The preprocessed data created by the jupyter notebook is saved under "preprocessedData.csv".
The metadata can be found in "metadata.txt".

### Reproduce Results
To reproduce the results, launch and run the jupyter notebook "life_exp_notebook_group_30.ipynb". It generates the csv files "mergedData.csv" and "preprocessedData.csv". It also generates graphs which can be found under the folder images. 

### Authors

* **Maroua Jaoua** 
* **Bogensperger Johannes** 
* **Siegl Stephan** 

### License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

