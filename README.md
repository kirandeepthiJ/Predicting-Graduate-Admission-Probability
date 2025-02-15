# Predicting-Graduate-Admission-Probability

## Project Overview
This project aims to predict the chances of graduate admission based on various academic and extracurricular factors. It utilizes machine learning techniques to analyze historical data and provide insights into the admission probability of students, particularly from an Indian perspective.

## Dataset Description
The dataset contains the following features:
- **Serial No.**: Unique row ID
- **GRE Scores**: Scores out of 340
- **TOEFL Scores**: Scores out of 120
- **University Rating**: Rating of the university (out of 5)
- **SOP & LOR Strength**: Strength of the Statement of Purpose and Letter of Recommendation (out of 5)
- **Undergraduate GPA**: GPA on a scale of 10
- **Research Experience**: Binary value (0 - No, 1 - Yes)
- **Chance of Admit**: Target variable (ranging from 0 to 1)

## Problem Statement
Predict the chances of graduate admission based on the given features using machine learning algorithms.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- Statsmodels
- SciPy

## Project Workflow
1. **Data Preprocessing**
   - Handling missing values (if any)
   - Feature scaling using StandardScaler
   - Splitting dataset into training and testing sets

2. **Exploratory Data Analysis (EDA)**
   - Data visualization using Matplotlib and Seaborn
   - Correlation analysis
   - Variance Inflation Factor (VIF) calculation

3. **Model Training & Evaluation**
   - Linear Regression
   - Random Forest Regressor
   - Performance evaluation using:
     - R-squared score
     - Mean Squared Error (MSE)
     - Mean Absolute Error (MAE)

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/graduate-admission-prediction.git
   ```
2. Install required dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn statsmodels scipy
   ```
3. Run the Jupyter Notebook or Python script to train and evaluate the models.

## Results
- The model provides insights into the factors influencing graduate admission.
- Predicts admission probability with reasonable accuracy.

## Future Improvements
- Incorporating additional features such as work experience, extracurricular activities, etc.
- Trying advanced machine learning models like XGBoost.
- Hyperparameter tuning for better performance.

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.

