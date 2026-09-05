# Udemy Courses Data Analysis (EDA with Python)

An exploratory data analysis project on a dataset containing over 3,600 Udemy courses across four primary domains: Web Development, Business Finance, Musical Instruments, and Graphic Design.

The goal of this project is to clean the raw data, analyze pricing and subscription trends, and explore what factors drive higher student engagement on the platform.

---

## What I Did in This Project

1. **Data Cleaning & Preprocessing:**
   - Handled missing values and dropped duplicate records.
   - Removed invalid records (courses with 0 lectures).
   - Extracted publishing `year` and `month` from timestamps to observe historical trends.

2. **Exploratory Data Analysis (EDA):**
   - **Free vs. Paid Courses:** Looked at course counts and average subscriber numbers. While paid courses make up over 90% of the catalog, free courses pull substantially higher average enrollments (~11.5k vs ~2.4k).
   - **Category Distribution:** Analyzed subscriber volume across categories, with Web Development leading in both total courses and audience reach.
   - **Correlation Heatmap:** Examined linear relationships between subscribers, review volume, and lecture counts.

---

## Key Findings

- **Supply vs. Demand:** Paid courses dominate platform listings, but free courses serve as major enrollment funnels.
- **Top Domain:** Web Development represents the largest audience share on Udemy among the four analyzed fields.
- **Engagement:** High review counts strongly correlate with total subscriber numbers.

---

## Tech Stack

- Python
- Pandas & NumPy (data cleaning & manipulation)
- Matplotlib & Seaborn (visualization)
- Jupyter Notebook / Google Colab

---

## Project Structure

```text
├── Project_Udemy_Courses_Analysis.ipynb   # Main notebook with analysis & plots
├── UdemyCoursesDataset.csv                # Dataset
└── README.md
