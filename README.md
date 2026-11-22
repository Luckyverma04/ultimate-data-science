# Ultimate Data Science 🚀

A growing collection of my **Data Science learning notes, hands-on Jupyter notebooks, practice datasets, and mini-projects**. This repository documents what I am learning and experimenting with, from NumPy and Pandas to visualization, web scraping, and practical data-processing projects.

> **Status:** Work in progress — I will keep adding new topics, exercises, and projects as I learn.

## 📚 Explore the repository

| Area | What's inside | Notebooks |
| --- | --- | ---: |
| [NumPy & Pandas](Basics%20of%20pandas%20numpy/) | Arrays, Series, DataFrames, file operations, cleaning, joins, grouping, reshaping | 8 |
| [Matplotlib & Seaborn](Matplotlib/) | Line, bar, pie, histogram, scatter, subplot, and Seaborn visualizations | 7 |
| [Web Scraping](Web_Scraping/) | HTTP requests, BeautifulSoup, extracting structured data from HTML | 2 |
| [Project 01 — Social Network](Project_01/) | JSON-based data cleaning and simple friend/page recommendations | 4 |
| [Project 02 — Coders of Bengaluru](Project_02/) | Parsing text records and preparing structured JSON data | 1 |

**Current repository:** 22 Jupyter notebooks across 5 learning/project sections, plus accompanying datasets and outputs.

## 🧠 Topics covered

### 1. NumPy & Pandas

| Notebook | Focus |
| --- | --- |
| [Basics_Numpy.ipynb](Basics%20of%20pandas%20numpy/Basics_Numpy.ipynb) | NumPy arrays, basic operations, and comparisons with Python lists |
| [3Darray.ipynb](Basics%20of%20pandas%20numpy/3Darray.ipynb) | Multidimensional arrays, indexing, slicing, shapes, and axis operations |
| [Pandas_Core.ipynb](Basics%20of%20pandas%20numpy/Pandas_Core.ipynb) | Series, DataFrames, and core Pandas operations |
| [Work_Csv.ipynb](Basics%20of%20pandas%20numpy/Work_Csv.ipynb) | Reading, filtering, displaying, and exporting CSV files |
| [Cleaning.ipynb](Basics%20of%20pandas%20numpy/Cleaning.ipynb) | Missing values, duplicates, string handling, and data-cleaning techniques |
| [Merging.ipynb](Basics%20of%20pandas%20numpy/Merging.ipynb) | Combining DataFrames with merge operations |
| [Aggregation_Grouping.ipynb](Basics%20of%20pandas%20numpy/Aggregation_Grouping.ipynb) | Grouping, aggregations, and grouped summaries |
| [Melt_And_Pivot.ipynb](Basics%20of%20pandas%20numpy/Melt_And_Pivot.ipynb) | Reshaping data with melt and pivot operations |

### 2. Data visualization

| Notebook | Focus |
| --- | --- |
| [Intro.ipynb](Matplotlib/Intro.ipynb) | Introductory plotting and line charts |
| [Bar.ipynb](Matplotlib/Bar.ipynb) | Bar charts |
| [histogram.ipynb](Matplotlib/histogram.ipynb) | Histograms and distributions |
| [scatter.ipynb](Matplotlib/scatter.ipynb) | Scatter plots and relationships |
| [pieChart.ipynb](Matplotlib/pieChart.ipynb) | Pie charts and customization |
| [sub_Plots.ipynb](Matplotlib/sub_Plots.ipynb) | Arranging multiple plots in a figure |
| [Seaborn.ipynb](Matplotlib/Seaborn.ipynb) | Seaborn plots and example datasets |

### 3. Web scraping

| Notebook | Focus |
| --- | --- |
| [Request.ipynb](Web_Scraping/Request.ipynb) | Making HTTP requests and saving HTML responses |
| [Beautiful_soup.ipynb](Web_Scraping/Beautiful_soup.ipynb) | Parsing HTML and extracting data using BeautifulSoup |

The `Web_Scraping/htmls/` folder contains saved HTML pages for experimentation. Some cells make live network requests and therefore need internet access.

## 🛠️ Practice projects

### Project 01: Social Network Data Exploration

A set of JSON-based exercises that progressively explore social-network-style data.

1. [Introduction and user connections](Project_01/01_intro.ipynb)
2. [Cleaning user and relationship data](Project_01/02_cleaning.ipynb)
3. [People you may know](Project_01/03-people_you_may_know.ipynb)
4. [Pages you may like](Project_01/04_pages_you_like.ipynb)

**Skills practiced:** JSON handling, Python functions, data cleaning, sets, and recommendation logic.

### Project 02: Coders of Bengaluru

[Explore the notebook](Project_02/coders_of_bengaluru.ipynb)

An exercise in transforming text-based records (`initialdata.txt`) into structured data, with an accompanying `final.json` file.

**Skills practiced:** Reading text files, parsing, data transformation, and JSON output.

## 🧰 Tools and libraries

- **Language:** Python
- **Notebook environment:** Jupyter Notebook / JupyterLab
- **Data processing:** NumPy, Pandas
- **Visualization:** Matplotlib, Seaborn
- **Web scraping:** Requests, BeautifulSoup
- **Data formats:** CSV, JSON, Excel, HTML

## ▶️ Getting started

**1. Clone the repository**

```bash
git clone https://github.com/Luckyverma04/ultimate-data-science.git
cd ultimate-data-science
```

**2. (Recommended) Create and activate a virtual environment**

```bash
python -m venv .venv
```

Windows (PowerShell):

```powershell
.venv\Scripts\Activate.ps1
```

macOS / Linux:

```bash
source .venv/bin/activate
```

**3. Install the commonly used packages**

```bash
python -m pip install jupyterlab numpy pandas matplotlib seaborn requests beautifulsoup4 openpyxl
```

**4. Launch Jupyter**

```bash
jupyter lab
```

Open any `.ipynb` file to explore its examples. **Tip:** Some notebooks use relative paths such as `data.csv` or `htmls/page1.html`. Run those notebooks with their respective topic folder as the working directory (or adjust the paths) so local files are found correctly. Internet access may be needed for notebooks that download pages or Seaborn datasets.

## 📁 Folder structure

```text
ultimate-data-science/
├── Basics of pandas numpy/    # NumPy and Pandas notebooks + sample datasets
├── Matplotlib/                # Plotting notebooks + saved visualization
├── Web_Scraping/              # HTTP, HTML parsing, saved HTML pages
│   └── htmls/
├── Project_01/                # Social network exercises + JSON data
├── Project_02/                # Coders of Bengaluru parsing exercise
├── .gitignore
└── README.md
```

## 🔄 Learning in progress

This is an **actively evolving learning repository**, not a finished library or production application. New notebooks and projects will be added over time, and existing examples may be refined as I improve my understanding.

---

*Learning by building, practicing, and documenting along the way.*
