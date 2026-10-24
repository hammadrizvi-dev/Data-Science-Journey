<div align="center">

  <h1>📊 Data Science Journey</h1>
  <p><strong>A structured, code-first repository documenting my transition from foundational data analysis to production-ready Machine Learning models.</strong></p>

  <p>
    <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" /></a>
    <a href="https://pandas.pydata.org/"><img src="https://img.shields.io/badge/Pandas-Data_Wrangling-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" /></a>
    <a href="https://numpy.org/"><img src="https://img.shields.io/badge/NumPy-Scientific_Computing-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" /></a>
    <a href="https://jupyter.org/"><img src="https://img.shields.io/badge/Jupyter-Interactive_Labs-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" /></a>
  </p>

  <p>
    <a href="#-repository-structure">Repository Structure</a> •
    <a href="#-featured-projects">Featured Projects</a> •
    <a href="#-curriculum--progress-tracker">Progress Tracker</a> •
    <a href="#-how-to-reproduce-locally">Run Locally</a>
  </p>

</div>

---

## 📂 Repository Structure

```text
Data-Science-Journey/
│
├── 📁 DS_Core_Sprints/       # Core concepts, daily exercises, and notes
│   ├── NumPy & Vectorization
│   ├── Pandas Data Wrangling
│   └── Data Visualization (Seaborn / Matplotlib)
│
├── 📁 Projects/              # End-to-end data analysis projects
│   └── 📁 01_Student_Performance_Analysis/
│
├── .gitignore                # System and cache ignores
├── requirements.txt          # Project dependencies
└── README.md                 # Primary documentation
```

---

## 🚀 Featured Projects

### 📌 01. Student Performance Analysis
> **Focus:** Data Inspection, Missing Value Handling & Behavioral Grouping

* **Objective:** Clean and analyze demographic and academic student data to identify performance drivers and score anomalies.
* **Key Operations:**
  * Handled missing attributes and deduplicated observations.
  * Utilized indexers (`.loc`, `.iloc`) and boolean masking for granular record slicing.
  * Executed multi-level `.groupby()` aggregations to compute composite subject averages.
* **Tech Used:** `Python`, `Pandas`, `NumPy`, `Jupyter Notebook`
* 🔗 **[Explore Project Folder & Notebook ➔](./Projects/)**

---

## 📈 Curriculum & Progress Tracker

| Milestone | Topic Domain | Key Concepts | Status |
| :---: | :--- | :--- | :---: |
| **01** | **Python & Core Foundations** | Data types, OOPs, Functions, File I/O | ✅ Completed |
| **02** | **NumPy & Pandas Wrangling** | Array indexing, DataFrames, Series, Aggregations | ✅ Completed |
| **03** | **Exploratory Data Analysis** | Outlier detection, Distribution profiling, Correlation | 🔄 In Progress |
| **04** | **Applied Business Statistics** | Probability, Central Tendency, Distributions, Hypothesis | ⏳ Upcoming |
| **05** | **Advanced SQL Querying** | JOINS, Subqueries, CTEs, Window Functions | ⏳ Upcoming |
| **06** | **Core Machine Learning** | Scikit-Learn, Regression, Classification, Model Evaluation | ⏳ Upcoming |

---

## ⚙️ How to Reproduce Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/hammadrizvi-dev/Data-Science-Journey.git
   cd Data-Science-Journey
   ```

2. **Set up a Virtual Environment (Recommended):**
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On Mac/Linux:
   source venv/bin/activate
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch JupyterLab:**
   ```bash
   jupyter lab
   ```

---

<div align="center">
  <sub>Maintained with 💻 by <a href="https://github.com/hammadrizvi-dev">Hammad Rizvi</a> • Connect on <a href="https://www.linkedin.com/in/hammadrizvi-dev">LinkedIn</a></sub>
</div>
