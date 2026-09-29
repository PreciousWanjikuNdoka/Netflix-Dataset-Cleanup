<<<<<<< HEAD
# Netflix Data Cleaning & Analysis Project

An end-to-end Python data cleaning project that processes, cleans, and exports the raw Netflix movies and TV shows dataset for downstream analysis.

---

## 🔗 Project References & Links

* **Project Specification:** [roadmap.sh Netflix Cleaning Project](https://roadmap.sh/projects/cleaning-netflix-dataset)
* **GitHub Repository:** [View Project Repository](https://github.com/PreciousWanjikuNdoka/Netflix-Dataset-Cleanup.git)

---

## 🧹 Data Cleaning Methodology & Steps Taken

The data cleaning pipeline in `Netflix_cleanup code.ipynb` follows a 5-step methodology:

1. **DataFrame Inspection:**
   * Used `.info()`, `.describe()`, and `.head()` to inspect dataset dimensions, column data types, and initial summary statistics.

2. **Missing Value Handling:**
   * Identified null and missing entries across all columns on a column-by-column basis and applied appropriate imputation or removal strategies.

3. **Mixed-Type Column Resolution:**
   * Handled mixed formats like the `duration` column (containing values such as `"90 min"`, `"2 Seasons"`, etc.) by using regular expression extraction (`str.extract`) to split data into quantitative numerical values (`duration_num`) and text units (`duration_unit`).

4. **Date Parsing:**
   * Converted raw date string attributes into standard `datetime64` objects for accurate chronological filtering and time-series analysis.

5. **Dataset Export:**
   * Exported the fully cleaned and structured DataFrame to a new file named `Netflix_cleaned.csv` using `.to_csv(..., index=False)`.

---

## 🚀 How to Run This Project on Your Machine

Follow these step-by-step instructions to set up and run the project locally on your machine.

### Prerequisites
Ensure you have the following installed on your system:
* **Git**: [Download Git](https://git-scm.com/downloads)
* **Python (v3.8 or higher)**: [Download Python](https://www.python.org/downloads/)
* **VS Code**: [Download Visual Studio Code](https://code.visualstudio.com/) with the **Python** and **Jupyter** extensions installed.

---

### Step 1: Clone the Repository
Open your terminal (macOS/Linux) or Command Prompt / PowerShell (Windows), navigate to your desired directory, and clone the repository:

```bash
git clone [https://github.com/PreciousWanjikuNdoka/Netflix-Dataset-Cleanup.git](https://github.com/PreciousWanjikuNdoka/Netflix-Dataset-Cleanup.git)


## 📊 Transformation Overview (Before vs. After)

### Raw Dataset (Before Cleaning)
![Raw Netflix Data Sample](./Before_cleaning.png)

### Processed Dataset (After Cleaning)
![Cleaned Netflix Data Sample](./After_cleaning.png)
=======
# Netflix-Dataset-Cleanup
>>>>>>> main
