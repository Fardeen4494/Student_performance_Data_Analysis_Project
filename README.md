# Student Performance Data Analysis Using Python

**Internship Module:** Module 01 – Week 1 (Beginner)  
**Tools:** Python, NumPy, Pandas, Matplotlib, Google Colab

## Project overview
This beginner project analyzes a fictional student academic-performance dataset. It demonstrates how to load CSV data, inspect and clean missing values, calculate averages, assign grades, summarize results, and create visualizations.

## Files
- `Student_Performance_Data_Analysis.ipynb` — complete Google Colab/Jupyter notebook.
- `student_performance.csv` — fictional sample dataset (30 student records).
- `README.md` — project documentation.

## Dataset columns
`Student_ID`, `Name`, `Gender`, `Math`, `Science`, `English`, `Computer`, `Attendance`.

A few subject marks are intentionally missing so the notebook can demonstrate missing-value handling. The records are fictional and must not be treated as real student information.

## How to run in Google Colab
1. Download this repository or open the notebook in Colab.
2. Open `Student_Performance_Data_Analysis.ipynb`.
3. Run the import cell.
4. When prompted, upload `student_performance.csv`.
5. Choose **Runtime → Run all** (or run cells from top to bottom).
6. Review the tables, charts, and printed insights.
7. Optionally uncomment the download lines in the final export cell to save the cleaned CSV.

## Analysis performed
1. CSV loading and dataset exploration.
2. Missing-value inspection and median imputation for numeric columns.
3. Student average calculation.
4. Grade assignment using the following illustrative scale:
   - A: 90–100
   - B: 80–89.99
   - C: 70–79.99
   - D: 60–69.99
   - F: below 60
5. Class and subject-wise summaries.
6. Bar chart of subject averages.
7. Bar chart of grade distribution.
8. Histogram of student averages.
9. Scatter plot of attendance versus average marks.
10. Identification of students who may benefit from additional support.

## Requirements
Google Colab already includes the required libraries in most cases. For a local environment:

```bash
pip install numpy pandas matplotlib jupyter
```

## Important note
This is an educational demonstration using synthetic data. Grade thresholds and the support flag are illustrative and should be adapted to an institution's actual policies before real-world use.
