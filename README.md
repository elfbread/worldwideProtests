# worldwideProtests

Python project for Code Louisville Data Analysis II in summer 2022.

Data sources:<br/> https://www.kaggle.com/datasets/kkhandekar/global-protest-tracker <br/>
              https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2021?select=world-happiness-report-2021.csv

PROJECT DESCRIPTION TO BE UPDATED: This project includes data for the ...

## Start-up instructions

Before starting, you need to download/install the following extensions in VS Code for Jupyter Notebook:

![Jupyter extension](extension.png)

Clone the repo to your computer. 

Package requirements are listed in the requirements.txt file. Install the libraries in the requirements.txt file using the following command:

`pip install -r requirements.txt`

Packages include:
- Pandas
- Numpy

Navigate to the folder and open main.ipynb with VS Code. Be sure to update the kernel in the upper right of VS Code (as shown in the screenshot below).The file import uses a public CSV saved in Google Sheets, a work around for users utilizing different operating systems (not having to adjust the import statement/file path).

## Important - be sure to update the kernel to the venv you are using in the upper right corner of VS Code (screenshot for assistance below):

![Setting kernel in VS Code](kernel.png)

## Important - SET YOUR FILE PATH at the beginning of the code. The program utilizes a *** LET STATEMENT *** that will allow the final CSV to export to a location of your choosing

## Let's talk project requirements:
Project plan (LINK)
Minimum 5 GitHub commits
Detailed README

Features used:
* Category 1: Read TWO data files (JSON, CSV, Excel, etc.)<br/>
    - Read in two CSV files from Kaggle (links above), including worldwide protests and world happiness report

* Category 2: Clean data, merge in pandas,  calculate a new value
    - Cleaned data (renaming columns, correcting boolean columns), merged dataframes, calculated a new value (Ladder_range)

* Category 3: Tableau dashboard

* Category 4: Virtual environment with instructions

* Category 5: Detailed README file with formatting and annotations in Jupyter Notebook
