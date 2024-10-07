# Next Word Prediction Using LSTMs

This project implements a Next Word Prediction model using Long Short-Term Memory (LSTM) networks. The model is trained on the text of **Franz Kafka's "Metamorphosis"** and can predict the next word in a given sentence.

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Training the Model](#training-the-model)
- [Callbacks Used](#callbacks-used)
- [Model Evaluation](#model-evaluation)
- [Results and Visualization](#results-and-visualization)
- [License](#license)

## Project Overview

The objective of this project is to build a model that can predict the next word based on a given sequence of words. This has applications in various fields such as text generation, autocomplete systems, and natural language understanding.

## Technologies Used

- Python 3.x
- TensorFlow and Keras
- NumPy
- Pandas
- NLTK
- Matplotlib
- Pickle

## Training the Model

The model is trained using the following architecture:

- **Embedding Layer**: Converts word indices to dense vectors.
- **LSTM Layers**: Two stacked LSTM layers for capturing long-range dependencies.
- **Dense Layer**: Outputs the predicted probabilities for each word in the vocabulary.

## Callbacks Used

- **ModelCheckpoint**: Saves the model during training.
- **ReduceLROnPlateau**: Reduces learning rate when a metric has stopped improving.
- **TensorBoard**: Visualizes the training process.

## Model Evaluation

The model is evaluated using the training data. Loss and accuracy metrics are monitored during training. The training history is plotted for visualization.

## Results and Visualization

Training loss and accuracy can be visualized using Matplotlib. This provides insights into the model's performance over epochs.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
