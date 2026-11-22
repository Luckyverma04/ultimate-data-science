# Ultimate Data Science 🚀

**Learning by building, exploring data, and visualizing the results.**

This repository documents my hands-on data science learning journey: practice notebooks, datasets, data cleaning, visualization techniques, web scraping, and small Python projects. I keep adding new material as I learn.

> **Status:** Actively learning and updating · **22 Jupyter notebooks** · **5 learning and project areas**

## Explore

| Area | What I practiced | Jump in |
| --- | --- | --- |
| **NumPy & Pandas** | Arrays, dataframes, missing values, merges, grouping, reshaping | [8 notebooks](Basics%20of%20pandas%20numpy/) |
| **Matplotlib & Seaborn** | Chart types, styling, annotations, subplot layouts, statistical plots | [7 notebooks](Matplotlib/) |
| **Web scraping** | HTTP requests, extracting information from HTML and exporting CSV | [2 notebooks](Web_Scraping/) |
| **Project 01 — Social Network** | Exploring and cleaning social graph data; friend and page recommendations | [4 notebooks](Project_01/) |
| **Project 02 — Coders of Bengaluru** | Parsing Instagram-style profile information from text into structured JSON | [1 notebook](Project_02/) |

## Data visualization gallery 📊

These are **actual chart outputs from my Jupyter notebooks**, not stock images. Each image links to the notebook where I practiced the technique.

| Line charts and comparisons | Grouped bar charts |
| --- | --- |
| [![Line graph comparing players](assets/charts/line-comparison.png)](Matplotlib/Intro.ipynb) | [![Grouped bar chart comparing players](assets/charts/grouped-bar.png)](Matplotlib/Bar.ipynb) |
| **Scatter plots — color and marker size** | **Histogram — age distribution** |
| [![Customized scatter plot](assets/charts/scatter-custom.png)](Matplotlib/scatter.ipynb) | [![Age distribution histogram](assets/charts/age-histogram.png)](Matplotlib/histogram.ipynb) |
| **Pie charts — labels and emphasis** | **Multiple plots in one figure** |
| [![Customized pie chart](assets/charts/pie-custom.png)](Matplotlib/pieChart.ipynb) | [![Multi panel subplots](assets/charts/subplots.png)](Matplotlib/sub_Plots.ipynb) |
| **Seaborn — box plots** | **Seaborn — heatmaps** |
| [![Seaborn boxplot](assets/charts/seaborn-boxplot.png)](Matplotlib/Seaborn.ipynb) | [![Seaborn heatmap](assets/charts/seaborn-heatmap.png)](Matplotlib/Seaborn.ipynb) |

### Visualization techniques I practiced

| Notebook | Techniques |
| --- | --- |
| [Intro.ipynb](Matplotlib/Intro.ipynb) | Basic `plot()`, single and multiple lines, titles, axis labels, legends, colors, line styles, markers, and `xkcd()` style |
| [Bar.ipynb](Matplotlib/Bar.ipynb) | Vertical bars, grouped bars, horizontal bars, bar colors, and value annotations |
| [histogram.ipynb](Matplotlib/histogram.ipynb) | Histograms, bins, and understanding frequency distributions |
| [scatter.ipynb](Matplotlib/scatter.ipynb) | Relationships between variables, point size, conditional colors, annotations, and multiple groups |
| [pieChart.ipynb](Matplotlib/pieChart.ipynb) | Pie charts, colors, slice borders, explode, shadows, start angles, percentages, and stacked area plots |
| [sub_Plots.ipynb](Matplotlib/sub_Plots.ipynb) | `subplot()`, `subplots()`, 1×2 and 2×2 grids, figure sizing, and layout adjustments |
| [Seaborn.ipynb](Matplotlib/Seaborn.ipynb) | Themes, line plots, bar plots, scatter plots with hue, box plots, heatmaps, and example datasets |

The gallery highlights selected plots; **open the notebooks to see the other variations and the code behind each figure**.

## Projects 🧩

### Project 01 — Social Network: data cleaning and recommendations

Worked with JSON representing users, friendships, liked pages, and page information. The notebooks move from inspecting the data to cleaning it and implementing simple recommendation logic.

