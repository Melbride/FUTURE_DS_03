# 📓 College Event Feedback Analysis

## 📌 Project Overview
This project analyzes student satisfaction survey data collected from multiple courses.  
The main objectives are to:

- Clean and prepare feedback data from a Google Form export.  
- Analyze ratings (1–5 scale) to find patterns of satisfaction.  
- Visualize feedback distribution using charts and graphs.  
- Identify top strengths and areas for improvement in teaching and course delivery.  
- Provide actionable recommendations for event/course organizers.  

---

## 📂 Dataset
- **Source:** Student Satisfaction Survey (CSV format)  
- **Size:** 580 rows × 11 columns  

**Key Columns:**
- `Questions` → Feedback questions answered by students  
- `Average` → Average rating score (1–5 scale)  
- `Percentage` → Converted satisfaction percentage (20%–100%)  
- `Course Name` → Student course/program  

---

## 🛠️ Steps Performed

### 1. Data Cleaning & Preparation
- Removed duplicates and irrelevant columns (`SN`, `Total Configured`, `Average/Percentage`).  
- Cleaned special characters from questions.  
- Split rating data into `Average` and `Percentage` columns.  
- Converted values to numeric for analysis.  

### 2. Exploratory Data Analysis (EDA)
- Distribution of average ratings (histogram).  
- Average rating per question and per course.  
- Word cloud of feedback questions.  
- Boxplots comparing ratings across courses.  

### 3. Insights Extracted
**Top-rated aspects (highest satisfaction):**
- Fairness of the internal evaluation process.  
- Teacher communication skills.  
- Teacher preparation for classes.  

**Lowest-rated aspects (areas needing improvement):**
- Use of ICT tools in teaching.  
- Teacher support in cognitive/social/emotional growth.  
- Identifying strengths and encouraging challenges.  

**Course performance:**
- Highest rated → FYBA, MSc Analytical Chemistry, TYBSC.  
- Lowest rated → MSc Data Science (1), SYBSC, MSc Physics (3).  

**Variability in ratings:**
- Some courses showed wide variation in feedback (higher disagreement among students).  

**Percentage trends:**
- Majority of courses scored above **80% satisfaction**.  

---

## 📊 Visualizations
The notebook includes:
- Histogram of average ratings.  
- Boxplots comparing course satisfaction.  
- Word cloud of feedback questions.  
- Tables summarizing top & bottom questions.  

---

## ✅ Recommendations
- **Strengthen ICT integration** → Increase use of multimedia and digital tools in teaching.  
- **Focus on mentoring** → Support students’ social, emotional, and cognitive development.  
- **Leverage strengths** → Continue strong practices in fairness, preparation, and communication.  
- **Target underperforming courses** → Offer faculty development workshops in courses with lower ratings.  
