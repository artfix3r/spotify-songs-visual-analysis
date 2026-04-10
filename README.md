# 🎵 Spotify Songs – Exploratory Data Analysis

A Python-based exploratory data analysis (EDA) project that visualizes and interprets 
musical attributes of 100 popular Spotify songs using **Pandas**, **Seaborn**, and **Matplotlib**.

---

## 📌 Overview

This project analyzes a labeled dataset of 100 Spotify songs and answers key questions about:
- **Distributions** of musical attributes (energy, valence, tempo, key, mode, duration)
- **Correlations** between attributes (e.g., energy vs. valence)
- **Outliers** in song duration and tempo patterns

---

## 📂 Dataset

File: `spotifysongs.csv`

| Column        | Description                              |
|---------------|------------------------------------------|
| `name`        | Song title                               |
| `artists`     | Artist name(s)                           |
| `energy`      | Intensity and activity level (0–1)       |
| `key`         | Musical key (0–11)                       |
| `mode`        | Major (1) or Minor (0)                   |
| `valence`     | Musical positivity/happiness (0–1)       |
| `tempo`       | Beats per minute (BPM)                   |
| `duration_ms` | Song duration in milliseconds            |

---

## 📊 Analysis Highlights

- **Normal distribution**: `valence`
- **Skewed distribution**: `energy`
- **Discrete fields**: `key`, `mode`
- **Outlier detected**: `duration_ms` (songs > 300,000 ms)
- **Popular tempo range**: 90–100 BPM
- **Positive correlation**: `energy` ↑ → `valence` ↑
- **Negative correlation**: `mode` ↑ → `valence` ↓
- **Uncorrelated**: `key` vs `valence`, `tempo` vs `duration_ms`

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/spotify-music-eda.git
cd spotify-music-eda
```

### 2. Install dependencies
```bash
pip install pandas seaborn matplotlib jupyter
```

### 3. Run the notebook
```bash
jupyter notebook section06_visualizing_data_solutions.ipynb
```

---

## 📁 Project Structure
