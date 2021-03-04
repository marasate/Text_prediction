# Text_prediction

Model uses LSTM. Note:

The file uses shakespear play as the input the input can be changed in line 4.
The current predictor predicts 13th word that can also be changed predict_len= 12+1 (please change the *12 to the deired input). 
Line 13 has a break statement as conda goes out of memory hence to read complete text remove that loop and break statement. 
Also when training model set epochs to 500 that will give better results as Acuraccy increases. 
Input is a string for testing in Generate function, please note that needs to be pre processed.
