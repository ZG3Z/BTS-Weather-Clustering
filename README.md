# BTS Weather Clustering 

* [Introduction](#introduction)
* [Data Preparation](#data-preparation)
* [Data Analysis](#data-analysis)
* [Machine Learning Models](#machine-learning-models)
* [Conclusion](#conclusion)

## Introduction

This project focuses on the analysis of weather conditions and their potential impact on the performance of Base Transceiver Stations (BTS) in Orange's network and competitors' networks. The analysis encompasses a variety of tasks, including data preparation, statistical analysis, comparative analysis, visualization, and the application of machine learning models. 

## Data Preparation

#### Data Sources
* Weather data is sourced from files labeled "A..", "B...", etc., providing temperature indicators for stations on different days in 2017.
* Station locations are specified in "kody_stacji.csv," with parameter codes explained in "kody_parametr.csv."
* Information about BTS is available in "bts.csv," detailing the operator, location, and supported technology.
* Anomalies in BTS functionality are recorded in "bts_anomalie_pct.xlsx," indicating the percentage of anomalies each month.

#### Data Processing
* Merged data from various sources using appropriate identifiers.
* Aggregated weather data to daily averages.
* Combined location data by linking geographic coordinates with place names.

## Data Analysis

#### Statistical Analysis
* Conducted exploratory data analysis, summarizing and analyzing datasets.

#### Comparative Analysis
* Compared Orange's network with competitors' networks based on relevant parameters.

#### Visualization
* Visualized weather data and network locations on a map.
* Identified stations prone to extreme weather conditions or experiencing significant weather changes.

## Machine Learning Models

#### Clustering
* Applied clustering techniques to identify stations with similar weather conditions and anomaly rates.

## Conclusion
* Evaluated the impact of weather on BTS anomalies.
