# 🎬 Movie Dataset Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a movie dataset using Python. The goal of this project is to analyze trends in movie genres, popularity, ratings, and release years using data analysis and visualization techniques.

The project demonstrates fundamental **data analysis skills** such as data cleaning, handling missing values, identifying duplicates, and extracting meaningful insights from the dataset.

This project is intended as a **beginner data analysis portfolio project** and showcases the use of common Python libraries used in data science.

---

## 📊 Dataset Information

The dataset contains information about thousands of movies and includes attributes such as:

* Release date
* Movie title
* Overview
* Popularity score
* Vote count
* Average vote rating
* Original language
* Genre
* Poster URL

Total dataset size:

* **Rows:** ~9,800+
* **Columns:** 9

---

## 🛠️ Tools and Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

These libraries were used for:

* Data manipulation
* Data cleaning
* Statistical analysis
* Data visualization

---

## 🔎 Project Workflow

### 1. Data Loading

The dataset was loaded using **Pandas**.

```python
import pandas as pd
df = pd.read_csv("mymoviedb.csv", lineterminator='\n')
```

---

### 2. Data Exploration

Initial exploration was performed to understand the dataset structure.

Key functions used:

* `df.head()`
* `df.info()`
* `df.describe()`
* `df.isnull().sum()`
* `df.duplicated().sum()`

These helped identify:

* missing values
* duplicate records
* column data types
* dataset structure

---

### 3. Data Cleaning

Data preprocessing steps included:

* Handling missing values
* Checking duplicate rows
* Converting release date column to datetime format

Example:

```python
df['Release_Date'] = pd.to_datetime(df['Release_Date'])
```

---

### 4. Exploratory Data Analysis (EDA)

The dataset was analyzed to answer several key questions about movies, popularity, and genres.

### Questions Explored

1. What is the most frequent movie genre in the dataset?

2. Which movie has the highest value in the **vote_average** column?

3. Which movie has the highest popularity and what is its genre?

4. Which movie has the lowest popularity and what is its genre?

5. Which year has the highest number of movie releases?

These questions helped uncover patterns and trends within the dataset.

---

## 📈 Data Visualization

Visualizations were created using **Matplotlib** and **Seaborn** to better understand trends in the data.

Examples of visualizations:

* Genre distribution
* Popularity comparisons
* Movie release trends by year

These visualizations help present insights in a more intuitive and understandable way.

---

## 💡 Key Skills Demonstrated

This project demonstrates the following **data analysis skills**:

* Data cleaning
* Data preprocessing
* Exploratory Data Analysis (EDA)
* Data visualization
* Working with real-world datasets
* Using Python for data analysis

---

## 🚀 Future Improvements

Possible improvements to this project include:

* Adding more advanced visualizations
* Performing correlation analysis
* Building a movie recommendation system
* Creating an interactive dashboard
* Performing machine learning analysis

---

## 📂 Project Structure

```
movie-data-analysis/
│
├── main.ipynb          # Jupyter Notebook containing analysis
├── mymoviedb.csv       # Dataset used in the project
└── README.md           # Project documentation
```

---

## 📚 Learning Outcome

This project helped strengthen my understanding of:

* Python for data analysis
* Data cleaning techniques
* Exploratory data analysis
* Visualization using Matplotlib and Seaborn
* Extracting insights from datasets

---

## 🔗 Author

**Nirmal**

Aspiring Data Analyst / Data Science Learner
Currently learning Python and its libraries, Data Analysis, and Machine Learning.
