# 📊 Udemy Courses Analysis

This project presents an interactive Power BI dashboard analyzing Udemy course data to uncover trends in **subscribers**, **revenue**, and **course distribution** across different **levels** and **subjects**. The analysis provides actionable insights to support strategic decisions for online course platforms.

---

## 🚀 Project Summary

This dashboard showcases insights from **3,672 Udemy courses**, capturing a total of:

- 👥 **12 million** subscribers  
- 📚 **575,000** reviews  
- 💰 **$244,000** in revenue  
- ⭐ **Average rating**: 3.1

It breaks down performance by **subject**, **course level**, **year**, and **payment type** (free vs. paid), offering a comprehensive view of Udemy’s course landscape.

---

## 📂 Dataset

**Source:** Udemy Courses Dataset

### 🔑 Key Data Fields:
- `course_id`: Unique identifier for each course  
- `course_title`: Title of the course  
- `price`: Course price (USD)  
- `level`: Difficulty level (e.g., Beginner, All Levels)  
- `subject`: Main subject category (e.g., Web Development, Business)

---

## 🛠 Tools Used

- **Power BI** – Interactive dashboard & data visualization  
- **Power Query** – Data cleaning and transformation  
- **Excel** – Raw data storage and initial inspection

---

## 🧹 Data Cleaning & Transformation

**Key Steps:**

- ✅ Removed unnecessary columns  
- ✅ Filtered out rows with missing values  
- ✅ Changed data types appropriately (e.g., `price` to numeric, `course_title` to text)  
- ✅ Handled null values in key fields  
- ✅ Combined four individual data sheets into one unified dataset  
- ✅ Merged datasets based on `course_id`  
- ✅ Removed duplicate records to ensure uniqueness

---

## 🔍 Insights & Observations

### 📊 Key Findings

- **Web Development** dominates with **8 million** subscribers  
- **Business Finance** and **Graphic Design** follow, with **1.9M** and **1.1M** respectively  
- A sharp **revenue spike in 2016** suggests increased course creation or pricing shifts  
- **Beginner** and **All-Level** courses attract the most subscribers and revenue  
- **69.56%** of users choose **paid** courses, indicating strong monetization potential

### 💡 Recommendations

- **Expand Web Development Courses** – Leverage high demand with specialized or advanced content  
- **Diversify Subject Areas** – Explore underrepresented or emerging fields  
- **Investigate 2016 Spike** – Analyze what triggered growth to replicate success  
- **Monetize High-Traffic Courses** – Add premium tiers, certifications, or mentorship  
- **Segment User Base** – Tailor strategies for paid vs. free users

---

## 📁 Folder Structure

```text
📂 Udemy-Courses-Analysis/
├── 📄 README.md
├── 📂 Data/
│   └── 🧮 Udemy Courses Dataset.xlsx
├── 📂 Analysis/
│   └── 📉 Udemy Courses Analysis.pbix
├── 📂 Outputs/
│   └── 📊 Udemy Courses Dashboard.pdf
└── 📂 Visuals/
    └── 🖼️ Dashboard Preview.png
```
![Dashboard Preview](https://github.com/Sarah-Aladwar/Udemy-Courses-Analysis/raw/main/Visuals/Dashboard%20Preview.PNG)
