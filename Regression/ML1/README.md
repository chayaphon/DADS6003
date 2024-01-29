## Objective
The main objective of this project is to predict housing prices based on various features using linear regression.

## Dataset
- source data : [kaggle](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset?select=Housing.csv)
- Transformation :
  - Column : 'mainroad', 'guestroom', 'basement', 'hotwaterheating', 'airconditioning', 'prefarea' are Norminal measurement ("Yes","No"), need to convert to binary value 0,1<br>
  - Column : 'furnishingstatus' can be rank as Orderinal measurement ( 0 = unfurnished, 1 = semi-furnished, 2 = furnished)<br>

## Technologies Used
- Python
- pandas
- scikit-learn
- matplotlib
- pickle

## Files in the Repository
- Housing.csv: The dataset used in the project.
- house_price_prediction.ipynb : Jupyter notebooks with all the code and analysis.
- ml_6610422007.sav: ML model output from this project.
