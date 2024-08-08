# lstm_chatbot_by_team_tazeen
created an lstm chatbot using pre trained model on corpus movie dataset.
LSTM-Based Chatbot
Overview
This repository hosts an LSTM-based chatbot model developed using TensorFlow. The model is designed to understand and generate responses based on movie dialogues. The LSTM (Long Short-Term Memory) architecture helps in capturing long-range dependencies in text, making it suitable for conversation modeling.

Dataset
The chatbot was trained using a subset of the Cornell Movie-Dialogs Corpus. Due to computational constraints and to streamline the development process, only a small portion of the dataset was utilized. This subset includes dialogues that cover a wide range of conversational topics, providing a robust foundation for the chatbot's language capabilities.

Model
The model architecture comprises of two main components:

Encoder LSTM: Processes the input query and encodes the information into a context vector.
Decoder LSTM: Takes the context vector and generates a response based on the learned dialogue patterns.
The encoder and decoder are built using LSTM layers, which help maintain the context over longer input sequences.


License
This project is open-sourced under the MIT license.



