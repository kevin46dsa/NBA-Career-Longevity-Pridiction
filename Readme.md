<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

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
```

The script will load the dataset, preprocess the data, and train the model using machine learning techniques.

## Evaluation

To evaluate the model's performance, you can run the `evaluate_model.py` script:

```
python evaluate_model.py
```

The script will generate various evaluation metrics and visualizations to assess the predictive accuracy of the model.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please feel free to submit a pull request or open an issue.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code as per the terms of the license.

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/kevin46dsa/NBA-Career-Longevity-Pridiction.svg?style=for-the-badge
[contributors-url]: https://github.com/kevin46dsa/NBA-Career-Longevity-Pridiction/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/kevindsa2017
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
