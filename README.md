# FIFA-World-Cup-2022
The idea is to simulate the FIFA 2022 World Cup games with machine learning, in order to predict the competition's winner. The project uses two datasets: [International football results from 1872 to 2022](https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017) and [FIFA World Ranking 1992-2022](https://www.kaggle.com/datasets/cashncarry/fifaworldranking)

We used the same logic that was used in the [Soccer World Cup 2018 Winner
](https://www.kaggle.com/code/agostontorok/soccer-world-cup-2018-winner) notebook, that models the problem as binary classification one. We used this to make it easier to analyze model's results, so the model predicts between win from home team and draw/win from away team.To remove the advantage of away team, we predicted the results changing teams from away and home (because there is not home advantage in World Cup), and used as probabilities the mean of the two predictions. 
