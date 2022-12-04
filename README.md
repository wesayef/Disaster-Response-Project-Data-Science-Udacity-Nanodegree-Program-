# Disaster Response Project ( Data Scientist - UdacityNanodegree Program)
## Table of Contents
1. [Introduction](https://github.com/louisteo9/udacity-disaster-response-pipeline#introduction)
2. [File Descriptions](https://github.com/louisteo9/udacity-disaster-response-pipeline#file-descriptions)
3. [Installation](https://github.com/louisteo9/udacity-disaster-response-pipeline#installation)
4. [Instructions](https://github.com/louisteo9/udacity-disaster-response-pipeline#instructions)
5. [Acknowledgements](https://github.com/louisteo9/udacity-disaster-response-pipeline#acknowledgements)
6. [Screenshots](https://github.com/louisteo9/udacity-disaster-response-pipeline#screenshots)

## Introduction
This project is part of the Udacity's Data Scientist Nanodegree Program in collaboration with [Figure Eight](https://www.figure-eight.com/).

In this project, the pre-labeled disaster messages will be used to build a disaster response model that can categorize messages received in real time during a disaster event, so that messages can be sent to the right disaster response agency.

This project includes a web application where disaster response worker can input messages received and get classification results.

## Dataset
The data in this project comes from Figure Eight - Multilingual Disaster Response Messages. This dataset contains 30,000 messages drawn from events including an earthquake in Haiti in 2010, an earthquake in Chile in 2010, floods in Pakistan in 2010, super-storm Sandy in the U.S.A. in 2012, and news articles spanning a large number of years and 100s of different disasters.

The data has been encoded with 36 different categories related to disaster response and has been stripped of messages with sensitive information in their entirety.

Data includes 2 csv files:

1. disaster_messages.csv: Messages data.
2. disaster_categories.csv: Disaster categories of messages.

## File Descriptions
### Folder: app
**run.py** - python script to launch web application.<br/>
Folder: templates - web dependency files (go.html & master.html) required to run the web application.

### Folder: data
**disaster_messages.csv** - real messages sent during disaster events (provided by Figure Eight)<br/>
**disaster_categories.csv** - categories of the messages<br/>
**process_data.py** - ETL pipeline used to load, clean, extract feature and store data in SQLite database<br/>
**ETL Pipeline Preparation.ipynb** - Jupyter Notebook used to prepare ETL pipeline<br/>
**DisasterResponse.db** - cleaned data stored in SQlite database

### Folder: models
**train_classifier.py** - ML pipeline used to load cleaned data, train model and save trained model as pickle (.pkl) file for later use<br/>
**classifier.pkl** - pickle file contains trained model<br/>
**ML Pipeline Preparation.ipynb** - Jupyter Notebook used to prepare ML pipeline


## Acknowledgements
* [Udacity](https://www.udacity.com/) for providing an excellent Data Scientist training program.
* [Figure Eight](https://www.figure-eight.com/) for providing dataset to train our model.

