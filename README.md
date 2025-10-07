# From-Experience-to-Earnings
# 💼 Salary Data Analysis using PySpark

## 📘 Project Overview
This project performs **Salary Data Analysis** on an employee dataset using **PySpark** to derive insights into compensation trends.  
It aims to identify how factors such as **experience, education level, gender, and job role** impact salary distribution.  
The results can help organizations make informed decisions about **pay equity**, **workforce planning**, and **HR policies**.

---

## 🎯 Objectives
- Analyze and visualize salary data for 1,000 employees.  
- Identify relationships between **experience**, **education**, and **salary**.  
- Compare **average salaries by gender** to assess pay gaps.  
- Provide actionable **insights and recommendations** for HR departments.  

---

## 🗂️ Dataset Information
**Dataset Name:** `Salary_Data.csv`

**Attributes:**
| Column Name | Description |
|--------------|-------------|
| Age | Age of the employee |
| Gender | Male or Female |
| Education_Level | Qualification (Bachelor’s, Master’s, etc.) |
| Job_Title | Employee role/designation |
| Years_of_Experience | Work experience in years |
| Salary | Annual salary in INR |

**Dataset Quality:**
- ✅ No missing values  
- ✅ Balanced data (across gender, job title, education)  
- ✅ Ready for PySpark analysis  

---

## 🧰 Tools and Technologies
- **Programming Language:** Python  
- **Big Data Framework:** Apache Spark (PySpark)  
- **Libraries Used:** Pandas, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook / Google Colab  

---

## ⚙️ Steps Performed
1. **Data Loading**
   - Created a Spark session and loaded `Salary_Data.csv`.
   - Verified schema and displayed sample data.

2. **Data Exploration**
   - Displayed summary statistics.
   - Checked salary distribution and trends.

3. **Filtering**
   - Identified employees with salary > ₹50,000.
   - Extracted female employees with >5 years of experience.

4. **Aggregation & Analysis**
   - Calculated average, minimum, and maximum salary.  
   - Grouped data by **Gender**, **Education**, and **Experience** to analyze pay trends.

5. **Visualization**
   - Created salary distribution and comparison graphs.
   - Displayed gender-based and education-based salary patterns.

---

## 📊 Key Insights
- **Experience vs Salary:** Direct positive correlation — higher experience leads to higher pay.  
- **Education Level:** Postgraduates and specialized degrees have higher average salaries.  
- **Gender Gap:** Slight difference in average salaries between genders.  
- **Job Titles:** Specialized and senior roles show higher salary clusters.  

---

## 💡 Recommendations
- Ensure **pay equity** through periodic analysis.  
- Encourage **upskilling and advanced education** for better compensation.  
- Use salary data insights to design **transparent pay structures**.  
- Implement **predictive analytics** to forecast future salary trends.

---

## 🚀 Future Enhancements
- Develop a **dashboard** for real-time HR analytics.  
- Implement **machine learning models** for salary prediction.  
- Perform **clustering** to segment employees by salary groups.

---

## 🧠 How to Run
```bash
# Clone the repository
git clone https://github.com/your-username/salary-data-analysis.git

# Navigate to project directory
cd salary-data-analysis

# Install required packages
pip install pyspark pandas matplotlib seaborn

# Run the notebook
jupyter notebook Salary_Analysis.ipynb
