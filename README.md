# CHPC Summer School 2025: Working with Data in Python
This repository contains a Python script for exploring and visualizing animal data, specifically focusing on animal species, their sizes, and vulnerabilities. The script demonstrates the use of pandas, numpy, matplotlib, and seaborn for data analysis and visualization.

# Table of Contents
Overview
Installation
Usage
Code Explanation
Contributing
License
Overview
This script performs various data manipulation and visualization tasks using the super-animals.csv dataset. The key tasks include:

# Importing and exploring the dataset.
Visualizing the distribution of animal sizes and species frequencies.
Subsetting data based on species and categories (e.g., birds).
Performing statistical analyses (mean, median, standard deviation) of animal sizes.
Exploring numerical data across species categories.
Visualizing data using histograms, box plots, and scatter plots.
Applying log transformations to the data for better visualization and understanding.

# Installation
Clone the repository:

```
git clone https://github.com/yourusername/chpc-summer-school-2025.git
```
Navigate to the project directory:

```cd chpc-summer-school-2025```
Install the required packages:

```pip install pandas numpy matplotlib seaborn```

# Usage
Modify the file path in the script to point to where the super-animals.csv file is located on your machine:

```os.chdir(r"/path/to/your/data")```
Run the Python script to process and analyze the data:

```python animal_data_analysis.py```
The script will produce visualizations, such as histograms, bar plots, and box plots, and provide insights into the data like summary statistics (mean, median, etc.) and species distributions.

Code Explanation
1. Data Import and Exploration
The ```super-animals.csv``` file is loaded into a pandas DataFrame.
Basic data exploration is performed, including checking the variable names, number of observations, and the number of columns.
2. Visualizations
Histogram: The script generates a histogram of animal sizes using seaborn's histplot.
Barplot: A barplot of species frequencies is created using seaborn's barplot.
Boxplot: Boxplots of animal sizes and weights are drawn for the bird species.
Scatterplot: A scatterplot visualizes the relationship between animal size and weight.
3. Statistical Summary
Summary statistics (mean, median, standard deviation) are computed for the animal size.
The script includes a five-number summary (min, 25th percentile, median, 75th percentile, max) for the size of animals by species.
4. Data Transformation
The script performs a log transformation on the Size and Weight variables of birds to examine the relationship between the two variables on a transformed scale.
5. Subset and Filter Data
Subsets of the data are created, including selecting only birds or filtering by species category (Birds and Mammals).
A frequency table and barplot of the vulnerability indices of the birds are also generated.
6. Grouping Data by Species
The script groups data by species and computes descriptive statistics for each group, providing insights into the distribution of animal sizes within each species.

# Contributing
Contributions are welcome! If you find any bugs or have suggestions for improvement, feel free to fork the repository and submit a pull request.

# Fork the repository
Create a new branch ```(git checkout -b feature-branch)```
Commit your changes ```(git commit -am 'Add new feature')```
Push to the branch ```(git push origin feature-branch)```
Create a new Pull Request

# License
This project is licensed under the MIT License - see the LICENSE file for details.
