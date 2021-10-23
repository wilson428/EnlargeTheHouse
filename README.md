# EnlargeTheHouse

It's high time to resize the House of Representatives. Simulate how Congress apportions seats in the House, and try your own method!

## Data

There are two files in the [data](data) directory, `apportionment_2010.csv` and `apportionment_2020.csv`. These files were directly downloaded [from Census.gov](https://www.census.gov/data/tables/2020/dec/2020-apportionment-data.html) and lightly modified for readability. They contain both the official decennial population counts used for apportionment and the resulting number of seats, such that the user can check her calculations against the official results.

## Scripts

+ [Calculating_Apportionment.ipynb](https://colab.research.google.com/drive/1bBHxmUGtqs2kIH-myie5_bOZgFaT-hPT?usp=sharing): Recalculate apportionment in Python and check against official tally before monkeying with the assumptions.

+ [EnlargeTheHouse.ipynb](https://colab.research.google.com/drive/1TjyO-2bO4z5X_Hblw0AoINpxTMjWDkIS?usp=sharing): Use the code from the first notebook to test alternative sizes and measure the results.
