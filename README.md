# 🔭 Kepler Exoplanet Analysis

Exploratory Data Analysis (EDA) of NASA's Kepler Exoplanet Dataset using Python.

## 📖 Project Overview

This project explores exoplanet candidates discovered by NASA's Kepler Space Telescope. The goal is to understand the characteristics of detected planets and identify potential Earth-like candidates through data analysis and visualization.

The analysis focuses on:

- Planet radius distribution
- Planet classification by size
- Equilibrium temperature distribution
- Relationship between planet radius and temperature
- Identification of Earth-like planet candidates

---

## 📊 Dataset

The dataset contains information about exoplanet candidates observed by the Kepler mission, including:

- Planet Radius (`koi_prad`)
- Equilibrium Temperature (`koi_teq`)
- Planet Status (`koi_disposition`)
- Stellar Properties
- Orbital Characteristics

Dataset size:

- 9,564 planet candidates
- Multiple planetary and stellar attributes

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Analysis Performed

### 1. Planet Status Analysis

Examined the distribution of confirmed, candidate, and false-positive planets.

### 2. Planet Radius Distribution

Analyzed how planet sizes vary across the dataset and investigated outliers.

### 3. Planet Classification

Classified planets into four categories:

- Earth-like
- Super Earth
- Neptune-like
- Gas Giant

### 4. Temperature Analysis

Explored the distribution of planetary equilibrium temperatures.

### 5. Earth-like Candidate Search

Applied simple filtering criteria to identify potentially Earth-like planets:

- Confirmed planets only
- Radius < 1.5 Earth radii
- Equilibrium temperature between 230 K and 320 K

---

## 📈 Key Findings

- The dataset contains 9,564 exoplanet candidates.
- Gas Giants are the most common planet category.
- Planet radius distribution is strongly right-skewed.
- Planet temperatures span a very wide range.
- Only a limited number of confirmed planets satisfy the Earth-like criteria used in this analysis.

---

## 🚀 Future Improvements

Possible extensions of this project include:

- Machine Learning classification models
- Habitability prediction
- Advanced statistical analysis
- Interactive dashboards using Power BI or Tableau

---

## 👨‍💻 Author

**Ilgın Ertekin**

Astronomy & Space Sciences Graduate  
Aspiring Data Analyst

GitHub: https://github.com/Ilgin08
