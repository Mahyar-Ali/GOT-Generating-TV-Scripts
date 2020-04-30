# GOT-Generating-TV-Scripts
Generating scripts for the next season of any TV serial. Can also be used to
generate Poetry,Novels,e.t.c.
-----------------------------------------------------------------------------
Versions:-
1 - This version of the model was created in Tensorflow 1.x
2 - This version of the model was created in Tensorflow 2.x
3 - This version of the model was created in Tensorflow 2.x

-----------------------------------------------------------------------------
Model Architecture for 1 and 2:-
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
Model Architecture for 3:-
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
embedding (Embedding)        multiple                  10674800  
_________________________________________________________________
lstm (LSTM)                  multiple                  1869824   
_________________________________________________________________
lstm_1 (LSTM)                multiple                  1869824   
_________________________________________________________________
lstm_2 (LSTM)                multiple                  1311744   
_________________________________________________________________
dense (Dense)                multiple                  6858559   
=================================================================
Total params: 22,584,751
Trainable params: 22,584,751
Non-trainable params: 0

lstm and lstm_1 makes the bidirectional rnn. Moreover this model was created 
using custom layers.

------------------------------------------------------------------------------
Author : m.mahyar ali 
