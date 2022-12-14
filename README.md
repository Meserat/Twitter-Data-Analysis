# Twitter-Data-Analysis

### OverView

This project aims to understand twitter data through visualisations, transforming some features, and preparing it for appropriate modelling - topic modelling and sentiment analysis

## Repository Creation using template

### Data Source

Data source For this Project was given as sampled twitter data. (can be found in data folder)

## Installation Guide

        git clone https://github.com/Meserat/Twitter-Data-Analysis.git

        cd Twitter-Data-Analysis

        pip install -r requirements.txt

## Project Structure

### Notebooks

This folder holds the nooteboks used to process and visualize the data

Data exploration and Preprocessing - holds Data Exploratory features and visualizations

### Data

This folder holds the data of the project

#### africa_twitter_Data.zip

#### global_twitter_data.zip

#### Others cleaned data's

### tests

This folder holds unit test files

## Data preparation

First download dataset from [here](https://drive.google.com/drive/folders/19G8dmehf9vU0u6VTKGV-yWsQOn3IvPsd).
then extracted it and get two json file data (global_twitter_data.json, and africa_twitter_data.json)
after that create a git branch “bugfix” to fix the bugs in the fix_clean_tweets_dataframe.py and fix_extract_dataframe.py.
To fix the bugs in clean_tweets_dataframe.py, you have to carefully consider the data type conversion in pandas dataframe. Furthermore, removing or dropping unimportant rows or columns is the purpose of this challenge
