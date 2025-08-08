# Social Media Usage & Emotional Wellbeing

Exploring how online behavior relates to emotional states.

---

## 📊 Dataset Description
- **Source**: Provided dataset by AI Inventor Emirhan BULUT (for educational purposes).
- **Size**: ~1,000 rows × 10 columns.
- **Key Variables**:
  - Age, Gender, Platform, Daily Usage Time, Posts Per Day, Likes, Comments, Messages, Dominant Emotion

---

## 🎯 Research Goal
Understand how platform choice, time spent online, and activity levels relate to users’ emotional wellbeing.

---

## 🔍 Steps Taken
- **Data Cleaning**:
  - Removed missing values
  - Corrected invalid ages
  - Set `User_ID` as index
  - Checked for duplicates
- **Exploratory Data Analysis (EDA)**:
  - Univariate: Distributions of numerical and categorical variables
  - Bivariate: 
    - Emotions by Platform
    - Usage Time vs. Emotion
    - Activity Levels vs. Emotion
- **Visualization**:
  - Matplotlib & Seaborn for plots

---

## 📌 Main Findings
- **Platform matters**: Instagram users report more happiness; Twitter and Facebook show more anxiety/neutral emotions.
- **Time matters**: Negative emotions linked to longer daily usage.
- **Activity matters**: Happier users are more active; bored or sad users engage less.

---

## 🛠 How to Reproduce
**Requirements**:
- Python 3.10+
- pandas, matplotlib, seaborn, sqlite3 (optional)

**Steps**:
1. Clone the repo  
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
