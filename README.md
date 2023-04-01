I'll analyse the data in .xlsx format used is from a pomodoro app named [Materlist](https://masterlistapp.com) which has been collecting my study information for over 2 years.


[Here is my Kagge Notebook](https://www.kaggle.com/code/itszehra/study-analysis)
# Study Analysis 
This repository contains a Jupyter notebook `data_manipulation.ipynb` that demonstrates data manipulation techniques using the Python libraries NumPy, Pandas, and Seaborn.

## Getting Started
To run the notebook, you can either:

1. Download the repository as a ZIP file and extract it on your computer, or
2. Clone the repository using Git by running the following command in your terminal: `git clone https://github.com/itszehrakaya/study-analysis.git`

Then, navigate to the `data_manipulation.ipynb` file and open it in Jupyter Notebook or Jupyter Lab.

## Prerequisites
You will need to have Python 3 installed on your computer along with the following libraries:

- NumPy
- Pandas
- Seaborn
- Matplotlib (for data visualization)

You can install these libraries using pip, a package installer for Python. Open your terminal and type the following command:

`pip install numpy pandas seaborn matplotlib`
## Data
The data used in this notebook is from an individual study/work tracking app, and it includes personal work sessions. The data is stored in a Microsoft Excel file called `masterlistdatacopy.xlsx`. The file includes the following columns:

- `Date`: The date of the work session
- `Start Time`: The start time of the work session
- `End Time`: The end time of the work session
- `Time Focused`: The duration of the work session in minutes
- `Task`: The subject or project being worked on

## Description
The Jupyter notebook `data_manipulation.ipynb` contains examples of data manipulation techniques, including:

- Loading data into Pandas data frames from Excel files using Pandas' `read_excel()` method
- Filtering data using boolean indexing and the `loc` method.
- Handling missing data using Pandas' `dropna()` and `interpolate()` methods
- Updating data using the `update()` method
- Removing leading and trailing whitespaces from string columns using the `str.strip()` method
- Converting string columns to datetime using Pandas' `to_datetime()` method
- Sorting data frames using Pandas' `sort_values()` method
- Grouping data and performing aggregate calculations using Pandas' `groupby()` method and the `.agg()` function
- Calculating the sum of a column using Pandas' `sum()` method
- Finding the largest values using Pandas' `nlargest()` method
- Resetting index using the `reset_index()` method
- Converting data to NumPy arrays using the .values attribute and the to_numpy() method
- Creating a multi-index using the `MultiIndex()` function
- Reshaping data using Pandas' `unstack()` method
- Visualizing data using Seaborn's `countplot()` function

## Contributing
If you would like to contribute to this project, feel free to submit a pull request.


