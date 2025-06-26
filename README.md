# Netflix Movie Data Analysis

This project analyzes a Netflix movie dataset using Python and Jupyter Notebook. The analysis includes data cleaning, feature engineering, and exploratory data analysis to uncover insights about movie genres, popularity, vote averages, and release years.

## Project Structure

- `mymoviedb.csv` — The dataset containing movie information.
- [`netflix.ipynb`](netflix.ipynb) — Jupyter Notebook with all analysis code and visualizations.
- `README.md` — Project overview and instructions.

## Steps Performed

1. **Import Libraries**  
   Used `numpy`, `pandas`, `matplotlib`, and `seaborn` for data manipulation and visualization.

2. **Load Dataset**  
   Loaded `mymoviedb.csv` into a pandas DataFrame.

3. **Initial Exploration**  
   Displayed the first few rows, checked data types, and summarized the dataset.

4. **Data Cleaning**  
   - Checked and removed duplicates.
   - Converted `Release_Date` to datetime and extracted the year.
   - Dropped unnecessary columns: `Overview`, `Original_Language`, `Poster_Url`.
   - Handled missing values.

5. **Feature Engineering**  
   - Categorized `Vote_Average` into bins: not_popular, below_avg, average, popular.
   - Split and exploded the `Genre` column for better analysis.

6. **Exploratory Data Analysis**  
   - Analyzed genre distribution.
   - Visualized vote average and genre counts.
   - Identified movies with highest and lowest popularity.
   - Plotted the distribution of movies by release year.

## How to Run

1. Open [`netflix.ipynb`](netflix.ipynb) in Jupyter Notebook or VS Code.
2. Ensure `mymoviedb.csv` is in the same directory.
3. Run the notebook cells sequentially to reproduce the analysis and visualizations.

## Example Insights

- Most common genres and their distribution.
- Years with the most movie releases.
- Movies with the highest and lowest popularity.
- Distribution of vote averages among movies.

---

**Author:**  
*Netflix Movie