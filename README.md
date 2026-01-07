# 📊 COVID-19 Data Analysis & Visualization

A Python-based data analysis project that explores **COVID-19 case growth, vaccination progress, and continent-level comparisons** using the *Our World in Data* dataset.  
The project emphasizes **clean preprocessing**, **clear visualizations**, and **reproducible analysis**.

---

## 📌 Project Overview

This project analyzes global COVID-19 data to:
- Track **case growth trends** for a selected country
- Compare **vaccination progress vs total cases**
- Analyze **continent-wise COVID-19 impact**
- Present insights through **clear and readable plots**

The dataset is sourced from **Our World in Data**, ensuring reliability and up-to-date reporting.

---

## ✨ Key Features

- 📥 Automatic dataset download
- 🧹 Data cleaning & preprocessing
- 📈 Time-series visualization of cases
- 💉 Vaccination vs cases comparison
- 🌍 Continent-level statistical analysis
- 🧩 Modular and maintainable code structure

---

## 🗂️ Project Structure

covid-data-analysis/
│
├── data/
│   └── compact.csv
│
├── scripts/
│   ├── downloader.py
│   ├── data_cleaning.py
│   ├── analysis.py
│   └── utils.py
│
├── main.py
├── requirements.txt
└── README.md

---

## 🛠️ Technologies Used

- Python 3
- Pandas – data manipulation
- Matplotlib – data visualization
- Requests – HTTP data download

---

## 📊 Visualizations Included

- COVID-19 Case Growth Over Time (Country-wise)
- Vaccination Progress vs Total Cases
- Continent-wise Comparison of Cases & Vaccinations

All plots include:
- Proper axis scaling
- Readable number formatting (in millions)
- Legends and gridlines for clarity

---

## 🚀 Getting Started

Clone the repository:
git clone https://github.com/your-username/covid-data-analysis.git
cd covid-data-analysis

Install dependencies:
pip install -r requirements.txt

Run the project:
python main.py

The script loads the dataset, preprocesses it, and generates all visualizations automatically.

---

## 🧪 Example Usage

plot_case_growth(data, "India")
plot_vaccination_vs_cases(data, "India")
compare_continent_stats(data)

You can replace "India" with any other country available in the dataset.

---

## 📁 Dataset Information

Source: Our World in Data  
Dataset URL: https://catalog.ourworldindata.org/garden/covid/latest/compact/compact.csv  

The dataset includes:
- Confirmed cases
- Death statistics
- Vaccination data
- Government stringency index
- Population and continent information

---

## 👤 Author

Mohit Wadhwani  
Computer Science Student | Data Analysis & Visualization  
India

---

## 📜 License

This project is intended for educational and academic use.  
All data credit belongs to Our World in Data.
