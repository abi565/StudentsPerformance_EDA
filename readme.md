# 🎓 Students Performance EDA and Visualization

**Course Code:** U21ADP05  
**Course Title:** Exploratory Data Analysis and Visualization  
**Student:** Abinaya I  
**Roll No:** 23AD001  
**Institution:** KPR Institute of Engineering and Technology  
**Batch:** 2023–2027  

---

## 📘 Project Overview
This project performs a complete **Exploratory Data Analysis (EDA)** and **Visualization** on the **Students Performance in Exams** dataset (Kaggle source).  
The goal is to analyze factors affecting student academic performance using both **numerical and textual features**, and to implement a **deep learning model (MLP)** for predicting performance levels.

The project satisfies all requirements from the Assignment II instructions — including preprocessing, encoding, visualization (5+ plots), model building, and evaluation.

---

## 🧩 Folder Structure
StudentsPerformance_EDA/
├──  StudentsPerformance_augmented.csv
├── 01_EDA_and_Preprocessing.ipynb
├── visuals/
│ ├── heatmap.png
│ ├── wordcloud.png
│ ├── sentiment_scatter.png
│ ├── roc_curve.png
│ └── accuracy_loss_curves.png
├── Assignment_II_EDA_Report_ABINAYA.pdf
├── README.md
└── requirements.txt


---

## 🧠 Key Features
- Cleaned and processed dataset with **20+ features**
- Added **textual feedback** and derived **sentiment polarity**
- Conducted **comprehensive EDA** with correlation, boxplots, distributions, and text analysis
- Built **MLP deep learning model** using TensorFlow/Keras
- Included **evaluation visuals**: Accuracy, Loss, Confusion Matrix, ROC Curve
- Fully documented with a **Word report** and a **GitHub repository**

---

## 📊 Visualizations
1. Distribution of Math, Reading, and Writing Scores  
2. Correlation Heatmap of Numeric Features  
3. Boxplots of Performance by Gender and Test Prep Course  
4. WordCloud of Student Feedback  
5. Sentiment vs Total Score Scatterplot  
6. ROC Curve and Confusion Matrix of Model  and more.

---

Libraries Used

pandas, numpy – data manipulation
matplotlib, seaborn, wordcloud – visualization
textblob – sentiment analysis
scikit-learn – preprocessing and metrics
tensorflow / keras – deep learning model

---

References

Kaggle: Students Performance in Exams Dataset
Scikit-learn Documentation
TensorFlow Documentation
TextBlob Library
Matplotlib & Seaborn Guides
