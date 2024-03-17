# SUMMARY Game_analysis_1

You can access detailed analysis and all code [here](https://colab.research.google.com/github/Rogerio-mack/game_analysis/blob/main/Game_analysis_1.ipynb)

# Study hypotheses

Three research questions were investigated in this study:

1. whether the interaction device influences the player's experience;
2. whether player performance impacts the gaming experience;
3. whether there is a difference between gender related to preference for the interaction device.

# Scoring guidelines GEQ Post-game Module

The post-game Module consists of four components; the items for each are listed below. Component **scores are computed as the average value of its items**.

- Positive Experience: Items 1, 5, 7, 8, 12, 16.
- Negative Experience: Items 2, 4, 6, 11, 14, 15.
- Tiredness: Items 10, 13.
- Returning to Reality: Items 3, 9, and 17

# 1. Whether the interaction device influences the player's experience

**`ANOVA one-way method`** applied.

**Results**

* Device type does not influence the Positive_Experience. f-stat = $1.593921$ p-value = $0.206690$
* **Device type influences the Negative_Experience**. f-stat = $15.448490$ p-value = $0.000001$
* Device type does not influence the Tiredness. f-stat = $1.261331$ p-value = $0.286387$
* **Device type influences the Returning_to_Reality**. f-stat = $6.505133$ p-value = $0.001974$

# 2. Whether player performance impacts the gaming experience

**`Pearson method`** should be applied.

**For now, inconclusive**. **Issue:**  It is necessary to associate each occurrence of the Game Experience Questionnaire with the player's score. There are, however, more scores than responses to the questionnaire.

# 3. Whether there is a difference between gender related to preference for the interaction device

**`Chi-square method`** applied

**Issue** (*warning*): There a more participant profiles (49) than preference answers (34). There is also a preference answer with no profile. Thus, this results in only 33 cases.

**Results**

* There is no evidence that gender influences device preference. Chi-square: $0.462947$ p-value = $0.793364$
* There is no evidence that gender influences opinions about how challenging the gaming experience is. Chi-square: $0.812808$ p-value = $0.666041$
