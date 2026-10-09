# 📊 Expectation Decider – Student Performance Probability Analysis

### Turning Student Data into Meaningful Probability Insights

## 📌 About the Project

**Expectation Decider** is a Python-based data analysis project that uses probability and statistical techniques to understand student performance in a competitive mathematics examination.

The project analyzes study hours, attendance, group discussion participation, and previous test scores to explore patterns associated with passing or failing the final examination.

## 🎯 Project Objectives

* Understand basic probability concepts and terminology.
* Calculate empirical and theoretical probability.
* Construct probability distributions and calculate mean and variance.
* Visualize the relationship between study hours and attendance.
* Analyze group discussion participation and examination results.
* Calculate joint, marginal, and conditional probabilities.
* Apply Bayes' theorem to estimate the probability of passing given high attendance.
* Present findings using tables and data visualizations.

## 📂 Dataset Information

The dataset contains **500 student records** with the following attributes:

| Column                | Description                                 |
| --------------------- | ------------------------------------------- |
| `study_hours`         | Hours studied per week                      |
| `attendance`          | Lecture attendance percentage               |
| `group_discussion`    | Participation in group discussions (Yes/No) |
| `previous_test_score` | Previous test score out of 100              |
| `final_exam_pass`     | Final examination result (Pass/Fail)        |

## 🛠️ Tools and Technologies

* **Python** – Statistical calculations and analysis
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical calculations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Anaconda & Jupyter Notebook** – Development environment

## 🔍 Project Analysis

### 1. Probability Fundamentals

* Definition of probability and key terminology
* Real-world probability examples from student data

### 2. Empirical vs. Theoretical Probability

* Calculate probabilities using observed student results
* Compare observed results with a theoretical model

### 3. Random Variables and Probability Distribution

* Define the random variable \(X\), representing the number of students passing among three selected students
* Construct a probability distribution table
* Calculate the expected value and variance

### 4. Venn Diagram Analysis

Visualize the overlap between:

* Students studying more than 10 hours per week
* Students with attendance above 80%

### 5. Contingency Table Analysis

Examine the relationship between group discussion participation and final examination results.

### 6. Probability Calculations

* Joint probability
* Marginal probability
* Conditional probability
* Independence and dependence of events

### 7. Bayes' Theorem

Estimate the probability of passing the examination given high attendance, using the hypothetical probabilities supplied in the assignment.

### 8. Data Visualization

* Study hours and attendance Venn diagram
* Group discussion versus examination result chart
* Average performance comparison chart

## 📈 Key Findings

Based on the dataset:

* **Total students:** 500
* **Students passed:** 309
* **Students failed:** 191
* **Observed pass probability:** 61.8%
* **Students studying more than 10 hours per week:** 327
* **Students satisfying both study-hours and attendance conditions:** 110
* **Pass rate among group discussion participants:** Approximately 65.42%

Using the hypothetical values provided in the assignment, Bayes' theorem gives a **77.78% probability of passing given high attendance**.

These findings describe observed patterns and stated assumptions; they do not prove that any single factor causes examination success.

## 💡 What Makes This Project Valuable?

This project connects mathematical probability with a practical educational scenario. It demonstrates how student data can be transformed into statistical evidence, visual insights, and meaningful conclusions.

The analysis provides a foundation for future development of a student performance prediction model using machine learning.

## 📁 Project Structure

```text
Expectation-Decider/
│
├── Expectation Decider.ipynb
├── student_performance_500.csv
└── README.md
```

## 🎓 Learning Outcomes

Through this project, I explored:

* Data analysis using Python and Pandas
* Statistical probability calculations
* Random variables and probability distributions
* Conditional probability and Bayes' theorem
* Contingency tables and event relationships
* Data visualization and interpretation

## 🔮 Future Scope

* Develop a machine learning model to predict student examination outcomes.
* Identify students who may benefit from additional academic support.
* Explore relationships between study habits and performance.
* Build an interactive dashboard for educational data analysis.

## 🏁 Conclusion

Expectation Decider demonstrates how probability and statistical analysis can help us understand patterns in student performance. By combining mathematical calculations, tables, and visualizations, the project provides a foundation for evidence-based educational insights and future predictive analytics.

---

**Project:** Expectation Decider
**Domain:** Data Analytics and Probability
**Language:** Python
**Environment:** Anaconda / Jupyter Notebook
