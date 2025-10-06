# 🌾 Cropify — Crop Yield Prediction System

## 🧠 Overview
**Cropify** is a machine learning-based system designed to predict **crop yield** using key **environmental** and **soil** parameters such as rainfall, temperature, and soil type.  
This project aims to assist farmers, agricultural planners, and researchers in optimizing crop production by providing accurate yield forecasts based on real-world data.

---

## 🚀 Features
- 📊 **Data Analysis:** Cleaned and preprocessed datasets containing environmental and soil information.  
- 🌱 **Predictive Modeling:** Implemented and compared multiple regression models including:
  - Linear Regression  
  - Random Forest Regressor  
- ⚙️ **Model Optimization:** Tuned hyperparameters to improve model accuracy and reliability.  
- 🧩 **Data Handling:** Addressed missing and inconsistent data to ensure robust model training.  
- 📈 **Performance Evaluation:** Evaluated models using metrics such as R² score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

---

## 🧰 Tech Stack
- **Programming Language:** Python  
- **Libraries:**  
  - `Pandas` — Data manipulation and preprocessing  
  - `NumPy` — Numerical computations  
  - `Scikit-learn` — Machine learning models and evaluation  
  - `Matplotlib / Seaborn` — Data visualization (optional)

---

## 📂 Project Structure
Cropify/
│
├── data/ # Dataset files (CSV or Excel)
├── notebooks/ # Jupyter notebooks for analysis
├── models/ # Saved ML models (optional)
├── cropify.py # Main script or model training file
├── requirements.txt # List of dependencies
└── README.md # Project documentation

---

## 🔍 Workflow
1. **Data Collection:** Environmental and soil factor datasets were gathered and explored.  
2. **Data Preprocessing:** Cleaned data by handling missing values and removing inconsistencies.  
3. **Feature Selection:** Chose the most relevant attributes influencing crop yield.  
4. **Model Training:** Trained multiple regression models.  
5. **Model Evaluation:** Compared models and selected the best performer (Random Forest).  
6. **Prediction:** Generated yield predictions for unseen data.

---

## 📊 Results
- The **Random Forest** model outperformed other algorithms, offering high prediction accuracy.  
- Achieved significant improvement in model stability through preprocessing and hyperparameter tuning.

---

## 🧾 Future Enhancements
- Integrate **real-time weather data APIs** for dynamic predictions.  
- Develop a **web dashboard** (using Flask/FastAPI + React) for user interaction.  
- Expand dataset with additional soil and climate parameters for higher precision.

---

## 🤝 Contribution
Contributions, issues, and feature requests are welcome!  
Feel free to fork this repository and submit a pull request.

---

## 🧑‍💻 Author
**Anushka Jaiswal**  
🎓 B.Tech in Computer Science and Engineering  
🔗 [GitHub](https://github.com/anushka04-j) |

---

## 🪴 License
This project is open-source and available under the [MIT License](LICENSE).

