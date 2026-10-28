# AI-Powered Student Performance Prediction System

## Project Overview
This project uses Python and machine learning to analyze student performance and predict final marks based on study hours, attendance, and previous scores.

## Objectives
- Analyze student performance data.
- Explore relationships between student characteristics and final marks.
- Build a Linear Regression model.
- Evaluate predictions using MAE and R² score.
- Generate predictions for new student inputs.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Machine Learning Model
Linear Regression was used to predict final marks from three input features:
- Study Hours
- Attendance
- Previous Score

## Results
- Mean Absolute Error (MAE): 5.43 marks
- R² Score: 0.757

These results were obtained using a simulated dataset and a held-out test set. They should not be interpreted as evidence of real-world predictive accuracy.

## Limitations
The dataset was synthetically generated for educational purposes. Performance on real student data may differ significantly.

## Future Improvements
- Use a real, publicly available dataset.
- Compare multiple machine learning models.
- Improve model validation.
- Develop an interactive prediction interface.

## Project Files
- `AI_Student_Performance_System.ipynb` — notebook containing the analysis, visualizations, and machine learning workflow.
- `student_performance_data.csv` — simulated dataset, to be added to the repository.
