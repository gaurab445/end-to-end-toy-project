#  Placement Prediction using Logistic Regression

This project applies **Logistic Regression** to predict whether a student will be placed based on their **CGPA** and **IQ**.

---

##  Dataset

The dataset `placement.csv` contains:
- **cgpa** — student's cumulative GPA  
- **iq** — intelligence quotient  
- **placement** — 1 = Placed, 0 = Not placed

## library
pandas – for loading and handling the dataset (read_csv, DataFrame operations)

numpy – for numerical operations

matplotlib.pyplot – for data visualization (scatter, plots)

mlxtend.plotting – for plotting decision regions of the trained model

scikit-learn (sklearn) – for machine learning tasks:

LogisticRegression – model training

train_test_split – splitting data into training/testing sets

StandardScaler – feature scaling

accuracy_score – model evaluation

pickle – for saving the trained model (model.pkl)


## steps 
-Load and visualize data using matplotlib.

-Split dataset into training and testing sets.

-Standardize data using StandardScaler.

-Train a Logistic Regression model.

-Evaluate accuracy with accuracy_score.

-Visualize decision regions.

-Save the trained model as model.pkl.
