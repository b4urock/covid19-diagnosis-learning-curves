![img](https://github.com/b4urock/covid19-diagnosis-learning-curves/raw/main/Assets/logo-sirio-libanes.png)

# covid19-diagnosis-learning-curves
Diagnosis learning curve - Hospital Sírio Libanês - São Paulo e Brasília

## Abstract
Classification of the COVID-19 patient's situation in the Sírio Libanês Hospital facilities (Brasília-DF and São Paulo-SP) with the provided data.

### Task:
1. Predict admission to the ICU of confirmed COVID-19 cases.

### Available data
* Patient demographic information
* Patient previous grouped diseases
* Blood results
* Vital signs
* Blood gases

### Study variables: 
* ICU - YES or NO  - `ICU` - (0,1);
* Time Window - `WINDOW` - ['0-2', '2-4', '6-12', 'Above-12');

### Technologies and libs

* Python 3.7
* Pandas
* Numpy
* Seaborn 
* Matplotlib
* Plotly
* Pycaret
* Sklearn
* Scipy
* shap
* Sweetviz
* Fbprophet

Unfortunately, my interactive graphs made with Plotly are not available at GitHub due to its static render of the notebooks and it doesn't include the embedded HTML/JavaScript that makes up a Plotly graph. See https://help.github.com/articles/working-with-jupyter-notebook-files-on-github/

**To avoid that, please consider open it at [google colab](https://colab.research.google.com/drive/1d1tpn1oA2IN90gQdzROVcRihqcm4gjXX?usp=sharing)**
