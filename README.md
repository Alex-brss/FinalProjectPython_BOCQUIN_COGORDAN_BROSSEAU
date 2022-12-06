# FinalProjectPython_BOCQUIN_COGORDAN_BROSSEAU

## Diabetes Data Analysis Project
This project aims at analyzing factors related to readmission as well as other outcomes of patients with diabetes using data preprocessing and machine learning techniques. In addition, we have developed a Flask API that allows users to easily interact with the trained model and make predictions on new data.

## Prerequisites

Python 3.5 or higher
Pandas library
Numpy library
Seaborn library
Scikit-Learn library

## Data
The dataset used for this project is the diabetic_data.csv file, which contains information about patients with diabetes. The dataset includes a variety of features, such as age, gender, medical history, and laboratory test results.

## Data Preprocessing
Before we can begin analyzing the data, we need to preprocess it to clean and transform it into a format that is suitable for our analysis. The data preprocessing steps are as follows:


Read the diabetic_data.csv file into a Pandas DataFrame.
Remove rows that have missing values in key columns such as diag_1, diag_2, and diag_3.
Remove the weight feature because it has a large number of missing values.
Convert the age column to a numerical value by mapping the age range strings to a corresponding integer value.
Create new features by combining existing columns. For example, we create the health_index feature by summing the number_emergency, number_inpatient, and number_outpatient columns.
Use the describe() method to generate summary statistics for the preprocessed data.
Modeling
Once the data has been preprocessed, we can begin applying machine learning algorithms to it. In this project, we use the gradient boosting algorithm to train a model on the preprocessed data. The model can then be used to make predictions on new data.
[00:04]
Results
The results of the analysis can be found in the Jupyter notebook included in this project. The notebook includes detailed explanations and visualizations of the data preprocessing steps, the modeling process, and the results of the analysis.

Conclusion
This project demonstrates the potential of data preprocessing and machine learning techniques to analyze medical data and gain insights into factors related to readmission and other outcomes of patients with diabetes. The techniques used in this project can be applied to other medical datasets to gain a better understanding of different diseases and their effects on patients.

Source: The data are submitted on behalf of the Center for Clinical and Translational Research, Virginia Commonwealth University, a recipient of NIH CTSA grant UL1 TR00058 and a recipient of the CERNER data. John Clore (jclore '@' vcu.edu), Krzysztof J. Cios (kcios '@' vcu.edu), Jon DeShazo (jpdeshazo '@' vcu.edu), and Beata Strack (strackb '@' vcu.edu). This data is a de-identified abstract of the Health Facts database (Cerner Corporation, Kansas City, MO). UCI Archive: http://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008

Collaborated with Victor Bocquin and Alexandre Cogordan
