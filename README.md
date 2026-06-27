# Medical Appointment No Shows: Predictive Analysis Using Machine Learning 🏥📊

An advanced data science and machine learning project conducted at **Majmaah University** (College of Computer Science and Information Taekwondo/Information Systems). This project analyzes patient attendance patterns using a dataset of **110,527 records** to predict and mitigate no-show behaviors in healthcare scheduling.

---

## 👥 Authors & Team
- **Researchers:** Raneem Almutairi, Joud Alzaid, Shahad Alotaibi, **Shaden Awaji**
- **Supervisor:** Dr. Amal Aljohani
- **Institution:** Majmaah University

---

## 📌 Project Overview & Objectives
Missing medical appointments reduces hospital efficiency and wastes valuable medical resources. This project explores the core factors influencing patient attendance and evaluates multiple machine learning models to forecast no-shows accurately.

### Key Research Questions:
1. Can machine learning models accurately predict whether a patient will miss an appointment?
2. Which clinical or demographic factors affect attendance the most?
3. Does receiving SMS reminders directly improve patient attendance?
4. Do longer waiting times between booking and the actual appointment increase missed visits?

---

## 🛠️ Project Methodology
The analytical pipeline follows a structured data science workflow:
1. **Raw Data Acquisition:** Sourced from the Kaggle Medical Appointment No Shows dataset.
2. **Data Preprocessing & Cleaning:** Handling missing values, modifying structures, and feature selection.
3. **Data Partitioning:** Splitting data into training and testing sets.
4. **Model Building & Testing:** Implementing and evaluating baseline and ensemble models.

---

## 📊 Experimental Results & Model Evaluation

The models were evaluated based on **Accuracy, Precision, Recall, F1-Score, and AUC-ROC** metrics. Below is the comparative performance analysis:

| Model Algorithm | Accuracy | Precision | Recall | F1-Score | AUC | ROC |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Decision Tree** | 80.3% | 80.3% | 100% | 0.8907 | 0.793 | 0.790 |
| **Random Forest** | 79.8% | 80.4% | 98.9% | 0.8872 | 0.852 | 0.850 |
| **Logistic Regression** | 80.0% | 80.3% | 99.5% | 0.8889 | 0.756 | 0.760 |
| **Naive Bayes** | 64.4% | 56.6% | 87.0% | 0.6860 | 0.727 | 0.730 |

### Key Findings:
- **Random Forest** provided the most stable and reliable prediction performance, particularly achieving the highest AUC-ROC (0.852), demonstrating strong classification stability.
- Predictive features such as waiting periods and SMS notification integration significantly bolster overall forecasting stability.

---

## 🔮 Future Work
- Incorporating larger and more recent localized healthcare datasets.
- Applying advanced deep learning architectures for behavior forecasting.
- Integrating feature engineering optimization to scale accuracy further.
- Developing real-time integrated prediction dashboards for hospitals.

---

## 📚 References
1. Kaggle, "Medical Appointment No Shows Dataset," 2016.
2. Pedregosa et al., "Scikit-learn: Machine Learning in Python," *JMLR*, 2011.
3. Haq, M. A., & Khan, M. A. R., "Machine Learning Approaches to Predict No-Shows in Saudi Rehabilitation Hospitals," *Saudi J. Health Syst. Res.*, 2025.

   ---

## 📜 Certificates & Recognitions

This project was officially recognized and presented at the **Data Science Expo 2026** hosted by the College of Computer and Information Sciences at **Majmaah University**.

[Shaden Awaji  .jpg.pdf](https://github.com/user-attachments/files/29424677/Shaden.Awaji.jpg)

- **Awarded To:** Shaden Awaji
- **Event:** Data Science Expo 2026
- **Issued By:** College of Computer and Information Sciences, Majmaah University (Department Chair: Dr. Amal Aljohani)