| Step | Notebook | What it does |
| --- | --- | --- |
| 01 | [Explore user connections](Project_01/01_intro.ipynb) | Load JSON, inspect users, friend connections, and pages |
| 02 | [Clean social network data](Project_01/02_cleaning.ipynb) | Handle missing user names, duplicate friends/pages, and inactive users |
| 03 | [People you may know](Project_01/03-people_you_may_know.ipynb) | Suggest connections using mutual friends |
| 04 | [Pages you may like](Project_01/04_pages_you_like.ipynb) | Recommend pages using overlap in users' liked pages |

**Main learning:** representing connected data in Python, cleaning nested JSON, using dictionaries and sets, and implementing recommendation rules.

### Project 02 — Coders of Bengaluru: Instagram-style profile data

In [coders_of_bengaluru.ipynb](Project_02/coders_of_bengaluru.ipynb), I worked with text containing social-media-style profile details. The notebook reads `initialdata.txt`, splits the records into chunks, extracts fields such as usernames, post counts and follower counts, handles `K`/`M` number notation, and prepares structured information.

- **Input:** [`initialdata.txt`](Project_02/initialdata.txt)
- **Notebook:** [`coders_of_bengaluru.ipynb`](Project_02/coders_of_bengaluru.ipynb)
- **Structured data file:** [`final.json`](Project_02/final.json)

**Main learning:** practical text parsing, data extraction, type conversion and turning semi-structured profile information into data that can be analyzed further.

> This is a parsing/data-structuring exercise. The charts in the gallery come from the Matplotlib/Seaborn notebooks, not from this Instagram-style profile notebook.

## NumPy & Pandas — from arrays to analysis

| Notebook | Topics |
| --- | --- |
| [Basics_Numpy.ipynb](Basics%20of%20pandas%20numpy/Basics_Numpy.ipynb) | Array operations, dimensions, performance and memory comparison with Python lists |
| [3Darray.ipynb](Basics%20of%20pandas%20numpy/3Darray.ipynb) | Multidimensional arrays, shape, slicing, indexing, `axis` and data types |
| [Pandas_Core.ipynb](Basics%20of%20pandas%20numpy/Pandas_Core.ipynb) | Series, DataFrames, indexing, selection and core transformations |
| [Work_Csv.ipynb](Basics%20of%20pandas%20numpy/Work_Csv.ipynb) | Reading CSV, filtering rows and writing updated CSV files |
| [Cleaning.ipynb](Basics%20of%20pandas%20numpy/Cleaning.ipynb) | Null detection, `dropna`, `fillna`, forward/backward fill, duplicates, strings, `astype`, `map` and `apply` |
| [Merging.ipynb](Basics%20of%20pandas%20numpy/Merging.ipynb) | Inner/left/right/outer joins and dataframe combination |
| [Aggregation_Grouping.ipynb](Basics%20of%20pandas%20numpy/Aggregation_Grouping.ipynb) | `groupby`, salary summaries, aggregations and grouping by multiple fields |
| [Melt_And_Pivot.ipynb](Basics%20of%20pandas%20numpy/Melt_And_Pivot.ipynb) | Wide/long format and `melt`/`pivot` practice |

## Web scraping 🌐

- [Request.ipynb](Web_Scraping/Request.ipynb) — HTTP requests, checking responses and downloading HTML pages for practice.
- [Beautiful_soup.ipynb](Web_Scraping/Beautiful_soup.ipynb) — extracting book titles, prices and ratings using BeautifulSoup and saving a CSV.
- [`htmls/`](Web_Scraping/htmls/) — saved HTML practice pages, so examples can be explored locally.

## Tools and libraries

**Python · Jupyter Notebook · NumPy · Pandas · Matplotlib · Seaborn · Requests · BeautifulSoup · JSON · CSV**

## Run the notebooks locally

1. Clone the repository and enter the folder:

   ```bash
   git clone https://github.com/Luckyverma04/ultimate-data-science.git
   cd ultimate-data-science
   ```

2. Install the core learning libraries in your Python environment:

   ```bash
   python -m pip install notebook numpy pandas matplotlib seaborn requests beautifulsoup4 openpyxl
   ```

3. Launch Jupyter:

   ```bash
   jupyter notebook
   ```

4. Open a notebook and run its cells. For notebooks that read local files, **run them with the notebook's folder as the working directory**, or adjust the relative dataset paths. Some Seaborn samples or scraping exercises require an internet connection.

## Learning log

This repository is **a work in progress**, not a finished course or production application. I use it to practice concepts, test ideas, learn from mistakes, and build projects incrementally. As I cover more topics, I will add notebooks, project notes, and selected visual results here.

---

**Explore the notebooks, follow the experiments, and check back for new topics.**
