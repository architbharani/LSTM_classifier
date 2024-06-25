# LSTM_classifier

Here, I have tried to classify AG_NEWS dataset from hugging face. It has 4 labels.
Used Bi-LSTM with padding for classification


To use this model:
Clone this repository
Download LSTM.pth file from 
https://drive.google.com/file/d/12bXK0aNVZK8_f7sYaCrRqbdRllOtZKmE/view?usp=drive_link

Place in same directory as code

Load the model and you can start experimenting



The version for pytoch are as follows:
torch==1.13.0+cu117

torchdata==0.5.0

torchtext==0.14.0



bert.ipynb contains the score of bert fine-tuned on same dataset.  There is a difference of about 3% accuracy on test dataset.
