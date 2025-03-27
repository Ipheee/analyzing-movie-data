TASK
Analysing Movie Data

Scenario: You've been given a dataset of movie title, release year, genre, runtime, and rating.

Task:

1. Data Import & Preparation:

a. Load the movie dataset into a Pandas DataFrame using the pd.read_csv() function.

b. Explore the DataFrame using df.head(), df.info(), and df.describe().

c. Clean the data:

i. Handle any missing values (e.g., using df.fillna()).

ii. Convert data types as needed (e.g., using pd.to_numeric()).


2. Data Exploration and Analysis:

a. NumPy:

i. Calculate the average runtime of movies in each genre using np.mean() and groupby operations.

ii. Find the movie with the longest runtime using np.argmax().

b. Pandas:

i. Create a new column for "movie age" by calculating the difference between the current year and the release year.

ii. Filter the DataFrame to display movies released in a specific year range.

iii. Analyze the relationship between runtime and rating using correlation (df.corr()).

c. Matplotlib:

i. Create a histogram to visualise the distribution of movie ratings using plt.hist().

ii. Generate a scatter plot to show the relationship between runtime and rating using plt.scatter().

iii. Create a bar chart to compare the average rating of movies in different genres using plt.bar().

3. Data Visualization:

a. Use Matplotlib to create visualisations that highlight interesting patterns or insights from the data.

b. Add titles, labels, and legends to make your visualisations informative.
