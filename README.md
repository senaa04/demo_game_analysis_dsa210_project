# demo_game_analysis_dsa210_project

## PROJECT OVERVIEW

In this project, I aim to analyze whether the presence of video game demos influence the commercial success of full games and the review score of full games. By combining the datasets that I will collect, I plan to explore whether demo popularity leads to commercial popularity and whether games sell more if they have demos.

## MOTIVATION

Ever since I was a kid, video games have intrigued me. Before I buy a game, I usually look at the reviews to get a feel for how it was received. If the game has a demo, I can download it and try it for myself. However, many game studios avoid developing demos since it takes time and effort. My plan is to understand if demos contribute to sales so that it is valuable for developers and players to have a demo in hand.

## DATA SOURCES

Game Review Data: I plan to use Metacritic and Steam games dataset which contains user and critic review.
Sales Data: VGChartz/Kaggle. This dataset provides global sales of games. 
General Game Data and Demo Data: Steam also provides data about demos and game attributes.

For Steam Store Games dataset: https://www.kaggle.com/datasets/mistercerberus/steam-games-dataset

For Metacritic Review Dataset: https://www.kaggle.com/datasets/henrylin03/metacritic-games-user-reviews-and-metascores/data


For Game Sales Dataset: https://www.kaggle.com/datasets/gregorut/videogamesales( I will be using this dataset if the wanted steam game data is in this dataset.)
    
If not enough data is found, I can use this dataset: https://www.kaggle.com/datasets/trolukovich/steam-games-complete-dataset

## PROJECT PLAN

For data collection I plan to collect datasets of Metacritic, Steam and VGChartz from Kaggle. According to these datasets, I will identify the games that have demos.

Then, I will merge the datasets based on if the game has a demo or not, the sale rates, and the reviews.

Later, I will explore the effect that demos have on the overall positive/negative experience of the player and the sales of the full games.

## 1.	Data Cleaning and Merging Plan
•	Clean the games and sales datasets and create common titles.

•	Find demos and matching game.

•	Merge Steam data with Metacritic and VGChartz data.

## 2.	Exploratory Data Analysis (EDA)
•	Distribution of global sales – Histogram of global sales across all games in the dataset.

•	Distribution of Metacritic scores – Histogram of review scores for all games.

•	Using boxplot to compare scores of demos and non-demo games.

•	Using boxplot to compare the sales of demos and non-demo games.

•	Using scatter plot to observe if demo popularity is directly proportional with sales of the game.
(I took help from AI to guide me through EDA part above.)

## HYPOTHESIS
This project is contructed by two main hypotheses:

## 1.	First Hypothesis
H0: Demo presence has no effect on full game scores.

Ha: Demo presence increases full game scores.

## 2.	Second Hypothesis
H0: Demo popularity has no effect on full game sales.

Ha: Demo popularity increases the full game sales.