# Final Project - BSc(Hons) in Computing in IT - 4th Year

## Project Title: Interactive Health and Fitness Prediction System

### Team Members:
- Guilherme Oliveira
- Willian Lopes do Amaral

## Overview:
This project aims to develop an interactive health and fitness prediction system that assists users in managing their fitness goals, calorie expenditure, and food intake. The system utilizes machine learning models to provide personalized predictions based on user inputs.

## Project Components:
1. **Calories Prediction Model:**
    - Predicts the number of calories burned during physical exercise based on user characteristics (gender, age, height, weight) and exercise parameters (duration, heart rate, body temperature).
    - Model: Random Forest Regressor
    - Input Data: User details and exercise parameters
    - Output: Estimated calories burned
    
2. **Food Category Recommendation:**
    - Recommends suitable food categories based on nutritional values provided by the user.
    - Model: Support Vector Classifier (SVC)
    - Input Data: Nutritional values of the food
    - Output: Predicted food category
    
3. **User Interaction Interface:**
    - Allows users to interact with the system by providing input for calorie prediction or food category recommendation.
    - Provides an intuitive interface for easy interaction.
    - Implemented in Python for flexibility and ease of use.
    
## Usage:
1. **Calories Prediction:**
    - Users input their gender, age, height, weight, exercise duration, heart rate, and body temperature.
    - The system predicts the number of calories burned during the exercise session.
    - Helps users track their calorie expenditure and manage fitness routines effectively.

2. **Food Category Recommendation:**
    - Users input nutritional values such as energy, protein, fat, carbohydrates, etc., for a food item.
    - The system recommends suitable food categories based on the provided nutritional values.
    - Assists users in making informed dietary choices and maintaining a balanced diet.

3. **Exiting the Program:**
    - Users can exit the program at any time by selecting the exit option from the menu.

## Technologies Used:
- Python
- Scikit-learn (for machine learning models)
- Pandas (for data manipulation)
- Joblib (for model persistence)
- Command Line Interface (CLI) for user interaction

## Future Enhancements:
- Integration with fitness tracking devices for real-time data input.
- Incorporation of additional machine learning models for enhanced prediction accuracy.
- Deployment as a web or mobile application for wider accessibility.

## Instructions for Running the Program:
1. Clone the repository to your local machine.
2. Install the required dependencies (`pip install -r requirements.txt`).
3. Run the Python script (`python main.py`) to launch the interactive prediction system.
4. Follow the on-screen instructions to input data and obtain predictions.

## Conclusion:
The Interactive Health and Fitness Prediction System provides users with valuable insights and recommendations to support their fitness journey. By leveraging machine learning techniques, the system delivers personalized predictions tailored to individual needs, empowering users to make informed decisions for a healthier lifestyle.
