# SMS-Spam-Detection
# SMS Spam Detection using Recurrent Neural Network (RNN)

This project utilizes a Recurrent Neural Network (RNN) to detect spam in SMS messages. The dataset is sourced from the 'SMSSpamCollection.txt' file and includes labeled messages as spam or ham (non-spam).

### Dataset

- The dataset is loaded and inspected using pandas.
- Messages are labeled as spam (1) or ham (0).

### Train-Test Split

- The dataset is split into training and testing sets.

### Tokenization and Padding

- Messages are tokenized and padded for input to the RNN model.

### Model Architecture

- RNN model with Embedding, SimpleRNN, and Dense layers.
- Binary classification using the sigmoid activation function.

### Training

- The model is compiled and trained for 50 epochs with early stopping.

### Evaluation

- Model performance is evaluated using classification report and confusion matrix.
- Accuracy and other metrics are displayed.

### Results

- A confusion matrix is plotted and saved.

### Usage

1. Install required libraries: `pip install pandas matplotlib seaborn tensorflow`.
2. Run the script: `python spam_detection_rnn.py`.
