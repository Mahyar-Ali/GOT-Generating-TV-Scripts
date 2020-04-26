# GOT-Generating-TV-Scripts
Generating scripts for the next season of any TV serial. Can also be used to
generate Poetry,Novels,e.t.c.
-----------------------------------------------------------------------------
Versions:-
1 - This version of the model was created in Tensorflow 1.x
2 - This version of the model was created in Tensorflow 2.x
-----------------------------------------------------------------------------
Model Architecture:-
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
embedding_7 (Embedding)      (128, None, 400)          10674800  
_________________________________________________________________
lstm_14 (LSTM)               (128, None, 512)          1869824   
_________________________________________________________________
lstm_15 (LSTM)               (128, None, 256)          787456    
_________________________________________________________________
dense_7 (Dense)              (128, None, 26687)        6858559   
=================================================================
Total params: 20,190,639
Trainable params: 20,190,639
Non-trainable params: 0

-----------------------------------------------------------------------------
