#Student-Marks-Prediction-using-Machine-Learning
- This project predicts student marks based on academic effort indicators using supervised machine learning techniques. The objective is to understand how factors like number of courses and study time influence academic performance.

#Project Overview
- **Problem Type:** Regression (Supervised Learning)
- **Dataset:** Student Marks Dataset (Kaggle)
- **Algorithms Used:**
- Linear Regression
- Decision Tree Regression
- **Evaluation Metrics:**
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
 
#Dataset Description
The dataset contains information about students and their academic performance.

#Features Used:
- `number_courses` – Number of courses enrolled
- `time_study` – Study time in hours

#Target Variable:
- `Marks` – Final marks scored by the student (0–100)

#Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

#Methodology
1. Load and preprocess the dataset  
2. Split data into training and testing sets (80/20)  
3. Train Linear Regression and Decision Tree models  
4. Evaluate models using MAE and MSE  
5. Visualize predictions and compare model performance  
6. Predict marks for user-provided input values

#Results
- Linear Regression performs well for linear trends.
- Decision Tree captures non-linear patterns but may overfit.
- Model comparison is done using Mean Absolute Error.

#How to Run
1. Clone this repository
2. Place `Student_Marks.csv` in the project directory
3. Run the Python script
4. Enter values for:
   - Number of courses
   - Study time in hours
5. View predicted marks

#Future Enhancements
- Add more features such as attendance or sleep hours (with proper data)
- Use Polynomial Regression
- Deploy as a web app using Streamlit or Flask

#Author
Mehi Manswa Bhagat 
Machine Learning Mini Project
