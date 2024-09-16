# Titanic Survival Prediction: Enhancing Cruise Ship Safety

## Industry: Tourism & Hospitality  
## Domain: Maritime Safety & Risk Management

### 🚢 Use Case Summary

Leveraging machine learning techniques to analyze historical Titanic passenger data, this project aims to develop predictive models to enhance modern cruise ship safety protocols. The AI-powered "Safety Companion" system is designed to:

1. Identify high-risk passengers
2. Optimize evacuation procedures
3. Personalize safety briefings

### 🎯 Objective

The goal is to develop and compare machine learning models to predict passenger survival probability, forming the foundation of the "Safety Companion" system for cruise ships.

### 🧠 Models

1. **Logistic Regression**: 
   - Provides interpretability and serves as a baseline model.
   - Achieved **79.80% accuracy** on training data.
   - Implemented with feature normalization.

2. **Deep Artificial Neural Network (ANN)**: 
   - Captures complex patterns for higher accuracy.
   - Achieved **82.49% accuracy** on training data.
   - Architecture: Input layer, hidden layers [128, 64, 32], output layer.
   - Used custom 'sriram' activation function for improved performance.

### 📊 Key Features (Ranked by Importance)

1. **Passenger Class (Pclass)**
2. **Sex**
3. **Age**
4. **Family Size**

### 🛠️ Implementation Steps

1. **Data Preprocessing & Exploratory Data Analysis (EDA)**:
   - Normalized all features using Z-score normalization.
   - Focused on key features: Sex, Age, Family Size, and Passenger Class.
   
2. **Model Development**: 
   - Built and trained models (Logistic Regression & Deep ANN).
   
3. **Performance Comparison**: 
   - Evaluated model performance on survival prediction.

4. **Feature Importance Analysis**: 
   - Ranked the impact of each feature on model predictions.

5. **Training Visualization**: 
   - Visualized loss curves for training progression.

### 🌟 Key Findings

1. **Model Performance**:
   - The Deep ANN outperformed Logistic Regression by 2.69 percentage points.
   - This suggests the presence of non-linear relationships in the data.

2. **Feature Importance**:
   - **Passenger Class (Pclass)** is the strongest predictor of survival.
   - **Sex** is almost equally important, supporting the "women and children first" policy.
   - **Age** has moderate importance.
   - **Family Size** is relevant, but less influential.

3. **Survival Factors**:
   - Lower-class passengers were at higher risk.
   - Gender significantly influenced survival chances.
   - Age was a factor but less impactful than class and gender.
   - Family size had some influence on survival predictions.

4. **Non-linear Relationships**:
   - The superior performance of the Deep ANN indicates complex interactions between features.

### 🔜 Implications and Future Enhancements

1. Prioritize risk assessment based on multiple factors, not single attributes.
2. Pay special attention to passengers in lower classes during emergencies.
3. Balance gender and age considerations in evacuation protocols with ethical concerns.
4. Utilize the Deep ANN model for more accurate risk assessments.

#### Future Steps:
- Gather more detailed data on cabin locations and lifeboat proximity.
- Incorporate real-time factors such as passenger location on the ship.
- Develop a user-friendly interface for crew members.
- Conduct simulations to test and refine the system.
- Address ethical implications and potential biases in the model's recommendations.
