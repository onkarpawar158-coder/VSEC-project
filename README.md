# 📊 Student Performance Analysis Using Python

A data analysis and visualization project that explores student performance in Mathematics, Reading, and Writing using Python.

## 📌 About the Project

Student Performance Analysis is a Python-based project developed for the **Scientific Computing with Python (VSEC)** subject. It analyzes students' examination scores to identify performance patterns, understand relationships between subjects, and compare results based on test preparation course completion.

The project uses **Pandas, NumPy, Matplotlib, and Seaborn** to process the dataset, perform statistical analysis, and create meaningful visualizations.

## 🎯 Objectives

- Load and analyze student examination data.
- Inspect data quality and check for missing or duplicate records.
- Calculate average scores and descriptive statistics.
- Analyze correlations between Mathematics, Reading, and Writing scores.
- Compare the performance of students who completed test preparation courses with those who did not.
- Present the results using graphs and charts.

## 🛠️ Technologies Used

| Technology       | Purpose                              |
| ---------------- | ------------------------------------ |
| Python           | Programming and analysis             |
| Jupyter Notebook | Interactive development environment  |
| Pandas           | Data loading, cleaning, and grouping |
| NumPy            | Numerical calculations               |
| Matplotlib       | Creating charts and plots            |
| Seaborn          | Statistical data visualization       |

## 📂 Project Structure

```text
Student-Performance-Analysis/
│
├── student_performance.ipynb
├── StudentsPerformance.csv
├── README.md
└── .gitignore
```

*Note: The filenames above should match the actual files in the repository.*

## 📁 Dataset Description

The project uses the **Students Performance in Exams** dataset, which contains 1,000 student records and 8 columns.

| Column                      | Description                        |
| --------------------------- | ---------------------------------- |
| gender                      | Student gender                     |
| race/ethnicity              | Student group category             |
| parental level of education | Parent's education level           |
| lunch                       | Type of lunch program              |
| test preparation course     | Test preparation completion status |
| math score                  | Mathematics examination score      |
| reading score               | Reading examination score          |
| writing score               | Writing examination score          |

## ⚙️ Methodology

1. **Data Loading:** Import the CSV dataset using Pandas.
2. **Data Inspection:** Examine the dataset's dimensions, columns, and data types.
3. **Data Quality Check:** Check for missing values and duplicate records.
4. **Statistical Analysis:** Calculate average scores and other descriptive statistics.
5. **Correlation Analysis:** Examine relationships between the three subject scores.
6. **Group Comparison:** Compare average subject scores according to test preparation course completion.
7. **Visualization:** Generate charts and plots to communicate the results.

## 📈 Key Findings

- Average Mathematics score: **66.09**
- Average Reading score: **69.17**
- Average Writing score: **68.05**
- Reading and Writing scores have a strong positive correlation of approximately **0.955**.
- Students who completed the test preparation course had higher average scores in all three subjects in this dataset.

These findings describe patterns in the dataset and do not establish that test preparation alone caused the differences in scores.

## 📊 Visualizations

The notebook includes visualizations such as:

- Average score comparison across subjects.
- Distribution of Mathematics scores.
- Correlation heatmap of subject scores.
- Average subject scores grouped by test preparation course completion.

## 🚀 Installation and Usage

### Prerequisites

- Python 3.x
- Jupyter Notebook

### 1. Clone the repository

```bash
git clone https://github.com/onkarpawar158-coder/VSEC-project.git
```

Replace `YOUR-USERNAME` and `YOUR-REPOSITORY` with your actual GitHub details.

### 2. Open the project directory

```bash
cd YOUR-REPOSITORY
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Run the analysis

Open `student_performance.ipynb` and run the notebook cells from top to bottom. Keep `StudentsPerformance.csv` in the same directory as the notebook so the dataset can be loaded correctly.

## 🎓 Academic Information

- **Project Title:** Student Performance Analysis Using Python
- **Subject:** Scientific Computing with Python (VSEC)
- **Class:** Second Year B.Tech
- **Academic Year:** 2026–2027
- **Team Members:**
  - Onkar Pawar
  - Pratik Shendage

## 🔮 Future Scope

- Analyze additional factors related to student performance.
- Develop interactive dashboards for exploring results.
- Explore machine learning methods for score prediction.
- Extend the analysis with additional educational datasets.

## 📚 Dataset Reference

Kaggle — *Students Performance in Exams*
[https://www.kaggle.com/datasets/spscientist/students-performance-in-exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

## 📄 License

This project was developed for educational and academic purposes.

---

**Developed as part of the Scientific Computing with Python (VSEC) course project.**
