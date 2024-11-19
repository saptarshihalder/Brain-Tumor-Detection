### **Other Feature Selection Techniques Used**

1. **Mutual Information Classifier**:
   - Identifies features with the highest information gain for classification tasks.
   - **Top features**: `IDH1`, `TP53`, `ATRX`.

2. **Chi-Squared Test**:
   - Measures dependency between features and the target variable.
   - **Selected 20 key features**, including `Age_at_diagnosis`, `IDH1`, and `TP53`.

3. **Principal Component Analysis (PCA)**:
   - Used for dimensionality reduction, retaining 95% variance in the dataset.
   - Reduced 25 features to 21 principal components.
   - **Top contributors**: `BCOR`, `SMARCA4`, `PDGFRA`.

4. **XGBoost Classifier**:
   - Utilized for feature ranking based on importance scores.
   - **Highly ranked features**: `IDH1`, `TP53`, `ATRX`, `EGFR`.
