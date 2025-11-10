# 💼 Maximizing Developer Market Value in the U.S.A  
### *A Data-Driven Analysis Using the Stack Overflow Developer Survey*

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-lightgrey?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-yellow?logo=plotly)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Graphics-9cf?logo=seaborn)

---

## 🧠 Executive Summary
This project explores a key question for aspiring software developers:  
> **“What should developers focus on to maximize their market value in the U.S.?”**  

Leveraging data from a global developer survey, this analysis identifies which **skills, education levels, technologies, and work arrangements** have the strongest relationship with **compensation** in the United States.  

Key findings reveal that while **education and experience** play an important role, the **ability to work remotely**, **proficiency in modern technologies**, and **adaptability** are the most powerful drivers of long-term earning potential.

---

## 🎯 Introduction

**Objective:**
This analysis combines exploratory data analysis, visualization, and storytelling to uncover actionable insights into developer compensation trends in the U.S.

**Key Question:**  
*What should aspiring developers focus on in order to maximize their market value in the USA?*

---

## 🔍 Workflow
1. **Data Preparation**
   - Removed duplicates and cleaned inconsistent entries  
   - Created new columns: `Region`, `EmploymentCategory`, `Student`  
   - Standardized education and work experience variables  

2. **Exploratory Analysis**
   - Investigated global and regional distributions of compensation, tools, and technologies  
   - Focused on U.S. respondents for detailed compensation insights  

3. **Statistical & Visual Analysis for U.S.A Full-Time Employed Developers**
   - Explored correlations between:
     - Education level and compensation  
     - Remote work and compensation  
     - Experience and compensation  
     - Programming languages, databases, and collaboration tools  
   - Created visualizations: histograms, boxplots, heatmaps, and pie charts  

---

## 📊 Results

### 🌍 **Global Highlights**
- Most respondents are from **Europe** and **North America**.
  
The comparison between languages developers use today and those they want to learn next reveals clear market trends:
- Java and C remain critical for legacy systems but show signs of decline in future interest, while Go and Rust stand out as emerging, high-value skills that could define the next wave of developer demand.  
  
### 🇺🇸 **U.S.-Specific Insights**

<p align="center">
  <img src="https://github.com/edgalbinski/Compensation-Analysis-For-American-Developers/blob/main/Images/compensation_by_experience.png?raw=true" width="45%">
  <img src="https://github.com/edgalbinski/Compensation-Analysis-For-American-Developers/blob/main/Images/compensation_by_remotework.png?raw=true" width="45%">
  <br>
  <em>Figure 1: Average Yearly Compensation by Years of Experience (left) and by Remote Work Status (right) for Full-Time Employed Developers in the U.S.A</em>
</p>

<p align="center">
  <img src="https://github.com/edgalbinski/Compensation-Analysis-For-American-Developers/blob/main/Images/compensation_by_lang%26dbs.png?raw=true" width="65%">
  <br>
  <em>Figure 2: Average Yearly Compensation by Programming Languages and Databases for Full-Time Employed Developers in the U.S.A</em>
</p>


- **Education:** Master’s degree holders earn the **highest average salary (~$143K)**. But that is **only $10k more per year** in average than developers with a Bachelor's or Professional Degree.   
- **Remote Work:** Remote professionals earn **≈ $30K more** per year than in-person workers.  
- **Experience:** Salaries rise steeply during the **first 10 years**, then stabilize around **$150K**. Work experience has very strong correlation to compensation for the first 10 years of a developer's career.  
- **Technologies:** Developers using Bash/Shell and Redis report above-average pay. In contrast, whether a developer uses Python, JavaScript, SQL, or HTML does not appear to have a significant impact on compensation.   
- **Job Satisfaction:** Weak correlation with pay — satisfaction depends on more than money.  

---

## 💡 Recommendations

1. **🎓 Invest in Practical Education**  
   - Obtain at least a **Bachelor’s degree**; a Master’s adds value but experience and portfolio work seem to matter more.

2. **🌐 Embrace Remote Work Skills**  
   - Build communication, self-management, and digital collaboration skills. Remote-ready developers consistently earn more. The analysis suggests that among developers with at least a Bachelor's degree, working remotely makes a bigger difference in compensation than a Masters or a Professional Degree.   

3. **💻 Focus on High-Demand Technologies**  
   - Prioritize **Bash/Shell**, **Python**, **JavaScript**, **SQL**, **HTML** and **modern databases** like **Redis** and **PostgreSQL**.  
   - Stay alert to emerging languages (**Go**, **Rust**) to stay ahead of industry demand.
   - Get comfortable using **MacOS** for work and earn on average about **$20k more** per year **than Windows developers**

4. **🧭 Study Now and be Patient With Compensation**  
   - The first 10 years of a developer’s career are typically defined by a steep increase in compensation.
   - Continuous learning is essential to stay current with emerging tools and technologies, which become increasingly correlated with compensation as developers gain experience.
   - Developers who are still studying earn about half as much as those who have completed their studies.
   - For this reason, it’s recommended to prioritize education and skill development during the first decade in order to maximize compensation.
   - Since experience level is a limiting factor for compensation, and compensation growth tends to plateau after a decade, building a strong foundation of in-demand skills early is financially smart: It will have a lower opportunity cost as opposed to going back to school later on, and can position developers for higher earning potential once they reach 10+ years of experience.
   - Note that developers will always need to keep learning in order to remain relevant in this rapidly changing market. 

---

## Conclusion & Next Steps

This analysis shows that **remote adaptability, continuous learning (specially for the first 10 years), and technical versatility** are central to maximizing a developer’s market value in the U.S.  

While higher education remains beneficial, **career growth now depends more on adaptability** — the ability to learn quickly, communicate effectively, and integrate new technologies efficiently.

### 🔮 Next Steps
- Integrate **job market data** (LinkedIn/Indeed APIs) to validate compensation trends.  
- Use **predictive modeling** to estimate salary potential based on skill and experience combinations.  

---

## 👨‍💻 Author

**Eduardo Galbinski Rodrigues**  
📍 Data Analyst | Background in SMB Development & Financial Sales |

📧 [dudugr03@gmail.com](mailto:dudugr03@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/edgalbinski/)  
💻 [GitHub](https://github.com/edgalbinski)

---

> ⭐ *If you found this project insightful, consider starring the repository to support my work!*  
