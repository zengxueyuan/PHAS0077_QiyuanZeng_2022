# PHAS0077_QiyuanZeng_2022

## Coding
This project contains three ipynb code which have been labeled based on their running order

- 1. Data pre-process.ipynb

        This file is to integrate eight thyroid dataset files into one csv file.

- 2. Data analysis.ipynb

        Analyse the distribution of our dataset and handling the missing value problem

- 3. Modelling.ipynb

        Using ten machine learning algorithms to train thyroid classification prediction models.

        All the main outcome and accuracy, precision results are in this ipynb file. 

#
## Data sets

1. Download the dataset from UCI (https://archive.ics.uci.edu/ml/datasets/thyroid+disease), and store it into _UCI Machine Learning Repository Data_ file.

2. Transfer the .data and .test files in raw dataset into csv file so that we can read and process easily. These processed data are stored in 'Dataset' file

3. 'Dataset_edited' is a folder to store the data which have been cleaned and integrated in our research.

    - _new_data.csv_ is the file that has integrated all the data from eight raw dataset files. It contains 25453 instances.

    - _noMissing.csv_ is the file that has handled all the missing value in _new_data.csv_ file. It contains 19556 instances.

    - _processed_data.csv_ is the file that transfer the string 't/f' into integer '1/0' in order to make data analysis more easily.

