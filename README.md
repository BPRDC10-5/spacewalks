# Spacewalks

## Overview

Spacewalks is a Python analysis tool for researchers to generate visualization and statistical summaries of NASA's extravehicular activity datasets.

## Features

Key features of Spacewalks:

- Generates a CSV table of summary statistics of extravehicular activity crew sizes
-Generates a line plot to show the cumulative duration of space walks over 

## Pre-requisites

spacewalks was developed using Python version 3.12

To install and run Spacewalks you will need to have Python >=3.12 installed. You will also need the follwing libraries:

- [NumPy](https://www.numpy.org/) >=2.0.0 - Spacewalk's test suite uses NumPy's statistical functions
- [Matplotlib](https://matplotlib.org/stable/index.html) >=3.0.0  - Spacewalks uses Matplotlib to make plots
- [pytest](https://docs.pytest.org/en/8.2.x/#) >=8.2.0  - Spacewalks uses pytest for testing
- [pandas](https://pandas.pydata.org/) >= 2.2.0 - Spacewalks uses pandas for data frame manipulation 

## Installation Instructions

-Clone the Spacewalks repository to your local machine using git. If you don't have Git installed, you can download it from the official Git website

'''
git clone https://github.com/rbeowski/spacewalks.git
cd spacewalks
'''

- Install the necessary dependencies
'''
python -m pip install -r requirements.txt 
'''

-To ensure everythin is working correctly, run the tests using pytest.
'''
python -m pytest
'''

## Simple Usage Example

to run an analysis using the 'eva_data_analysis.py' script from the commmand line terminal, launch the script using Python as follows:

'''
python eva_data_analysis.py eva_data.json eva_data.csv
'''

The first argument is the path to the JSON data file.
The second argument is the path to the CSV data file.

