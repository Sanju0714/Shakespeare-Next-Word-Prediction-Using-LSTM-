# Shakespeare Next Word Prediction Using LSTM

## Project Overview
This project implements a deep learning model to predict the next word in a sequence of Shakespearean text using Long Short-Term Memory (LSTM) networks. Built with Python and TensorFlow/Keras, the model learns sequential patterns from Shakespeare's writings and generates text based on user-provided input.

## Objectives
- Build an LSTM-based next-word prediction model.
- Preprocess text data for deep learning.
- Learn sequential patterns and contextual relationships in text.
- Generate Shakespeare-style text using the trained model.

## Technologies Used
- **Programming Language:** Python
- **Deep Learning Framework:** TensorFlow, Keras
- **Libraries:** NumPy, Pandas
- **Techniques:** NLP, Tokenization, Sequence Generation, LSTM

## Project Workflow
1. **Data Collection:** Load Shakespearean text as the training corpus.
2. **Text Preprocessing:** Clean the text and prepare it for modelling.
3. **Tokenization:** Convert words into numerical tokens.
4. **Sequence Generation:** Create input sequences and corresponding next-word targets.
5. **Model Building:** Develop an LSTM-based neural network to learn patterns in the text.
6. **Model Training:** Train the model using the prepared sequences and an optimization algorithm.
7. **Evaluation:** Monitor training and validation loss and accuracy.
8. **Text Generation:** Generate text using next-word prediction with temperature and top-k sampling.

## Model Architecture
The model uses an LSTM network to learn sequential dependencies in Shakespearean text. The architecture includes:
- An embedding layer to represent tokens numerically.
- An LSTM layer to learn sequential patterns.
- Dropout for regularization.
- A dense output layer to predict the next word.

## Key Features
- Text preprocessing and tokenization.
- Training sequence creation with a fixed context window.
- LSTM-based next-word prediction.
- Model training with Adam optimization.
- Early stopping to help reduce overfitting.
- Text generation using temperature and top-k sampling.

## Results and Evaluation
The model is evaluated using training and validation loss and accuracy. Generated text can also be examined for its resemblance to Shakespearean writing.

The model's predictions depend on the training data and learned vocabulary. It may produce grammatically incorrect or contextually inconsistent text.

## Project Structure
```text
Shakespeare-Next-Word-Prediction/
├── Next_Word_Prediction.ipynb
└── README.md
```

*Update the notebook filename above to match the file uploaded to your repository.*

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
cd YOUR-REPOSITORY
```

Install the required libraries:

```bash
pip install tensorflow numpy pandas matplotlib
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and run the cells in sequence.

## Applications
- Predictive text and typing assistance.
- Basic language modelling.
- Text generation experiments.
- Learning sequence modelling and recurrent neural networks.

## Future Improvements
- Experiment with different LSTM architectures and hyperparameters.
- Improve prediction quality with a larger and more diverse text corpus.
- Compare LSTM with GRU and Transformer-based models.
- Build an interactive interface for next-word prediction.

## Learning Outcomes
- Practical experience with deep learning and NLP.
- Understanding of tokenization and sequence preparation.
- Experience training and evaluating LSTM models.
- Understanding of sampling methods for text generation.

## Author
**Sanjana Gorli**

## License
This project is intended for educational and learning purposes. Add an open-source license if you wish to permit others to reuse the code under specified terms.
