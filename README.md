# Palmer Penguins: Data Cleaning and EDA

## Dataset
I used the Palmer Penguins dataset from seaborn-data on GitHub (https://raw.githubusercontent.com/mwaskom/seaborn-data/master/penguins.csv). It has 344 penguins and 7 columns: species, island, bill length, bill depth, flipper length, body mass, and sex.

## Cleaning Steps
1. Checked the shape, data types, and summary statistics.
2. Found 2 missing values in each measurement column (the same 2 penguins) and 11 missing values in sex.
3. Checked for duplicate rows and found none.
4. Dropped the 2 rows with no measurements, leaving 342 rows.
5. Filled the 11 missing sex values with "Unknown".
6. Checked outliers with the IQR method and found none.

## Key Observations
1. Gentoo penguins are the heaviest, at around 5,000 g on average.
2. Flipper length and body mass are strongly linked (about 0.87).
3. In the bill length vs bill depth plot, each species forms its own cluster.

## Files
- eda_penguins.ipynb: loading, cleaning, and charts
- data/raw_dataset.csv: original data
