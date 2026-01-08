Cancer Risk Prediction with Machine Learning
-------------------------------------------------------

<img width="800" height="400" alt="2025-08-15_MLSS_Cover" src="https://github.com/user-attachments/assets/93a6dc27-648f-4f45-861a-509a0022342e" />
<pre></pre>

This repository contains a machine learning project that predicts an individual’s cancer risk level (low, medium, or high) based on clinical and demographic features.

The model is built using standard preprocessing techniques and evaluated to identify the best performing algorithm for risk classification.

---

🧠 Overview

Cancer is a complex disease influenced by multiple factors including lifestyle, genetics, and medical history. Accurately identifying individuals at higher risk can support early monitoring, intervention, and personalized healthcare approaches. This project implements a machine learning model to estimate cancer risk categories using labeled patient data.

---

🚀 Features

- 📊 **Data preprocessing:** Cleaning, feature scaling, and encoding for optimal model training.
- 🤖 **Model comparison:** Evaluates multiple classifiers to identify the best fit.
- 📈 **Best performing model:** Logistic Regression with tuned parameters achieved the highest predictive accuracy.
- 🔍 **Risk prediction:** Outputs categorical risk levels (low/medium/high) for new patient profiles.

---

📁 Repository Structure

├── Assignment.ipynb # Main notebook with analysis, modeling, evaluation
├── README.md # Project overview and instructions
└── requirements.txt # Python dependencies


---

🧪 Model Performance

After comparing several machine learning algorithms, **Logistic Regression** was selected as the best performer.

- **Training accuracy:** ~0.9066  
- **Tuned validation accuracy:** ~0.8600

The model classifies patient records into risk levels that can support further clinical analysis or patient education.

---

 🛠 Usage

To use the model for predicting cancer risk:

1. Clone the repository
   ```
   git clone https://github.com/jefflung/cancer-risk-factors.git
   cd cancer-risk-factors

2. Install dependencies
   ```
   pip install -r requirements.txt
   ```

3. Load and run the prediction code
   ```
   from sklearn.preprocessing import StandardScaler
   # load your model and new patient data
   prediction = best_model.predict(scaler.transform(new_data))
   risk_category = le_risk.inverse_transform(prediction)
   print("Predicted Risk Level:", risk_category)
   ```
---

📌 Notes & Limitations

This is a proof-of-concept model. Actual clinical deployment requires rigorous validation and ethical review.

Model performance depends on the quality and representativeness of the dataset.

New features or datasets may improve accuracy and generalizability.

---

📚 References

Machine learning libraries (scikit-learn, pandas, numpy)

Standard risk factor modeling approaches in health analytics

---

👩‍💻 Contact

Developed by jefflung

Feel free to open issues or submit pull requests for improvements!
