# Project Overview

# Introduction
Real-world data rarely comes clean. Using Python and its libraries, you will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling. You will document your wrangling efforts in a Jupyter Notebook, plus showcase them through analyses and visualizations using Python (and its libraries) and/or SQL.

The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for you to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. More on this soon.

# Project Steps Overview
Your tasks in this project are as follows:

* Step 1: Gathering data

* Step 2: Assessing data

* Step 3: Cleaning data

* Step 4: Storing data

* Step 5: Analyzing, and visualizing data

* Step 6: Reporting
    * your data wrangling efforts
    * your data analyses and visualizations

If you want to work outside of the Udacity classroom, the following software requirements apply:
* You need to be able to work in a Jupyter Notebook on your computer. Please revisit our Jupyter Notebook and Anaconda tutorials earlier in the Nanodegree program for installation instructions.
* The following packages (libraries) need to be installed. You can install these packages via conda or pip. Please revisit our Anaconda tutorial earlier in the Nanodegree program for package installation instructions.
  * pandas
  * NumPy
  * requests
  * tweepy
  * json
* You need to be able to create written documents that contain images and you need to be able to export these documents as PDF files. This task can be done in a Jupyter Notebook, but you might prefer to use a word processor like Google Docs, which is free, or Microsoft Word.
A text editor, like Sublime, which is free, will be useful but is not required.

## Project Motivation
Context
Your goal: wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. The Twitter archive is great, but it only contains very basic tweet information. Additional gathering, then assessing and cleaning is required for "Wow!"-worthy analyses and visualizations.

## The Data
In this project, you will work on the following three datasets.
* Enhanced Twitter Archive
* Additional Data via the Twitter API
* Image Predictions File

## Step 1: Gathering Data
In this step, you will gather all three pieces of data as described below in the "Data Gathering" section in the `wrangle_act.ipynb` notebook.

## Step 2: Assessing Data
After gathering all three pieces of data, assess them visually and programmatically for quality and tidiness issues. Detect and document at least **eight (8) quality issues** and **two (2) tidiness issues** in the "Accessing Data" section in the `wrangle_act.ipynb` Jupyter Notebook.

You need to use two types of assessment:
**Visual assessment:** each piece of gathered data is displayed in the Jupyter Notebook for visual assessment purposes. Once displayed, data can additionally be assessed in an external application (e.g. Excel, text editor).
**Programmatic assessment:** pandas' functions and/or methods are used to assess the data.

**Step 3: Cleaning Data**
Clean all of the issues you documented while assessing. Perform this cleaning in the "Cleaning Data" section in the `wrangle_act.ipynb`.

**Step 4: Storing Data**
In the "Storing Data" section in the `wrangle_act.ipynb` notebook, store the cleaned master DataFrame in a CSV file with the main one named `twitter_archive_master.csv`. If additional files exist because multiple tables are required for tidiness, name these files appropriately. Additionally, you may store the cleaned data in a SQLite database (which is to be submitted as well if you do).

**Step 5: Analyzing and Visualizing Data**
In the Analyzing and Visualizing Data section in your wrangle_act.ipynb Jupyter Notebook, analyze and visualize your wrangled data.

You must produce at least **three (3) insights** and **one (1) visualization**.

**Step 6: Reporting**
Create a **300-600 word written report** called `wrangle_report.pdf` or `wrangle_report.html` that briefly describes your wrangling efforts. This is to be framed as an internal document.
Create a **250-word-minimum written report** called `act_report.pdf` or `act_report.html` that communicates all the insights and displays the visualization(s) produced from your wrangled data. 
You must clearly document the piece of assessed and cleaned (if necessary) data used to make each analysis and visualization.
