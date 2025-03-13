# BMKG-Individual-Project
This is my individual project for the course Building and Mining Knowledge Graphs taught at Maastricht University. 

## Overview

This project constructs a Knowledge Graph (KG) for football players by integrating real-world player statistics with FIFA video
game data over two consecutive years (2021 and 2022). SPARQL queries are used to assess the quality of the knowledge
graph and to derive inferences that would be challenging using traditional structured data. Additionally, logistic regression
and a vanilla neural network are developed and compared for classifying players as released or retained. Both models
achieve a similar test score accuracy of ~ 67%. 

## Features

- **Data cleaning**: Merged Stats.csv files and FIFA.csv files year wise. 
- **Knowledge Graph construction**: Converted .csv files to KG/.ttl files.
- **SPARQL queries**: 5 queries for checking data quality, 3 queries for inference.
- **Classification model**: Vectorized KG and compared logistic regression and one layer neural network for classification task. 

## Installation steps

1. Clone the Repository:
   ```bash
   git clone https://github.com/sri-ram-swaminathan/BMKG-Individual-Project.git

   cd BMKG-Individual-Project
   ```
2. Set up virtual environment 

    ```bash
    python -m venv venv
    source venv/bin/activate 
    ```
3. Install dependencies 

    ```bash
    pip install -r requirements.txt
    ```
