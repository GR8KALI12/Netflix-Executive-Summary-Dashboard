# Netflix-Executive-Summary-Dashboard
---

## Netflix Popular TV Shows — Power BI Dashboard

### Objectives
- Build an interactive dashboard representing TV show preferences on a yearly basis
- Analyze the total count and percentage distribution of titles aired on Netflix
- Identify the most popular content rating among all Netflix titles
- Visualize the geographical distribution of content by country and region

---

### Tools & Technologies
| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard development and data visualization |
| Power Query Editor | Data cleaning and transformation |
| DAX | Calculated measures and aggregations |
| Power BI Online Service | Report publishing and sharing |
| Kaggle | Data source retrieval |

---

### Data Source
Dataset retrieved from Kaggle — [Netflix Data Visualization Notebook](https://www.kaggle.com/code/joshuaswords/netflix-data-visualization/notebook)

- `netflix_titles.csv` — Primary dataset containing Netflix show metadata
- `netflix_icon.png` — Branding asset used within the report

---

### Implementation & Execution

**1. Data Ingestion**
Downloaded the dataset from Kaggle and imported the CSV file into Power BI Desktop.

**2. Data Cleaning** *(via Power Query Editor)*
- Removed missing values and duplicate records
- Standardized text formatting using find-and-replace techniques and letter case normalization
- Ensured overall data consistency across all fields

**3. Data Transformation & Modeling**
Applied necessary transformations post-cleaning to prepare the data for visualization, including column profiling and data type validation.

**4. Dashboard Development**
- Added a **KPI visual** to highlight the most popular content rating using the `MAXX` DAX function
- Implemented a **tile-based slicer** to enable year-wise filtering across all visuals
- Created a **DAX measure** using the `DIVIDE` function to calculate the percentage share of titles by rating
- Designed a **horizontal bar chart** to display the total count of titles by country, segmented by TV shows vs. Movies

---

### Key Observations

- **Most Popular Rating:** `TV-MA` emerged as the dominant content rating across all Netflix titles
- **Content Type Split:** Contrary to initial expectations, Netflix hosts significantly more Movies than TV Shows overall
- **Geographic Distribution:** The United States leads by a substantial margin in total content volume, followed by the United Kingdom and India, with the UK edging ahead, though still notably behind India in overall contribution

---

### Key Learnings
- Data profiling and exploratory data analysis (EDA)
- Data cleaning and imputation techniques
- Writing DAX queries for aggregated measures and calculated columns
- Applying data visualization best practices — including selecting the appropriate chart type to communicate insights effectively

---
