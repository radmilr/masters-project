# Instructions to run
The following steps should be followed:
 1) One should first create a python virtual environemnt. To download the package type `pip install venv` in the terminal. If you have the package, simply type `python3 -m venv {ENVNAME}`, which will create a venv.
 2) Activate the venv by typing `.\{ENVNAME}\Scripts\activate` on Windows or `source {ENVNAME}/bin/activate` on Linux
 3) Install the requirements located in the main folder - `requirements.txt` by typing `pip install -r requirements.txt`
 4) Then download both datasets from [here](https://archive.ics.uci.edu/ml/datasets/Productivity+Prediction+of+Garment+Employees) (regression data) and [here](https://archive.ics.uci.edu/ml/datasets/Mushroom) (classification data) and put them in the following directory: `master-project/data`.


# Table of content:

| File name     | Description     
| ------------- | ------------- |
| classification_data_analysis_preprocessing.ipynb | Classification dataset exploratory data analysis and preprocessing. | 
| classification_explainability.ipynb | Script that creates explanation plots for the classification models.| 
|decision_tree_classification.ipynb | Script that finetunes the parameters of the decision tree classifier. After the finetuning, the best parameters are utilised in order to build the best final model. |
|decision_tree_regression.ipynb | Script that finetunes the parameters of the decision tree regressor After the finetuning, the best parameters are utilised in order to build the best final model. |
| human_evaluation_statistics.ipynb | Script that automates the extraction of human evaluation study results. It also does the statistical analysis tests. |
| linear_regression.ipynb | Script that finetunes the parameters of the linear regression. After the finetuning, the best parameters are utilised in order to build the best final  model. |
| logistic_regression.ipynb | Script that finetunes the parameters of the logistic regression. After the finetuning, the best parameters are utilised in order to build the best final model. |
| long_short_term_memory_classification.ipynb | Script that finetunes the parameters of the long short-term memory classifier. After the finetuning, the best parameters are utilised in order to build the best final model. |
| long_short_term_memory_regression.ipynb | Script that finetunes the parameters of the long short-term memory regressor. After the finetuning, the best parameters are utilised in order to build the best final model. | 
| metric_based_results.ipynb | Script that computes the evaluation metrics' values for both classification and regression tasks. |
| regression_data_analysis_preprocessing.ipynb | Regression dataset exploratory data analysis and preprocessing. | 
| regression_explainability.ipynb | Script that creates explanation plots for the regression models. | 
| support_vector_classification.ipynb | Script that finetunes the parameters of thesupport vector classifier. After the finetuning, the best parameters are utilised in order to build the best final model. |
| support_vector_regression.ipynb | Script that finetunes the parameters of the support vector regressor. After the finetuning, the best parameters are utilised in order to build the best final model.|



