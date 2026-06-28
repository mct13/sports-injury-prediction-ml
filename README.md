# sports-injury-prediction-ml
Predictive Machine Learning pipeline and Explainable AI framework for sports injury profiling.
# Sports Injury Prediction & Performance Analytics Pipeline

An end-to-end Machine Learning and Explainable AI (XAI) framework to predict non-contact injuries in elite sports environments, bridging high-performance ensemble modeling with actionable clinical transparency[cite: 1].

## 🛠️ Tech Stack & Architecture
* **Language:** Python
* **Libraries:** scikit-learn, XGBoost, Random Forest, AdaBoost, SHAP, SMOTE, Pandas, NumPy[cite: 1]
* **Methodology:** CRISP-DM[cite: 1]

## 📊 Key Results & Metrics
* **Model Performance:** Achieved a cross-validated **ROC-AUC score of 0.9972**[cite: 1].
* **Clinical Safety:** Secured a **Recall score of 0.9800**, successfully minimizing dangerous false-negative predictions (reducing missed predictions to just 4 out of 200 test cases)[cite: 1].
* **Class Imbalance Resolution:** Applied **SMOTE** data augmentation to balance a severe 7:1 class risk ratio[cite: 1].

## 🧠 Explainable AI (XAI) Implementation
To eliminate the traditional "black-box" limitations of ensemble models, this architecture integrates **SHAP (SHapley Additive exPlanations)** via TreeExplainer[cite: 1]. This converts complex mathematical metrics into individual Local Risk Profiles that highlight the top 5 injury drivers (e.g., sleep quality, stress levels, cumulative workload) for direct stakeholder intervention[cite: 1].
