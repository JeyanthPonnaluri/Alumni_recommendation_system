# 🎓 Alumni Recommendation System using KNN

## 📌 Project Overview

This project is an AI-powered recommendation engine designed to help users discover and follow similar alumni profiles based on a selected profile. It leverages the **K-Nearest Neighbors (KNN)** algorithm to recommend alumni with similar characteristics such as age, profession, experience, and more.

## 👥 Contributors

- **P. Jeyanth** (Y23CD148)  
- **Sk. Mansoor Basha** (Y23CD168)

## 🔍 Features

- Intelligent alumni profile recommendations based on user selection.
- Uses similarity across multiple features: Age, Gender, Profession, Company, and Experience.
- Easily extendable with Deep Learning (DNN) for better personalization.
- Interactive CLI-based recommendation system.

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Google Colab (Jupyter Notebook)

## 🧠 Algorithm Used

### K-Nearest Neighbors (KNN)
- Computes similarity between alumni profiles using Euclidean distance.
- Encodes categorical features using Label Encoding.
- Recommends top-N most similar alumni profiles.

### Steps Involved:
1. Data Preprocessing
2. Encoding Categorical Features
3. Distance Calculation (Euclidean)
4. Selecting K Neighbors
5. Returning Top-N Recommendations

## 📂 Dataset Structure

| Column              | Description                         |
|---------------------|-------------------------------------|
| Name                | Alumni name                         |
| Age                 | Age in years                        |
| Gender              | Male/Female/Other                   |
| Company Name        | Company currently working in        |
| Working Profession  | Job title or profession             |
| Experience (Years)  | Total years of work experience      |

## 📈 Sample Interaction

💡 Choose one alumni to follow from these:

0: 👤 Aarti Pillai | Product Manager | ByteFusion | 10 yrs
1: 👤 Yuvraj Singh | Consultant | PrimeMatrix | 22 yrs
2: 👤 Anu George | Business Analyst | PixelCorp | 9 yrs
3: 👤 David Kim | Business Analyst | FusionWorks | 8 yrs
4: 👤 Arman Kapoor | Business Analyst | Synapse Systems | 13 yrs

Enter the number (0–4) of the alumni you want to follow: 3

🔍 You followed: David Kim

🎯 Recommended Alumni to Follow:

👤 Tanya Kapoor | AI Specialist | GreenByte | 12 yrs

👤 Aryan Iqbal | Business Analyst | Digimind | 13 yrs ...

pgsql
Copy
Edit

## 📌 Future Enhancements

- Add Deep Neural Network (DNN) recommender for better personalization.
- Implement user feedback loop to improve accuracy.
- Deploy as a web or mobile application.

## 📄 License

This project is intended for **educational purposes** only.
