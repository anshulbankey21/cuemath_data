# 📊 Cuemath India Data Analyst Project

This project focuses on analyzing and deriving insights from a realistic Cuemath student-tutor dataset in India, containing 110,000+ records with up to 30% missing values.

## 🔧 Project Objective

To simulate real-world data analyst tasks including:
- Data Cleaning and Imputation
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Insight Generation

## 📁 Dataset Overview

The dataset includes the following columns:

- `student_id`, `name`, `age`, `quiz_score`, `city`
- `Enrollment_Date`, `Last_Login`, `course_enrolled`
- `weekly_progress(%)`, `final_grade`, `tutor_name`
- `feedback_score`, `active_status`, `tutor_id`
- `grade`, `time_spent_minutes`, `parent_rating`

🧩 **Total Rows**: 110,000+  
⚠️ **Missing Values**: ~30% across key fields

---

## 🧹 Data Cleaning Process

- Filled missing `city` and `tutor_name` with default values (`"online"` and `"Guest_lecture"`)
- Imputed `last_login` using `enrollment_date`
- Used statistical and logical imputation for:
  - `quiz_score`, `weekly_progress(%)`, `feedback_score`, `time_spent_minutes`, `parent_rating`
- Feature engineering using lambda and correlation-based imputation

---

## 📊 Exploratory Data Analysis (EDA)

### ✅ Key Questions Answered:

1. Total active vs inactive students
2. Top enrolled courses
3. Distribution of age groups
4. Most common cities and online enrollments
5. Top tutors by feedback score and number of students
6. Monthly enrollment and login trends
7. Time spent vs weekly progress correlation
8. Age group analysis (11–15 most common)
9. Performance comparison between cities
10. Student activity per month
11. Grade-based segmentation (Excellent, Very Good, Good, Less)
12. Feedback vs parent rating correlation

> 📈 Charts: Bar plots, histograms, pie charts, boxplots, and heatmaps.

---

## 🧠 Insights Discovered

Student Engagement: Majority of students are active users, with significant time spent on the platform.

Top Tutor: Tutor ID tut019 has the highest number of enrolled students, indicating strong engagement or popularity.

Most Rated Tutor: Mr. Manish received the highest number of feedback scores and parent ratings, highlighting high-quality instruction.

Seasonal Trends:

May sees the highest student activity.

April has the maximum enrollments, while June shows a noticeable decline.

Course Popularity: "Geometry Essentials" is the most enrolled course across users.

Age Demographics: The 11–15 age group dominates the platform's user base.

Location-Based Engagement:

Students from Online mode are more prevalent and active compared to physical cities.

Bangalore students perform best in Trigonometry (Quiz Scores).

Pune students have the lowest average scores in Math Puzzles.

Consistent Usage: Many students are regularly using the app, reflecting strong platform stickiness.

---

## 🏗️ Feature Engineering

- `grade_level`: Categorized performance (Excellent, Very Good, etc.)
- `inactive_days`: Duration between enrollment and last login
- `days_since_login`: Time since last platform usage

---

## 🧰 Tools & Libraries

- `Python`, `Pandas`, `Matplotlib`, `Seaborn`, `NumPy`
- Jupyter Notebook for development and presentation

---

## ✅ Status

✔️ Data Cleaning Completed  
✔️ EDA and Insights Extracted  
✔️ Project Ready for Upload 🚀

---

## 📌 Author

**ANSHUL BANKEY**  
_B.Tech in CSE with specialization in Gaming Technology  
Aspiring Data Analyst | Python Enthusiast | 


---

## 📂 License

This dataset is artificially generated for educational purposes. No real Cuemath student data has been used.
