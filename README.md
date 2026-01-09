
**Objective:** Developed predictive models to estimate expected insurance losses and claim probabilities, addressing the industry challenge of premium mispricing and adverse selection.

**Data Engineering:** Processed a dataset of 37,451 policy records by engineering features such as policy duration and driver experience, while addressing zero-inflated and right-skewed distributions common in insurance data.

**Preprocessing:** Implemented advanced data cleaning techniques, including removing outliers based on IQR thresholds and imputing missing categorical values (Fuel Type) using supervised classification models like Decision Trees and XGBoost.

**Modeling:** Utilized the Tweedie Loss Function to train multiple algorithms, including LightGBM, XGBoost, and Neural Networks, for both regression (Loss Cost) and classification (Claim Status) tasks.

**Results:** Achieved optimal performance with a Neural Network for regression tasks (RMSE: 458.92) and XGBoost for classification tasks (ROC-AUC: 0.85), enabling more accurate premium pricing strategies.
