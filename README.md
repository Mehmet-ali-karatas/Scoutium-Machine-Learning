# Scoutium-Machine-Learning

 # Using Machine Learning to Identify and Evaluate Football Talent
Scouting classification with machine learning involves using machine learning algorithms to classify players based on their potential as a professional athlete. This can be done by training a machine learning model on a dataset of players that includes features such as their physical attributes, performance statistics, and other relevant characteristics. The model can then be used to predict the likelihood that a player will be successful at the professional level based on these features.

# Business problem: Scouting classification

Predicting which class (average, highlighted) players are according to the scores given to the characteristics of the football players watched by the Scouts.

# Dataset story: The data set consists of information from Scoutium, which includes the features and scores of the football players evaluated by the scouts according to the characteristics of the footballers observed in the matches.

# Dataset content:

scoutium_attributes.csv

8 Variables 10,730 Observations 527 KB

task_response_id: The set of a scout's evaluations of all players on a team's roster in a match
match_id: The id of the relevant match
evaluator_id: The id of the evaluator(scout)
player_id: The id of the relevant player
position_id: The id of the position played by the relevant player in that match
Goalkeeper
Stopper
Right-back
Left-back
Defensive midfielder
Central midfielder
Right wing
Left wing
Attacking midfielder
Striker
analysis_id: Set of attribute evaluations of a scout for a player in a match
attribute_id: The id of each attribute that the players were evaluated for
attribute_value: The value (points) a scout gives to a player's attribute
scoutium_potential_labels.csv

task_response_id: The set of a scout's evaluations of all players on a team's roster in a match
match_id: The id of the corresponding match
evaluator_id: The id of the evaluator(scout)
player_id: The id of the respective player
potential_label: A label that indicates a scout's final decision regarding a player in a match. (target variable)
