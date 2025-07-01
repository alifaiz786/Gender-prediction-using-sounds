# Gender Detection in Author Names using Fuzzy Matching

This project explores gender inference from author names using fuzzy phonetic matching. It combines New York Times best-selling children's book author data with a baby name dataset using the NYSIIS phonetic algorithm to estimate the gender distribution of authors from 2008 to 2017.

# Objectives

- Apply fuzzy phonetic matching (NYSIIS) to match names with gender labels
- Identify gender distribution trends in children's book authors over time
- Use name-based datasets to infer missing demographic attributes
- Demonstrate practical use of approximate string matching in data analysis

# Datasets

- nyt_kids_yearly.csv – Author and title data from NYT bestsellers
- babynames_nysiis.csv – NYSIIS-transformed baby names with male/female percentages

# Key Steps

1. Imported fuzzy and pandas libraries
2. Created NYSIIS codes for author first names
3. Matched phonetic names against a labeled baby name dataset
4. Inferred author gender using percentage thresholds
5. Added gender information to the original author dataset
6. Counted gender distributions among authors

# Tools Used

- Python
- pandas
- fuzzy (NYSIIS phonetic algorithm)
- numpy
- Jupyter Notebook

# How to Run

1. Clone this repository
2. Ensure `datasets/nytkids_yearly.csv` and `datasets/babynames_nysiis.csv` are available
3. Open the notebook `notebook-2.ipynb` in Jupyter
4. Run all cells to reproduce the analysis


