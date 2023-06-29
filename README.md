# Heart-Disease-Predictor
A Gradio-based GUI that determines if a patient has a Heart Disease using the Logistic Regression model. 

## Libraries Used
[Gradio](https://gradio.app/docs/)

[Numpy](https://numpy.org/doc/stable/)

[Pandas](https://pandas.pydata.org/pandas-docs/stable/)

[Seaborn](https://seaborn.pydata.org/)

[Scikit-Learn](https://scikit-learn.org/stable/)

[Joblib](https://joblib.readthedocs.io/en/latest)

## Working 
The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data). 

The data was analysed with the Pandas library to display the data in a tabular form. Seaborn was used for graphical analysis. Then, the data was split into training data and test data in the pre-processing stage. 

The data was then processed using Logistic Regression Algorithm and accuracy was calculated. Then, the trained model was stored in a Joblib file. 

Using Gradio, a GUI library, the Interface was created. The patients details are entered and depending on the result (0= negative, 1= positive) the reuslt is computed. Two demo examples have also been given to depict either case of a patient. 

## Images 

### 1. Patient has Heart Disease
<img width="923" alt="Screenshot 2023-06-29 181945" src="https://github.com/kritvisharma/Heart-Disease-Predictor/assets/129278877/fad525ca-21d4-4b23-badc-22e589ada187">
<img width="921" alt="Screenshot 2023-06-29 181950" src="https://github.com/kritvisharma/Heart-Disease-Predictor/assets/129278877/e04f7fe7-4661-40a8-96e9-1384eb0ca7bb">

Result: 

<img width="924" alt="Screenshot 2023-06-29 182540" src="https://github.com/kritvisharma/Heart-Disease-Predictor/assets/129278877/67ea5a86-4400-473b-b67f-fdff5d04d644">

### 1. Patient does not have Heart Disease
![Screenshot 2023-06-29 181800](https://github.com/kritvisharma/Heart-Disease-Predictor/assets/129278877/36a3a32d-fd3d-48fb-a57f-44eb0dab4291)
<img width="918" alt="Screenshot 2023-06-29 181810" src="https://github.com/kritvisharma/Heart-Disease-Predictor/assets/129278877/475d8c37-6504-45d0-ab94-6b3799a221e9">

Result: 

<img width="921" alt="Screenshot 2023-06-29 182237" src="https://github.com/kritvisharma/Heart-Disease-Predictor/assets/129278877/0effd9d3-c778-4ab8-bf0b-4bc21bebd430">


