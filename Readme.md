# NBA Career Longevity Prediction

This repository contains the code for the NBA Career Longevity Prediction project developed for the CS 513 course. The project aims to predict the career longevity of NBA players based on various features and factors.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Predicting the career longevity of NBA players can provide valuable insights for teams, players, and analysts. This project utilizes machine learning techniques to build a predictive model that estimates how long a player's career will last. By considering a range of player attributes, performance metrics, and external factors, the model can provide valuable predictions.

## Requirements

To run the code in this repository, you need to have the following dependencies installed:

- Python 3.x
- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn

## Installation

1. Clone this repository to your local machine using the following command:

   ```
   git clone https://github.com/kevin46dsa/NBA-Career-Longevity-Pridiction.git
   ```

2. Change your working directory to the project folder:

   ```
   cd NBA-Career-Longevity-Pridiction
   ```

3. Install the required dependencies using the following command:

   ```
   pip install -r requirements.txt
   ```

## Usage

1. Ensure that you have the necessary dataset in the correct format (see [Dataset](#dataset) section).

2. Execute the `main.py` file to run the NBA career longevity prediction model:

   ```
   python main.py
   ```

3. The model will generate predictions for the career longevity of NBA players and display the results.

## Dataset

The dataset used in this project contains information about NBA players, including their attributes, performance metrics, and career duration. The dataset should be in a CSV file format with the following columns:

- `Player`: Player's name
- `Age`: Age at the end of the season
- `G`: Games played
- `MP`: Minutes played per game
- `FG`: Field goals made per game
- `FGA`: Field goals attempted per game
- `FG%`: Field goal percentage
- `3P`: Three-pointers made per game
- `3PA`: Three-pointers attempted per game
- `3P%`: Three-point percentage
- `2P`: Two-pointers made per game
- `2PA`: Two-pointers attempted per game
- `2P%`: Two-point percentage
- `FT`: Free throws made per game
- `FTA`: Free throws attempted per game
- `FT%`: Free throw percentage
- `ORB`: Offensive rebounds per game
- `DRB`: Defensive rebounds per game
- `TRB`: Total rebounds per game
- `AST`: Assists per game
- `STL`: Steals per game
- `BLK`: Blocks per game
- `TOV`: Turnovers per game
- `PF`: Personal fouls per game
- `PTS`: Points per game
- `Career_Length`: Number of seasons played

Make sure to prepare the dataset and place it in the appropriate directory before running the code.

## Model Training

The code provided in the repository already includes a pre-trained model. However, if you wish to train the model from scratch, you can execute the `train_model.py` file:

```
python train_model.py
``
