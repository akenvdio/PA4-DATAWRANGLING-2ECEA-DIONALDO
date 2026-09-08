# PA4 | ECE2112 | EXPERIMENT 4 | DIONALDO, PVA
---
### **DATA WRANGLING AND DATA VISUALIZATION**
#### Submitted by Pierre Van Aken A. Dionaldo | 2ECE-A | 09.09.2026

This repository showcases the objective and detailed discussion of the experiment from the Programming Assignment 4 last September 8, 2026 where the class discussed Module 4 - **Data Wrangling and Data Visualization**

---
### **Objectives**
---
At the end of this laboratory activity, the student should be able to:

1. filter tabular data using several categorical and numerical conditions;
2. construct focused DataFrames by selecting relevant features;
3. summarize the relationship between categorical features and a numerical variable; and
4. communicate a data comparison using clear and correctly labeled plots.

The students are also expected to use the same ECE Board Exam 2 dataset supplied for Experiment 4. Work in a Jupyter Notebook using Pandas and a Python plotting library used in class. Use the dataset’s existing column labels, including Name, Gender, Track, Hometown, Math, GEAS, Electronics, and Average.
- Derive all tables and plot values from the dataset. Do not manually type rows, category means, or plotted values.
- When applying more than one condition, make every condition explicit in the filtering expression.
- Keep the original DataFrame unchanged.
- Every graph must have a title, axis labels, readable category labels, and a consistent scale appropriate to the data.

---
### **Programming Problems**
---
#### **A. VISAYAS COMMUNICATION DATAFRAME**

Create a DataFrame named VisComm containing students whose Hometown is Visayas and whose Track is Communication. Retain only these columns, in the stated order:
`Name, Gender, Math, Electronics, Average`
Display the resulting DataFrame and its number of rows. Both filtering conditions must be applied to the source dataset before the columns are selected.

**CODE**
```

```

**OUTPUT**
```

```

The following functions and methods in this code are:
- `code`: 
- `code`:
- `code`:

---
#### **B. VISAYAS FEMALE DATAFRAME**

Create a second DataFrame named VisFemale containing students whose Hometown is Visayas and whose Gender is Female. Retain only:
`Name, Track, GEAS, Electronics, Average`
Display VisFemale. Then display only the rows of VisFemale whose Average is at least 60. Do not overwrite VisFemale when performing this second filter.

**CODE**
```

```

**OUTPUT**
```

```

The following functions and methods in this code are:
- `code`: 
- `code`:
- `code`:

---
#### **C. CATEGORY-AVERAGE VISUALIZATION**

Examine how the recorded Average differs across the three categorical features Track, Gender, and Hometown.

a. For each feature, compute the mean of Average for every category using Pandas.
b. Display the three summary tables.
c. Create one figure containing three bar charts: mean Average by Track, by Gender, and by Hometown.
d. Below the figure, write three concise statements identifying the category with the highest sample mean for each feature.

**Interpretation rule**: Describe the observed dataset only. A difference in group means does not, by itself, establish that a feature causes a higher board-exam score.

**CODE**
```

```

**OUTPUT**
```

```

The following functions and methods in this code are:
- `code`: 
- `code`:
- `code`:

---
### **END OF NOTEBOOK**
