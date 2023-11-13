# Predicting-Student-Performance-from-Game-Based-Learning

Objective: Predict whether players will answer questions correctly during different game levels.

Introduction

This project focuses on predicting student performance during game-based learning using one of the largest open datasets of game logs. 

The primary goal of this task is to develop a model that can predict student performance in real-time during game-based learning. By doing so, we aim to support the creation of more effective learning experiences for students using educational games.

Dataset Description

The dataset provided includes training data and labels, consisting of game logs from an online educational game. The game logs contain information such as session ID, elapsed time, event name, level, coordinates, and other relevant details. The training set also includes labels indicating whether the user answered each question correctly. 

Files in the Repository

train.csv: The training set containing game logs.

test.csv: The test set for making predictions.

train_labels.csv: Correct values for all 18 questions for each session in the training set.


Columns

session_id - the ID of the session the event took place in

index - the index of the event for the session

elapsed_time - how much time has passed (in milliseconds) between the start of the session and when the event was recorded

event_name - the name of the event type

name - the event name (e.g. identifies whether a notebook_click is is opening or closing the notebook)

level - what level of the game the event occurred in (0 to 22)

page - the page number of the event (only for notebook-related events)

room_coor_x - the coordinates of the click in reference to the in-game room (only for click events)

room_coor_y - the coordinates of the click in reference to the in-game room (only for click events)

screen_coor_x - the coordinates of the click in reference to the player’s screen (only for click events)

screen_coor_y - the coordinates of the click in reference to the player’s screen (only for click events)

hover_duration - how long (in milliseconds) the hover happened for (only for hover events)

text - the text the player sees during this event

room_fqid - the fully qualified ID of the room the event took place in

text_fqid - the fully qualified ID of the

fullscreen - whether the player is in fullscreen mode

hq - whether the game is in high-quality

music - whether the game music is on or off

level_group - which group of levels - and group of questions - this row belongs to (0-4, 5-12, 13-22)
