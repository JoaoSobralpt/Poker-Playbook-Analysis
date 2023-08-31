Poker-Playbook-Analysis: A Comparative Study of Winner and Losing players
(Mid Bootcamp Project)

This project aims to analyze and profile poker players by exploring their gameplay statistics, predicting player types, and uncovering insights into the strategies employed by different player categories.
The project utilizes data analysis, statistical hypothesis testing, logistic regression, and data visualization techniques.

Project Overview
Poker Player Profiling is an in-depth analysis of poker players' strategies and behaviors to differentiate between winning players (Sharks) and losing players (Fish). 
The project involves various stages, including data collection, preprocessing, hypothesis testing, logistic regression modeling, and data visualization.

Objective
The main objective of this project is to understand the differences in statistics and gameplay between winning and losing poker players. 
The secondary objective of the project consists of developing a predictive model capable of classifying poker players into distinct categories based on their gameplay statistics. 
This model allows us to understand the factors influencing players' success and provide actionable insights to improve poker strategies.

Population
The project focuses on poker players participating in Cash NL 25(0.10$-0.25$) poker rooms on PokerKing platform. 
This population includes a diverse group of players with varying levels of experience and skill.

Data Details
The dataset consists of 1.5 million hands played by players on the PokerKing platform. 
The hands data was collected from hand history files, transformed into CSV format using PokerTracker, and imported into Jupyter Notebook for analysis.

Hypothesis Testing
Hypothesis testing is conducted to identify significant gameplay statistics that exhibit notable differences between winning and losing players.
Key statistics are selected based on p-values, allowing us to gain insights into the strategies employed by different player types.

Logistic Regression Modeling
Logistic regression is employed to predict player types (Fish or Shark) based on selected significant statistics.
Different iterations of the model are explored to optimize accuracy, precision, recall, and F1-score metrics.
The model helps differentiate between player types and provides insights into how gameplay statistics influence player success.

Data Visualization
Data visualization is crucial to showcasing project insights. 
Tableau, Equilab and Pokersnowie were used to create interactive visualizations that highlight the differences in statistics 
between player types, distribution of hands played, winning rates, and correlation between significant statistics.

Results and Conclusion
The project showcased through hypothesis testing  that there are at least 9 significant statistics that have a great impact on winnings/losses of diferent poker players.
The logistic regression model achieved an accuracy of 65.59% in predicting player types. Precision, recall, and F1-score metrics vary for different player types, indicating the model's ability to differentiate between Fish and Shark players. 
However, the model's performance is not consistent across both categories, with some instances of misclassification.

