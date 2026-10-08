# VEDA AI & ML Internship – Day 19

## Filter Dataset Records Using Pandas

### 📌 Objective

The objective of this task is to learn how to filter dataset records using Pandas based on single and multiple conditions.

### 🛠️ Tools & Technologies

- Python
- Pandas
- Jupyter Notebook
- Titanic Dataset

### 📊 Dataset

The **Titanic dataset** is used for this task. It contains passenger information such as:

- Passenger Class
- Gender
- Age
- Fare
- Survival Status

### 🔍 Filtering Techniques

The following Pandas filtering techniques were implemented:

1. **Filter by Age**
   - Selected passengers whose age is greater than 30.

2. **Filter by Gender**
   - Selected only female passengers.

3. **Multiple Conditions using AND**
   - Selected female passengers older than 30.

4. **Multiple Conditions using AND**
   - Selected first-class passengers who paid a fare greater than 50.

5. **Multiple Conditions using OR**
   - Selected passengers from either first or second class.

6. **Count Filtered Records**
   - Used `len()` to determine the number of records matching each condition.

### 💻 Example

```python
female_above_30 = df[
    (df["Sex"] == "female") & (df["Age"] > 30)
]

female_above_30.head()
````

### 📚 Key Concepts Learned

* Boolean indexing in Pandas
* Filtering DataFrame rows
* Equality conditions using `==`
* Comparison operators such as `>`
* AND operator `&`
* OR operator `|`
* Using parentheses with multiple conditions
* Counting filtered records

### 🎯 Interview Questions

1. How do you filter rows in Pandas?
2. How do you combine multiple conditions in Pandas?
3. What is the use of `&` and `|` operators in Pandas filtering?
4. Why are parentheses important when using multiple conditions?
5. How can you check the number of records after filtering a DataFrame?

### 📁 Project Structure

```text
VEDA-Task-19-Filter-Dataset-Records/
│
├── Day-19-Filter-Dataset-Records.ipynb
└── README.md
```

### ✅ Conclusion

This task provided practical experience in filtering DataFrame records using Pandas. Different filtering conditions, logical operators, and record-counting techniques were applied to the Titanic dataset.

```
```
