# Background & Motivation
This research project stems from a shared enthusiasm for mixed martial arts (MMA) and the burgeoning interest in content creation around this sport. The rise in popularity has led to increased speculation on past and future fights. Notably, the YouTube channel "Strike Savvy" caught our attention with its [video](https://youtu.be/TWafkxT699c?si=8Kc9wduSH8AubEW5) analysing the middleweight championship clash between Sean Strickland and Israel Adesanya. The video's utilisation of fight data to objectively compare fighter performances inspired us to delve into the practicality of treating this as a real-world bandit problem.

# Problem Statement
Our focus lies in scrutinising MMA fight data to determine if predicting a fighter's victory or defeat is feasible based on their performance indicators. Essentially, we aim to investigate the correlation between a fighter's in-fight performance and the fight’s outcome.

# Highlights of our Findings and Implications
Our research into MMA fight outcomes using bandit algorithms, namely Modified LinearUCB and Contextual Thompson Sampling, revealed a strong correlation between in-fight performance metrics and predictions in the Lightweight division. Their initial implementations—without optimisation—yielded an 86% accuracy rate and 89% accuracy rate respectively. We found that Thompson Sampling outperformed Linear UCB over time, possibly due to the nature of the algorithm making it more suitable for the unpredictable nature of MMA fights.

The consistent identification of the actual winning arm as one in our dataset suggests a potential learning bias, indicating a need for further model refinement to ensure generalisability. Future research should consider shuffling mechanisms while maintaining pairings and expanding datasets for more nuanced analyses.

Overall, our study offers promising insights into using bandit algorithms for sports analytics, particularly in MMA fight outcome predictions. It opens avenues for further research into more nuanced and robust models to refine predictive accuracy. 

# Source Of The Dataset
The dataset we used for our project was obtained from Kaggle at [this url](https://www.kaggle.com/datasets/danmcinerney/mma-differentials-and-elo).
