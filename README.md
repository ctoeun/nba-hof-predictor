# NBA Hall of Fame or Ball of Lame

Video Link: [Predicting the 2023 Basketball Hall of Fame Class Using Machine Learning](https://www.youtube.com/watch?v=WJod0UAwrjQ&t=5s) <br>

## Objectives
**What makes an NBA player one of the greatest in league history?**

To answer this question and multiple others, I am going to web scrape (using *python*) the stats of recently retired and current (2021-2022 season) NBA players and train a model to predict their qualifications and probability as a future NBA Hall of Famer (and potential First Ballot inductee).

To determine which players would be considered as a Hall of Famer, I am going to look at all previous Hall of Famers who were inducted as an **NBA player**. The data I have gathered dates back to 1946.

**Questions to consider:**

- What factors make a player likely to be inducted into the Hall of Fame?
- What is the probablity of making it to the Hall of Fame for recently retired and active players?
- Do championships alone determine a players greatness, or can a player be considered an all-time great without a championship?
- What are the most common variables among current hall of famers? Which provide the strongest correlations?
- Can I create a probabilistic classification model to predict the probability a player has to be chosen as a hall of famer based only on current stats?
- Can I create binary classification model to predict which current and recently retired players are going to be first ballot inductees?
- Can both models predict who are the top 2023 Hall of Fame inductees? Can the models go a step further and predict who are first ballots? <br>

**Benefits (Learned and accomplished):**

- Used python libraries, including dataframes, beautifulsoup, mathplotlib, etc, to gather and express results scraped from [Basketball-Reference.com](https://www.basketball-reference.com/).
- Gained better knowledge on python web scraping and determining which methods are best used in certain scenarios.
- Cleaned extracted data and formatted into desired dataframes and csv files.
- Explored and visualized the differences between players based on Hall of Fame status.
- Created two models with algorithms to predict a players chance of being a Hall of Famer and potential First Ballot, based on current Hall of Famers.
- Determined the most accurate models for binary and probabablistic classification. <br>

## Project Summary
**Overview:**

- Probabilistic and binary classification models have been trained on retired Hall of Fame eligible players to determine recently retired and current NBA players chances of becoming a Hall of Famer (possibly First Ballot) through stats, awards, and accomplishments. If a player is currently active, I assumed they will retired at the end of the season.

**Technical Contributions:**

- I used bar and scatter plots, along with distribution histograms to visualize the data. To carry out the predictions, Logistic Regression (Probabilistic Classification) and Random Forest Classifier (Binary Classification) models were used and trained on predictive variables with strongest correlations between Inducted as Player and First Ballot status.

**Main Results:**

- The two players predicted as First Ballot Hall of Famers in 2023 are **Dirk Nowitzki and Dwyane Wade**. **LeBron James, Kevin Durant, and Chris Paul** are the top 3 active players with the highest probability of being inducted into the Hall of Fame in the future (**All predicted First Ballots**).

**How are the results evaluated?**

- Although there were some imperfections, both models were able to correctly predict probabilities and first ballot status for current Hall of Famers. Active players who are considered as an all-time great and are included on the 75th Anniversary Team are the top players with highest probabilities.

**What are the future directions?**

- Include more advanced stats to showcase a players true potential and contributions
- Factor in total win-loss ratio
- Comparisons between previous and recent Hall of Famers (analyze evolution of the game)
- Predict Hall of Fame induction year when given a player's retired year
