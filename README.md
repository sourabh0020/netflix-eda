# 🎬 Netflix Content Analysis — EDA Project

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-EDA-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

An exploratory data analysis (EDA) of Netflix's movie and TV show catalogue using Python.

---

## 📌 Project Overview

This project analyzes the Netflix dataset to uncover patterns in content type, country distribution, ratings, genres, and release trends.

**Key Questions Answered:**
- How is content split between Movies and TV Shows?
- Which countries produce the most Netflix content?
- How has Netflix's content library grown year by year?
- What are the most common ratings and genres?
- Who are the most prolific directors on Netflix?

---

## 📁 Project Structure

```
netflix-eda/
│
├── data/
│   └── netflix1.csv              # Raw dataset (not tracked by Git)
│
├── notebooks/
│   └── Netflix_Content_Analysis.ipynb   # Main analysis notebook
│
├── plots/                        # Saved chart images
│   ├── movies_vs_shows.png
│   ├── top_countries.png
│   ├── content_per_year.png
│   ├── rating_distribution.png
│   ├── movie_duration.png
│   ├── top_directors.png
│   └── genre_heatmap.png
│
├── src/
│   └── analysis.py               # Standalone Python script version
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 📊 Analysis Highlights

| Analysis | Insight |
|---|---|
| Content Split | ~70% Movies, ~30% TV Shows |
| Top Country | United States dominates by far |
| Peak Year | 2019 had the most content added |
| Most Common Rating | TV-MA |
| Avg Movie Duration | ~99.6 minutes |

---

## 🖼️ Sample Visualizations

### Movies vs TV Shows
![Movies vs TV Shows](plots/movies_vs_shows.png)

### Top 10 Countries
![Top Countries](plots/top_countries.png)

### Genre Heatmap
![Genre Heatmap](plots/genre_heatmap.png)

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python 3.x | Core language |
| Pandas | Data loading, cleaning, analysis |
| NumPy | Numerical operations |
| Matplotlib | Charts and plots |
| Seaborn | Heatmap visualization |
| Jupyter Notebook | Interactive analysis |

---

## 🚀 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/sourabh0020/netflix-eda.git
cd netflix-eda
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Add the dataset**
- Place `netflix1.csv` inside the `data/` folder
- Dataset available on [Kaggle — Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)

**4. Run the notebook**
```bash
jupyter notebook notebooks/Netflix_Content_Analysis.ipynb
```

Or run the Python script directly:
```bash
python src/analysis.py
```

---

## 📂 Dataset

- **Source:** [Kaggle — Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Rows:** 8,790 titles
- **Columns:** show_id, type, title, director, country, date_added, release_year, rating, duration, listed_in

---

## 👤 Author

**Sourabh Yadav**  
[GitHub](https://github.com/sourabh0020) • [LinkedIn](https://www.linkedin.com/in/sourabhyadav96)

---

## 📄 License

This project is open source under the [MIT License](LICENSE).
