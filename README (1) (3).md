# Sales Data Analyzer

A Python-based interactive console application for loading, exploring,
cleaning, and visualizing sales datasets. This tool allows users to
analyze CSV data easily using Pandas and Matplotlib.

## 📌 Features

### **1. Load Dataset**

-   Load any CSV file into the program using `pandas.read_csv()`.
-   Automatically handles file loading errors.

### **2. Explore Data**

-   View first 5 rows\
-   View last 5 rows\
-   Show column names\
-   Show data types\
-   Display dataset info

### **3. Handle Missing Data**

-   Show rows with missing values\
-   Fill missing values with mean\
-   Drop rows with missing values\
-   Replace missing values with a custom value

### **4. Descriptive Statistics**

Displays summary statistics using:

    DataFrame.describe()

### **5. Data Visualization**

Supports: - Bar Plot\
- Line Plot\
- Scatter Plot\
- Pie Chart\
- Histogram\
- Stack Plot

### **6. Save Visualization**

Save generated plots to image files.

## 🛠️ Requirements

    pip install pandas matplotlib seaborn

## ▶️ How to Run

    python sales_analyzer.py

## 📂 Folder Structure

    /your-folder
    │-- sales_analyzer.py
    │-- dataset.csv

## 💡 Future Enhancements

-   Correlation heatmap\
-   Export cleaned dataset\
-   Outlier detection\
-   ML-based predictions

## 👨‍💻 Author

This program was created to simplify CSV data analysis using Python.

## 📝 License

Free to use and modify.
