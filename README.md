# Sign-Talk
A project on sign language translation done as a part of Hack-A-Week 2.0

## Overview
The project aims to create an language translation model which recognises the alphabet in sign language and predicts the letter by comparing with the trained data. A series of assumptions are made out of which the one with the highest confidence rate is displayed. 

The model is trained using sklearn and tensorflow libraries and then plotted using matplotlib. The hand recognition is carried out using mediapipe in openCV. The output is predicted in terms of confidence in the terminal.

## Libraries used
Matplotlib, seaborn, sklearn, numpy, pandas, tensorflow, mediapipe(python version 3.10)

## How it works

1. Fork and clone repo to your device

2. Save compressed csv files in the same folder

3. Run train_model.py to train the model

4. Run signtalk.py(Press Space bar to detect letter, and X to terminate program)

