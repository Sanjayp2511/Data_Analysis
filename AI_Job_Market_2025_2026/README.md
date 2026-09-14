# AI Job Market 2025–2026

## Analyzing Salaries, Demand, Skills & Career Trends

### 📌 Project Overview

This project analyzes the AI job market from 2025–2026 to understand how factors such as experience, education, job specialization, location, skills, and LLM adoption are associated with salary and job demand.

The analysis focuses on identifying patterns that can help aspiring AI professionals understand which roles and skills are valuable in the current AI job market.

---

## 🎯 Objectives

- Analyze salary distributions across AI roles.
- Examine the relationship between experience and salary.
- Compare salaries across job categories and job titles.
- Analyze salary differences across countries.
- Examine education and salary patterns.
- Identify high-demand AI roles.
- Analyze year-over-year demand growth.
- Identify the most frequently required skills.
- Identify skills associated with higher-paying roles.
- Compare LLM and non-LLM roles.
- Analyze correlations between important numerical variables.

---

## 📊 Dataset

The dataset contains **1,500 AI job postings** and **25 features**, including:

- Job title
- Job category
- Experience level
- Years of experience
- Education required
- Annual salary
- Salary range
- Country and city
- Remote work status
- Company size
- Industry
- Required skills
- AI salary premium
- Demand score
- Demand growth
- LLM role indicator

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Analysis Performed

### Salary Analysis

- Salary distribution
- Experience level vs salary
- Years of experience vs salary
- Job category vs salary
- Job category × experience
- Education vs salary
- Job title vs salary
- Job title × experience
- Country vs salary
- Country × experience
- Remote work vs salary

### Demand Analysis

- Demand by job category
- Demand by job title
- Year-over-year demand growth

### Skills Analysis

- Most frequently required skills
- Skills associated with higher salaries

### LLM Analysis

Comparison of LLM and non-LLM roles based on:

- Salary
- Demand
- Demand growth

### Correlation Analysis

Examined relationships between salary, experience, demand, demand growth, salary ranges, and AI salary premium.

---

## 📈 Key Findings

- Salary increases substantially across broad experience levels, from Entry-level to Lead roles.
- Exact years of experience have only a weak linear relationship with annual salary in this dataset.
- Architecture and AI Engineering are among the higher-paying job categories.
- AI Solutions Architect, Senior ML Engineer, and LLM Engineer are among the higher-paying roles.
- The USA has the highest average salary among the specific countries represented in the dataset.
- ML Operations and AI Engineering show particularly strong demand.
- LLM-focused roles have higher average salary, demand, and demand growth than non-LLM roles.
- Python is the most frequently required skill, followed by SQL and Cloud.
- System Design, RAG, Fine-tuning, and MLOps are associated with higher-paying job postings.
- Demand score and demand growth show a moderate positive relationship.

---

## 💼 Career Insights

The analysis suggests that aspiring AI professionals can benefit from developing a combination of strong technical fundamentals and specialized AI skills.

Recommended areas include:

- Python
- SQL
- Statistics
- Machine Learning
- Cloud technologies
- LLMs
- RAG
- Fine-tuning
- MLOps
- Communication
- Problem solving

Building a combination of foundational and modern AI skills can provide broader career opportunities than focusing on a single technology or job title.

---

## ⚠️ Limitations

- The dataset contains 1,500 job postings and may not represent the entire global AI job market.
- Some categories and skills have relatively small sample sizes.
- `demand_score` is an index and does not represent the actual number of job openings.
- Relationships identified in the analysis represent associations and should not be interpreted as causal relationships.
- Salary differences may also be influenced by factors not included in the dataset.

---

## 📁 Project Structure

```text
AI_Job_Market_2025_2026/
│
├── AI_Job_Market_2025_2026.ipynb
├── ai_jobs_market_2025_2026.csv
└── README.md
