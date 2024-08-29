# Unveiling Cricket Dynamics: Insights from Ball-By-Ball Data

## Overview

This project focuses on analyzing cricket match data to extract insights and predict player performance using various statistical and machine learning techniques. The analysis is centered around the 2022 T20 Asia Cup, leveraging data visualization and predictive modeling to understand key dynamics in the game of cricket.

## Project Motivation

Cricket is a globally popular sport with billions of viewers. Understanding player performance and game dynamics is crucial for teams and coaches to make informed decisions. This project aims to explore cricket data to identify trends, compare player statistics, and develop predictive models to enhance strategic decision-making.

## Key Features

- **Data Collection**: The dataset was gathered through web scraping from the ESPN Cricinfo website and is available on Kaggle.

- **Data Preprocessing**: 
  - Extracted missing features such as the bowling team and winning team.
  - Separated numerical runs from tags like 'W' (wicket) and 'NB' (no ball) using regular expressions.

- **Interactive Data Visualization**: Utilized Dash, a Python framework, to create interactive graphs. Users can toggle between overs and select specific teams and players for comparison.

- **Statistical Analysis**: Calculated batting and bowling statistics including runs scored, strike rates, wickets taken, and economy rates.

- **Predictive Modeling**: Developed linear regression models to predict the performance of batsmen and bowlers based on historical data.

## Project Structure

- **Data Source**: Cricket match data from the 2022 T20 Asia Cup, gathered via web scraping.

- **Data Processing and Visualization**: Implemented using Python, Pandas, and Dash.

- **Machine Learning Models**: Utilized scikit-learn for linear regression models to predict player performance.
  
- **Natural Language Processing (NLP)**: Explored using BERT models for tokenization to predict match outcomes.

## Transformer Models and NLP in Our Project

**Overview**:

- Used advanced NLP techniques with transformer models to analyze cricket commentary data.

- Aimed to extract meaningful insights and predict match outcomes and player performance.

**Transformer Models**:

- Employed BERT (Bidirectional Encoder Representations from Transformers) for processing cricket commentaries.

- BERT's bidirectional context understanding helped capture nuanced game dynamics.

**Attention Mechanisms and Attention Masks**:

- Utilized self-attention mechanisms to focus on key parts of the commentary relevant to predictions.

- Applied attention masks to ignore irrelevant data like padding, ensuring meaningful processing.

**Tokenization**:

- Used BERT’s tokenizer to break down commentary into tokens (words or subwords).

- Subword tokenization allowed handling of rare words by splitting them into smaller units, improving model processing.

**Neural Networks and Perceptrons**:

- Integrated a Multilayer Perceptron (MLP) to process numerical data, such as player statistics.

- Combined textual embeddings from BERT with numerical features to predict outcomes like runs scored or wicket likelihood.

**Large Language Models (LLMs)**:

- Leveraged BERT as an LLM to process and understand the cricket commentary.

- Despite computational challenges, BERT was key in integrating linguistic and numerical data for holistic predictions.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cricket-dynamics-analysis.git

2. Navigate to the project directory and install required packages

## Usage

- **Data Preprocessing**: Run the preprocessing scripts to clean and prepare the dataset for analysis.

- **Visualization**: Use the Dash app to explore player and team statistics interactively.

- **Model Training**: Train linear regression models to predict batsman runs and bowler wickets.

- **NLP Analysis**: Explore the preliminary code for predicting match outcomes using NLP techniques.

## Results

- Successfully visualized and compared player performance using interactive plots.
  
- Linear regression models demonstrated moderate success in predicting bowler performance (MSE of 1.17) but showed room for improvement in batsman predictions (MSE of 53.45).
  
- The NLP analysis, aimed at predicting match outcomes using contextual commentary data, could not be completed due to GPU limitations

## Future Work
- Improve the accuracy of batsman performance predictions by experimenting with more complex models and features.
  
- Complete the NLP analysis using available GPU resources to analyze the impact of contextual factors on match outcomes.
  
- Extend the analysis to include more cricket tournaments and formats for a comprehensive understanding of cricket dynamics.
  
## Contributors
- Pragnya Vijayan
- Vignesh Senthilkumar
  
## Acknowledgements
- Data was collected from ESPN Cricinfo and made available on Kaggle.
- Special thanks to the authors of the paper "Impact Calculation Of The Players Using The Cricket Commentary Corpus" for inspiration.

## Project Report
[Click here to read more about the project](https://drive.google.com/file/d/1XbnGVR8BAg7dFhreJKAl4cB-hanW_DNx/view?usp=sharing)
