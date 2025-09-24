# Fantasy Football Recommendations

## Objective
Can you predict a championship winning fantasy football team with the right predictive model? 
The purpose of this project is to define whether a predictive model can generate a winning fantasy football roster using existing data from past NFL seasons. 

## Data
The data used was obtained from Kaggle: [NFL Stats 2012-2024](https://www.kaggle.com/datasets/philiphyde1/nfl-stats-1999-2022)
This dataset has **4521** unique values providing an abundance of information from the last 12 seasons including the following:

1. Player Information
   - Player Name, Position, Team, Age, Height, Weight, College, and Draft round
    
2. Player Metrics
   - Statistical data on player performance, this includes pass yards, rush yards, receiving yards, touchdowns, interceptions, tackles, sacks, etc.. These metrics are broken down by season and game.

3. Fantasy Point
   - Calculated fantasy points for each player based on player performance, following popular fantasy football scoring rules.

4. Team affiliation
   -  The team(s) a player has been associated with during the specified time period, including any trades or transfers.
  
## Getting Started

To import the data into your notebook you will to authenticate Kaggle API.

-Make sure you have generated your API Token from Kaggle:

-Go to your Kaggle Account Settings

-Click Create New API Token

-This downloads a kaggle.json file.

-Place kaggle.json in the folder you specify in os.environ['KAGGLE_CONFIG_DIR'].

### Importing libraries

The required library are as follows:
*Used to setup enviromental variables*
`import os`

*The official Kaggle API package*
`from kaggle.api.kaggle_api_extended import KaggleAPI`

**Set Kaggle config directory**

The Kaggle API requires a kaggle.json file (your API credentials).

This file must be placed in a directory (usually ~/.kaggle on Linux/Mac or C:\Users\<username>\.kaggle on Windows).

## Author
Orangel Mendez - [gmail](omendez30@gmail.com)
  

