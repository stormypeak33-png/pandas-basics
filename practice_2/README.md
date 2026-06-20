# 🐼 Pandas Deep Dive — Beginner to Intermediate

A hands-on pandas learning journey covering core data manipulation skills in Python, built from scratch through guided practice.

## 📚 What I Learned

| Section ||        Topic       |
|---------||--------------------|
| 1 | Series & DataFrames       |
| 2 | Reading & Inspecting Data |
| 3 | Selecting & Filtering     |
| 4 | Data Cleaning             |
| 5 | Aggregation & GroupBy     |
| 6 | Merging & Reshaping       |

| 🚀 | Mini Project — Student Performance Analysis |

## 🚀 Mini Project — Student Performance Analysis

Analysed a dataset of 12 students across subjects (Math, Science, English) and cities.

**Tasks completed:**
- Loaded and inspected CSV data using `pd.read_csv()` and `StringIO`
- Found and filled null values with column means
- Created new columns: `Total` and `Average`
- Identified top 3 students by average score
- Grouped average scores by city
- Flagged at-risk students (Average < 65 or Attendance < 70)

## 🛠️ Skills Used

- `pd.read_csv()`, `StringIO`
- `head()`, `tail()`, `info()`, `describe()`, `shape`
- `loc`, `iloc`, boolean filtering, `isin()`
- `fillna()`, `dropna()`, `drop_duplicates()`, `rename()`, `astype()`
- `groupby()`, `agg()`, `sum()`, `mean()`, `max()`
- `merge()`, `concat()`, `pivot_table()`

## 🧰 Tools & Libraries

- Python 3
- Pandas
- NumPy
- Google Colab
