## Workplace Accident Prediction
### 📌 Project Overview

This project analyzes unsafe acts, incidents, and worker-related safety issues to predict total incidents and injuries in the workplace.
It applies correlation analysis, feature importance ranking, and regression models (Linear Regression, Decision Tree, Random Forest) to understand the impact of unsafe acts and workers on incident rates.

### 📂 Dataset Composition

**Features include:**

Unsafe Acts (UA) – Fall_UA, Trip_UA, Bump_UA, Hit_UA, Stuck_UA, Cut_UA, Muscle_UA

Incidents/Injuries (II) – Fall_II, Trip_II, Bump_II, Hit_II, Stuck_II, Cut_II, Muscle_II

Workers – Number of workers per day

Total_Unsafe_Acts – Daily sum of unsafe acts

Total_Incidents_Injuries – Daily incidents/injuries (target variable)

### ⚙️ Workflow

Correlation Analysis – Identify strong relationships (Workers, Unsafe Acts → Incidents/Injuries).

Feature Importance – Random Forest ranks Total_Unsafe_Acts as most influential.

Regression Models – Linear Regression, RANSAC, Decision Tree, Random Forest.

Model Evaluation – Metrics: MSE and R².

### 📊 Results

Linear Regression: Train R² = 0.665, Test R² = 0.609

Decision Tree: Test R² ≈ 0.54

Random Forest: Test R² ≈ 0.70 (best performance)
