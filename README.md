# Instructions to run
The following steps should be followed:
 1) One should first create a python virtual environemnt. To download the package type `pip install venv` in the terminal. If you have the package, simply type `python3 -m venv {ENVNAME}`, which will create a venv.
 2) Activate the venv by typing `.\{ENVNAME}\Scripts\activate` on Windows or `source {ENVNAME}/bin/activate` on Linux
 3) Install the requirements located in the main folder - `requirements.txt` by typing `pip install -r requirements.txt`
 4) Then download both datasets from [here](https://archive.ics.uci.edu/ml/datasets/Productivity+Prediction+of+Garment+Employees) (regression data) and [here](https://archive.ics.uci.edu/ml/datasets/Mushroom) (classification data) and put it in a separate folder - `master-project/data`.


# Table of content:

| File name     | Description     
| ------------- | ------------- |
| classification_data_analysis_preprocessing.ipynb | Classification dataset exploratory data analysis and preprocessing. | 
| classification_explainability.ipynb | Script that creates explanation plots for the classification models.| 
|
