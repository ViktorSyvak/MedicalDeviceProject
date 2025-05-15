# Machine Learning and Data Analysis work 

This folder contains Viktor's work to the MedEq project, specifically focusing on machine learning, data preprocessing, analysis, and visualization.

 
## Folder Structure

Viktor Work - Iteration 1  
├── InternshipProject.ipynb  
├── medical_students_dataset.csv  
└── images/
    └── bmi_predict.png
|(Contains output plots used in the analysis)

## Description

**InternshipProject.ipynb** 
 
This Jupyter notebook includes:

- Data loading and preprocessing: Using 'pandas', 'numpy', and 'scikit-learn'
- Exploratory Data Analysis (EDA): Using 'matplotlib' and 'seaborn'
- Correlation heatmaps and distribution visualizations: Visualizing relationships in the dataset.
- Feature standardization: Using 'StandardScaler' to scale the features.
- Linear regression model: predicting BMI
- Model performance evaluation: Using Mean Squared Error to evaluate the model's performance.
- Generated plot: Actual vs Predicted BMI (`bmi_predict.png`)

**medical_students_dataset.csv**  
The main dataset used for training and analysis, containing medical students data relevant to BMI prediction.

**images.zip**  
Contains saved plots like the BMI distribution and Actual vs. Predicted BMI used for integration into the Django web application.

**Medical students data.zip**  
Compressed version of the dataset folder for reference or re-use.

## Integration Notes

- The trained model can be saved using 'joblib' or 'pickle' for loading into Django.
- The 'bmi_predict.png' image can be rendered on the Django frontend to show model performance.
- Dataset and analysis logic can be connected to backend views for real-time predictions if required.

## Author
Viktor  
Machine Learning & Data Analysis Lead  
