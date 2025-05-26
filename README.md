# 🔥 Calories Burn Prediction Using Machine Learning

This project aims to predict the number of calories burned during physical activity using various machine learning regression algorithms. Accurate calorie predictions can support personal fitness tracking and promote healthier lifestyles.

## 📊 Dataset
The dataset used in this project consists of features such as:

- Gender
- Age
- Height
- Weight
- Duration of exercise
- Heart rate
- Body temperature

These attributes were used to train models that predict the total calories burned.

## 🧠 Machine Learning Models Used

We evaluated the following regression algorithms:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- AdaBoost Regressor
- Gradient Boosting Regressor
- XGBoost Regressor

## 🔬 Data Preprocessing

- Encoded categorical variables (`Gender`)
- Dropped highly correlated or redundant features (`Weight`, `Duration`)
- Scaled features using `StandardScaler`
- Split data into training and validation sets

## 📈 Evaluation Metrics

Each model was evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)
- Mean Absolute Error (MAE)

Cross-validation was also applied using 2-fold and 10-fold splits.

## ✅ Best Model

**XGBoost Regressor** achieved the best performance with:

- **MSE**: 204.20
- **RMSE**: 14.29
- **MAE**: 10.12
- **R² Score**: 0.95

## 📊 Visualizations

The project includes:

- Correlation heatmaps
- Feature distribution plots
- Scatterplots for feature-target relationships

## 📁 Project Structure

- `project.py` — main code for preprocessing, training, and evaluating models
- `exercise.csv` — dataset (not included here, replace path as needed)
- `README.md` — project documentation

## 📚 References

Research and comparisons based on multiple academic papers, with special focus on practical model performance.

---

## 🧑‍💻 Authors

Team 24, Faculty of Computer Science
Misr International University, Egypt
