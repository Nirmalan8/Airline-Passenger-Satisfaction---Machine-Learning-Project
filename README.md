#  Airline Passenger Satisfaction - Machine Learning Project

##  Project Overview
This project analyzes **airline passenger satisfaction** using machine learning models.  
The aim is to identify key factors influencing passenger satisfaction and predict whether a passenger is satisfied or dissatisfied based on service and flight-related features.

The dataset contains passenger survey data including **flight distance, service ratings, seat comfort, and more**.  
This analysis can help airlines improve their services and overall customer experience.

---

##  Dataset
- **Source:** [Kaggle - Airline Passenger Satisfaction]
- **Rows:** ~130,000
- **Columns:** 25 (categorical & numerical)
- **Target Variable:** `satisfaction` (Satisfied / Neutral or dissatisfied)

---

##  Workflow
1. **Data Understanding & Cleaning**
   - Checked for null values & data types
   - Handled missing values
   - Converted categorical features to numerical (label encoding / one-hot encoding)
2. **Exploratory Data Analysis (EDA)**
   - Visualized class distribution
   - Analyzed relationships between features & satisfaction
   - Correlation heatmap
3. **Feature Engineering**
   - Standardized numerical features
   - Removed irrelevant columns
4. **Model Building**
   - Tested multiple algorithms:
     

---

##  Results
- **Best Model:** RandomForest,Extreme Forest Classifier 
- **Accuracy:** 96%  
- **Key Features Influencing Satisfaction:**
  - Inflight WiFi service
  - Seat comfort
  - Food and drink
  - On-board service

---

## Tech Stack
- **Python** 
- **Libraries:**
  - Pandas, NumPy
  - Matplotlib, Seaborn
  - Scikit-learn
  

---
## Future Improvements
- Try deep learning models for comparison

- Hyperparameter tuning for even better accuracy

- Build a web app for real-time predictions

---
