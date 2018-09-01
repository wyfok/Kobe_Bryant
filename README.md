# Kobe_Bryant
Kobe Bryant Shot Selection

Which shots did Kobe sink?

(Originally this was a project of master study, using Knime to do analysis and prediction. Follow original steps in Knime and transform to python code)

Data from Kaggle 
https://www.kaggle.com/c/kobe-bryant-shot-selection

Data Description 

This data contains the location and circumstances of every field goal attempted by Kobe Bryant took during his 20-year career. Your task is to predict whether the basket went in (shot_made_flag).

We have removed 5000 of the shot_made_flags (represented as missing values in the csv file). These are the test set shots for which you must submit a prediction. You are provided a sample submission file with the correct shot_ids needed for a valid prediction.

The field names are self explanatory and contain the following attributes:

action_type

combined_shot_type

game_event_id

game_id

lat

loc_x

loc_y

lon

minutes_remaining

period

playoffs

season 

seconds_remaining

shot_distance

shot_made_flag (this is what you are predicting)

shot_type

shot_zone_area

shot_zone_basic

shot_zone_range

team_id

team_name

game_date

matchup

opponent

shot_id

