# Flight-Fare-Prediction-Using-Machine-Learning

A machine learning project to predict airline ticket prices using real-world flight data. Includes data cleaning, exploratory analysis, and model comparisons (Linear Regression, Random Forest, XGBoost, etc.) to identify key factors affecting fare variation and improve pricing insights for airlines and travelers.

---

## 📌 Project Objective

To forecast flight ticket prices using a dataset of flights from January 16, 2023 to March 6, 2023, and identify which factors most significantly impact airfare fluctuations.

---

## 📊 Dataset

The dataset includes 450,000+ flight records with the following features:

- `Date_of_Journey`
- `Airline`
- `Flight_Code`
- `Source` and `Destination`
- `Departure` and `Arrival`
- `Total_Stops`
- `Class`
- `Duration_in_hours`
- `Days_left`
- `Fare` (Target)

---

## 🔍 Exploratory Data Analysis (EDA)

Key findings:
- **Vistara** has the highest number of trips; **IndiGo** runs the most frequent flights.
- **Economy class** dominates bookings.
- **Evening flights** are more expensive.
- **Monday** sees peak fare prices.
- Considerable fare variability across times and days.

---

## 🧹 Data Preprocessing

- Removed 11,201 duplicate records
- Verified 0 missing values
- Label encoding for categorical variables
- Selected top influencing features: `Airline`, `Source`, `Destination`, `Fare`

---

## 🧠 Models Used

| Model                   | MAE        | RMSE       | R² Score |
|------------------------|------------|------------|----------|
| Linear Regression       | 16,880.08  | 20,390.03  | 0.0055   |
| Decision Tree Regressor| 14,606.74  | 18,455.97  | 0.1852   |
| Random Forest Regressor| 14,605.49  | 18,456.17  | 0.1852   |
| Extra Trees Regressor  | 14,606.77  | 18,455.97  | 0.1852   |
| XGBoost Regressor      | 14,824.09  | 18,577.12  | 0.1745   |

> ✅ Best Performing Model: **Random Forest Regressor**

---

## 📈 Visualizations

- Airline-wise trip and flight volume
- Box plots for timings vs fare
- Fare variation by weekday
- Correlation heatmaps
- Predicted vs actual fare curves

---

## 🔄 Limitations

- Models explain less than 20% of fare variation
- Important variables like holiday impact, international flag, or promotional pricing not included

---

## 🚀 Recommendations

- Integrate more granular data (e.g., booking time, holidays)
- Use advanced models (neural networks, boosted ensembles)
- Enable dynamic pricing strategies using fare prediction insights

---

## 📎 Report

Full PDF report available here: [Flight Fare Prediction Report.pdf](./Flight%20Fare%20Prediction%20Report.pdf)

---

## 👨‍💻 Author

**Deepak Arumugam Vivekanandan**  
📧 deep199907@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/deepakv1e7d6/)
# Flight-Fare-Prediction-Using-Machine-Learning

A machine learning project to predict airline ticket prices using real-world flight data. Includes data cleaning, exploratory analysis, and model comparisons (Linear Regression, Random Forest, XGBoost, etc.) to identify key factors affecting fare variation and improve pricing insights for airlines and travelers.

---

## 📌 Project Objective

To forecast flight ticket prices using a dataset of flights from January 16, 2023 to March 6, 2023, and identify which factors most significantly impact airfare fluctuations.

---

## 📊 Dataset

The dataset includes 450,000+ flight records with the following features:

- `Date_of_Journey`
- `Airline`
- `Flight_Code`
- `Source` and `Destination`
- `Departure` and `Arrival`
- `Total_Stops`
- `Class`
- `Duration_in_hours`
- `Days_left`
- `Fare` (Target)

---

## 🔍 Exploratory Data Analysis (EDA)

Key findings:
- **Vistara** has the highest number of trips; **IndiGo** runs the most frequent flights.
- **Economy class** dominates bookings.
- **Evening flights** are more expensive.
- **Monday** sees peak fare prices.
- Considerable fare variability across times and days.

---

## 🧹 Data Preprocessing

- Removed 11,201 duplicate records
- Verified 0 missing values
- Label encoding for categorical variables
- Selected top influencing features: `Airline`, `Source`, `Destination`, `Fare`

---

## 🧠 Models Used

| Model                   | MAE        | RMSE       | R² Score |
|------------------------|------------|------------|----------|
| Linear Regression       | 16,880.08  | 20,390.03  | 0.0055   |
| Decision Tree Regressor| 14,606.74  | 18,455.97  | 0.1852   |
| Random Forest Regressor| 14,605.49  | 18,456.17  | 0.1852   |
| Extra Trees Regressor  | 14,606.77  | 18,455.97  | 0.1852   |
| XGBoost Regressor      | 14,824.09  | 18,577.12  | 0.1745   |

> ✅ Best Performing Model: **Random Forest Regressor**

---

## 📈 Visualizations

- Airline-wise trip and flight volume
- Box plots for timings vs fare
- Fare variation by weekday
- Correlation heatmaps
- Predicted vs actual fare curves

---

## 🔄 Limitations

- Models explain less than 20% of fare variation
- Important variables like holiday impact, international flag, or promotional pricing not included

---

## 🚀 Recommendations

- Integrate more granular data (e.g., booking time, holidays)
- Use advanced models (neural networks, boosted ensembles)
- Enable dynamic pricing strategies using fare prediction insights

---

## 📎 Report

Full PDF report available here: [Flight Fare Prediction Report.pdf](./Flight%20Fare%20Prediction%20Report.pdf)

---

## 👨‍💻 Author

**Deepak Arumugam Vivekanandan**  
📧 deep199907@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/deepakv1e7d6/)
