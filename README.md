# Healthcare-Premium-Pediction

# Insurance Premium Prediction

---

- The initial model struggled to predict premiums accurately for individuals aged ≤ 25.
- To address this, the dataset was split into two segments: `age > 25` and `age ≤ 25`.
- A dedicated model was first built for the older group.
- Additional data was later obtained for the younger group, enabling a more expressive model with improved performance.
- Finally, the models were harmonized to support a **unified deployment pipeline** capable of serving all age groups with consistent feature input.

---

## 🧪 Workflow Overview

Each notebook follows a structured machine learning workflow:

### 🔹 1. Exploratory Data Analysis (EDA)
- Explored distributions, correlations, and feature relationships.

### 🔹 2. Data Cleaning
- Handled missing values, duplicates, and outliers.
- Ensured data consistency and integrity.

### 🔹 3. Feature Scaling
- Applied `Scalings` to normalize numerical features and prepare for downstream modeling steps.

### 🔹 4. Feature Engineering & Encoding
- Encoded categorical variables using appropriate strategies.
- Created or refined features to enhance model accuracy and ensure compatibility between datasets.

### 🔹 5. Multicollinearity Check
- Applied **Variance Inflation Factor (VIF)** to remove redundant and highly correlated features.

### 🔹 6. Model Development
- Trained and compared several classification algorithms:
  - `LogisticRegression`
  - `RandomForestClassifier`
  - `XGBClassifier`


---
