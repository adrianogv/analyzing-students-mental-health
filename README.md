# SQL Project - Analyzing Student Mental Health Data

## Project Overview

This project explores and analyzes a dataset on students' mental health, focusing on understanding the impact of **length of stay** (`stay`) on the **average mental health diagnostic scores** of international students. The dataset includes key mental health metrics derived from three diagnostic tests: 

- **PHQ-9 Test** (`todep`) measuring depression severity.
- **SCS Test** (`tosc`) assessing self-compassion levels.
- **ASISS Test** (`toas`) evaluating social anxiety levels.

The goal is to derive insights that can inform mental health support strategies for international students based on their length of stay.

---

## Analysis Steps

1. **Data Preparation:**
   - Filter the dataset to include only international students.
   - Extract and aggregate data on `stay`, the key metric defining the length of stay.

2. **Output Table Specification:**
   - A final table with **nine rows and five columns**, where the columns are:
     - `stay`: Length of stay.
     - `count_int`: Number of international students for each length of stay.
     - `average_phq`: Average PHQ-9 score, rounded to two decimal places.
     - `average_scs`: Average SCS score, rounded to two decimal places.
     - `average_as`: Average ASISS score, rounded to two decimal places.

3. **Data Processing and Calculations:**
   - Compute the averages of `todep`, `tosc`, and `toas` for each `stay` value.
   - Count the number of international students (`count_int`) for each `stay`.
   - Alias columns appropriately for clarity.

4. **Sorting:**
   - Sort the final table by `stay` in descending order.

---

## Tools and Technologies Used

- **SQL**: Data aggregation and analysis.
- **Python**: Data processing and visualization using libraries like Pandas and Matplotlib (if applicable).
- **GitHub**: Version control and collaboration.

---

## How to Use This Repository

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/sql-student-mental-health.git
   ```
2. Run the SQL script in your preferred environment or integrate it with Python for enhanced analysis.

3. View the analysis results in the provided Jupyter Notebook or `.sql` file.

---

## Results and Insights

The analysis reveals trends in mental health scores based on the length of stay. These findings are intended to aid stakeholders in designing targeted mental health interventions for international students.

---

## Future Scope

- Extending the analysis to include other demographic factors (e.g., age, gender, field of study).
- Incorporating machine learning models to predict mental health outcomes based on length of stay and other variables.
