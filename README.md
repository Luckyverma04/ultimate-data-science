<div align="center">

# 📊 Ultimate Data Science

**Learn • Practice • Analyze • Visualize • Build**

My hands-on Data Science learning journey — Jupyter notebooks, datasets, visualizations, web scraping, and practical Python projects. This repository is actively growing as I explore new topics.

[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?logo=python&logoColor=white)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0)](https://seaborn.pydata.org/)
![Learning](https://img.shields.io/badge/Status-Actively%20Learning-brightgreen)

**22 notebooks · 5 topic/project areas · real code and chart outputs**

[📚 Learning topics](#-learning-roadmap) · [📸 Chart gallery](#-visualization-gallery) · [🧩 Projects](#-projects) · [🚀 Run locally](#-run-locally)

</div>

---

## 🧭 Learning roadmap

| Area | What I have practiced | Material |
|---|---|---|
| 🧮 **NumPy & Pandas** | Arrays, multidimensional data, DataFrames, cleaning, merging, grouping, reshaping | [8 notebooks](Basics%20of%20pandas%20numpy/) |
| 📊 **Matplotlib & Seaborn** | Line/bar/scatter/pie/histogram plots, subplots, styling, statistical charts | [7 notebooks](Matplotlib/) |
| 🌐 **Web scraping** | HTTP requests, HTML parsing, extracting structured data | [2 notebooks](Web_Scraping/) |
| 🧩 **Project 01 — Social Network** | Data cleanup, mutual-friend and page recommendations | [4 notebooks](Project_01/) |
| 📱 **Project 02 — Coders of Bengaluru** | Instagram-style profile text parsing and structured data | [1 notebook](Project_02/) |

> **In progress:** This is my learning workspace, not a finished course. More exercises and projects will be added.

---

## 📸 Visualization gallery

**These are actual chart images extracted from my Jupyter notebooks.** Select a chart to open its corresponding notebook and explore the Python code behind it.

| 📈 Line plots | 📊 Grouped bars |
|:---:|:---:|
| [<img src="docs/screenshots/line-comparison.png" alt="Line plots and comparisons" width="440"/>](Matplotlib/Intro.ipynb) | [<img src="docs/screenshots/grouped-bar.png" alt="Grouped bar chart" width="440"/>](Matplotlib/Bar.ipynb) |
| **🎯 Scatter with color and size** | **📉 Histogram** |
| [<img src="docs/screenshots/scatter-custom.png" alt="Customized scatter plot" width="440"/>](Matplotlib/scatter.ipynb) | [<img src="docs/screenshots/age-histogram.png" alt="Age distribution histogram" width="440"/>](Matplotlib/histogram.ipynb) |
| **🥧 Pie chart formatting** | **🖼️ Multi-panel subplots** |
| [<img src="docs/screenshots/pie-custom.png" alt="Pie chart with customized slices" width="440"/>](Matplotlib/pieChart.ipynb) | [<img src="docs/screenshots/subplots.png" alt="Multiple subplot arrangements" width="440"/>](Matplotlib/sub_Plots.ipynb) |
| **📦 Seaborn box plots** | **🌡️ Seaborn heatmaps** |
| [<img src="docs/screenshots/seaborn-boxplot.png" alt="Seaborn box plot" width="440"/>](Matplotlib/Seaborn.ipynb) | [<img src="docs/screenshots/seaborn-heatmap.png" alt="Seaborn heatmap" width="440"/>](Matplotlib/Seaborn.ipynb) |

<details>
<summary><b>See another chart: horizontal bar plot</b></summary>

[<img src="docs/screenshots/horizontal-bar.png" alt="Horizontal bar plot" width="700"/>](Matplotlib/Bar.ipynb)

</details>

### 🎨 Visualization techniques practiced

| Notebook | Techniques explored |
|---|---|
| [Intro](Matplotlib/Intro.ipynb) | `plot()`, line styles, colors, labels, legends, markers, chart titles, `xkcd()` styling |
| [Bar](Matplotlib/Bar.ipynb) | Vertical, grouped and horizontal bars; comparing categories, colors, annotations |
| [Histogram](Matplotlib/histogram.ipynb) | Frequency distributions and bin selection |
| [Scatter](Matplotlib/scatter.ipynb) | Relationships, markers, size, color, annotations and data groups |
| [Pie chart](Matplotlib/pieChart.ipynb) | Slice labels, percentages, explode, shadows, start angles, colors, stacked area chart |
| [Subplots](Matplotlib/sub_Plots.ipynb) | `subplot()` and `subplots()`, figure grids and layout adjustments |
| [Seaborn](Matplotlib/Seaborn.ipynb) | Themes, line/bar/scatter plots, hue, box plots, heatmaps |

---

## 🧩 Projects

### Project 01 — Social Network Analysis & Recommendations

A hands-on exercise in exploring nested JSON social-network data, cleaning records, and creating simple recommendations based on shared connections and liked pages.

| Step | Notebook | What I built / explored |
|---|---|---|
| 01 | [Inspect the data](Project_01/01_intro.ipynb) | Users, friend connections, and pages |
| 02 | [Clean the network](Project_01/02_cleaning.ipynb) | Missing data, repeated entries and inactive users |
| 03 | [People you may know](Project_01/03-people_you_may_know.ipynb) | Mutual-friend recommendations |
| 04 | [Pages you may like](Project_01/04_pages_you_like.ipynb) | Recommendations using liked-page overlap |

**Skills:** Python dictionaries and sets, JSON, exploratory inspection, data cleaning, recommendation logic.

### Project 02 — Coders of Bengaluru (Instagram-style profile data)

This project works with **social-media-style profile text** rather than a ready-to-use spreadsheet. I practiced extracting profile fields and converting messy text into structured data for future analysis.

| File | Purpose |
|---|---|
| [coders_of_bengaluru.ipynb](Project_02/coders_of_bengaluru.ipynb) | Parsing, extracting fields and converting values |
| [initialdata.txt](Project_02/initialdata.txt) | Original profile-style text input |
| [final.json](Project_02/final.json) | Structured JSON data file |

**What I practiced:** usernames and profile details, follower/post counts, `K`/`M` shorthand, chunking text, type conversion, JSON structuring.

> This notebook focuses on **extraction and structuring**. The chart gallery above shows the Matplotlib and Seaborn exercises; it is not presented as visualizations from this Instagram-profile project.

---

## 📚 Concepts and notebooks

### NumPy & Pandas

| Notebook | Concepts |
|---|---|
| [Basics_Numpy](Basics%20of%20pandas%20numpy/Basics_Numpy.ipynb) | Arrays, operations and comparisons with Python lists |
| [3Darray](Basics%20of%20pandas%20numpy/3Darray.ipynb) | Multidimensional arrays, indexing, slicing, shapes and axes |
| [Pandas_Core](Basics%20of%20pandas%20numpy/Pandas_Core.ipynb) | Series, DataFrames, indexing and transformations |
| [Work_Csv](Basics%20of%20pandas%20numpy/Work_Csv.ipynb) | Reading, filtering and writing CSV files |
| [Cleaning](Basics%20of%20pandas%20numpy/Cleaning.ipynb) | Missing values, duplicates, strings, `map()`, `apply()`, type casting |
| [Merging](Basics%20of%20pandas%20numpy/Merging.ipynb) | Inner/left/right/outer joins and combining tables |
| [Aggregation_Grouping](Basics%20of%20pandas%20numpy/Aggregation_Grouping.ipynb) | `groupby()`, multiple grouping keys and aggregation |
| [Melt_And_Pivot](Basics%20of%20pandas%20numpy/Melt_And_Pivot.ipynb) | Converting between long and wide formats |

### Web Scraping

| Notebook | Concepts |
|---|---|
| [Request.ipynb](Web_Scraping/Request.ipynb) | HTTP requests, responses, downloading HTML |
| [Beautiful_soup.ipynb](Web_Scraping/Beautiful_soup.ipynb) | BeautifulSoup, parsing book details and exporting CSV |

The [`Web_Scraping/htmls/`](Web_Scraping/htmls/) folder contains local HTML pages used for practice.

---

## 🛠️ Tools and tech

| Category | Tools |
|---|---|
| Language | Python |
| Notebook environment | Jupyter Notebook |
| Data analysis | NumPy, Pandas |
| Visualization | Matplotlib, Seaborn |
| Data collection | Requests, BeautifulSoup |
| Data formats | JSON, CSV, Excel, HTML |

## 🚀 Run locally

```bash
git clone https://github.com/Luckyverma04/ultimate-data-science.git
cd ultimate-data-science

python -m pip install notebook numpy pandas matplotlib seaborn requests beautifulsoup4 openpyxl
jupyter notebook
```

Open the notebook you want to explore. Some notebooks use local datasets, so run them with the appropriate working directory or adjust relative file paths. Some scraping and sample dataset exercises require an internet connection.

## 📁 Repository structure

```text
ultimate-data-science/
├── Basics of pandas numpy/     # NumPy and Pandas practice + datasets
├── Matplotlib/                 # Plotting and Seaborn notebooks
├── Web_Scraping/               # Requests, BeautifulSoup and HTML files
├── Project_01/                 # Social network recommendation project
├── Project_02/                 # Coders of Bengaluru profile parsing
├── docs/
│   └── screenshots/            # Actual chart PNGs used in this README
└── README.md
```

## 🖼️ Direct image links

These URLs work **after the `docs/screenshots/` images have been committed to the `main` branch**.

| Output | Direct image link |
|---|---|
| Line plot | [View PNG](https://raw.githubusercontent.com/Luckyverma04/ultimate-data-science/main/docs/screenshots/line-comparison.png) |
| Grouped bars | [View PNG](https://raw.githubusercontent.com/Luckyverma04/ultimate-data-science/main/docs/screenshots/grouped-bar.png) |
| Scatter plot | [View PNG](https://raw.githubusercontent.com/Luckyverma04/ultimate-data-science/main/docs/screenshots/scatter-custom.png) |
| Histogram | [View PNG](https://raw.githubusercontent.com/Luckyverma04/ultimate-data-science/main/docs/screenshots/age-histogram.png) |
| Pie plot | [View PNG](https://raw.githubusercontent.com/Luckyverma04/ultimate-data-science/main/docs/screenshots/pie-custom.png) |
| Subplots | [View PNG](https://raw.githubusercontent.com/Luckyverma04/ultimate-data-science/main/docs/screenshots/subplots.png) |
| Box plot | [View PNG](https://raw.githubusercontent.com/Luckyverma04/ultimate-data-science/main/docs/screenshots/seaborn-boxplot.png) |
| Heatmap | [View PNG](https://raw.githubusercontent.com/Luckyverma04/ultimate-data-science/main/docs/screenshots/seaborn-heatmap.png) |

---

<div align="center">

**Learning something new, one notebook at a time.**

Made by **[Lucky Verma](https://github.com/Luckyverma04)**

</div>
