# Data Preview
### Dataset

1. Student Apptitude :
   - 3 columns
   - 150 rows
   - no null & duplicate data

2. Student Performance :
   - 3 columns
   - 150 rows
   - no null & duplicate data

### Data Quality

1. Student Apptitude :
- no missing
- no duplicated student_id

2. Student Performance :
- no missing
- no duplicated student_id


## Descriptive Statistics

The table below presents a summary of the dataset generated using the `describe()` function from the pandas library.  
It provides an overview of the distribution, central tendency, and variability for each numerical feature.

| Statistic | student_id | aptitude_score | performance_score |
|----------|------------|----------------|-------------------|
| count    | 150        | 150            | 150               |
| mean     | 75.50      | 44.24          | 2.54              |
| std      | 43.45      | 24.23          | 0.65              |
| min      | 1          | 9              | 1.55              |
| 25%      | 38.25      | 22             | 1.95              |
| 50%      | 75.50      | 38             | 2.48              |
| 75%      | 112.75     | 65             | 3.04              |
| max      | 150        | 97             | 3.80              |

**Column Description:**
- **student_id**: Unique identifier for each student.
- **aptitude_score**: Score representing students’ aptitude levels.
- **performance_score**: Final performance score achieved by students.


