# 🎬 IMDb Movie Analysis

> Exploratory SQL + Python analysis of IMDb / box-office data — surfacing what the
> top-grossing movies have in common and how runtime relates to revenue.

![status](https://img.shields.io/badge/status-complete-success)
![python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![sql](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)

> **Note:** This was my first data project. I've kept it as part of my learning record;
> for more recent work see my [pinned repositories](https://github.com/leokariuki).

## 📌 Business Problem
A studio deciding what to greenlight wants to know which characteristics — runtime,
genre, release timing — are associated with strong box-office performance, so it can
make better investment and scheduling decisions.

## 🎯 Objectives
- Identify the top-grossing movies and what they have in common.
- Explore the relationship between movie runtime and revenue.
- Practise SQL extraction and Python-based EDA / visualization.

## 🗂️ Data
IMDb-derived movie data (title, release year, runtime, revenue, ratings) combined with
Box Office Mojo and TMDB sources.
> Raw data files are large and should be treated as inputs only — download from the
> original sources rather than relying on copies in the repo.

## 🏗️ Workflow
`SQL extraction → Python cleaning (Pandas) → EDA & visualization (Matplotlib/Seaborn)`

## 🔑 Key Findings
- The highest-grossing movies most often had runtimes in the **100–130 minute** range.
- A handful of genres appeared consistently among the top earners.

> 📊 *Add 1–2 of your best charts here (e.g. `runtime_vs_revenue.png`) to make the findings visual.*

## 🚀 Quickstart
```bash
git clone https://github.com/leokariuki/myproject1.git
cd myproject1
pip install -r requirements.txt   # add this file: pandas, matplotlib, seaborn, jupyter
jupyter lab student.ipynb
```

## 🔮 Future Improvements
- Rebuild as a reproducible notebook with a clean `data/` download script.
- Add a simple revenue-prediction model (regression) on top of the EDA.

## 👤 Author
**Leo Kariuki** — [LinkedIn](https://www.linkedin.com/in/leokariuki/) · [Portfolio](https://leokariuki.lovable.app)
