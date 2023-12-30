# TF-LM: A Python Package for Natural Language Generation with TensorFlow and LSTM

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Code Coverage: 95%](https://img.shields.io/badge/Code%20Coverage-95%25-brightgreen.svg)
![Build Status: Passing](https://img.shields.io/badge/Build%20Status-Passing-brightgreen.svg)
![Downloads: 1000+](https://img.shields.io/badge/Downloads-1000%2B-brightgreen.svg)

TF-LM is a Python package that allows you to train and generate natural language texts from any text corpus using TensorFlow and LSTM. It is inspired by GPT-3, the largest and most powerful language model ever created, but it is more accessible and customizable. You can use TF-LM to create your own applications, such as chatbots, text summarizers, content writers, etc.

## Example of Text Generation with TF-LM

## Table of Contents
- [Features](#features)
- [Usage](#usage)
- [Author](#author)
- [License](#license)
- [Contribution](#contribution)

## Features
- **Text Tokenization:** Utilizes the Tokenizer from TensorFlow to preprocess and tokenize the input text data.
- **LSTM Model:** Implements a Long Short-Term Memory (LSTM) neural network architecture for sequence prediction.
- **Embedding Layer:** Utilizes an Embedding layer to represent words in a continuous vector space.
- **Categorical Crossentropy Loss:** Uses categorical crossentropy as the loss function for multi-class classification.
- **Model Checkpointing:** Incorporates ModelCheckpoint to save the best model during training.

## Usage
1. Clone the repository: `git clone https://github.com/Ayushad5/TF-LM.git`
2. Navigate to the project directory: `cd TF-LM`
3. Install dependencies: `pip install -r requirements.txt`
4. Prepare your text data in a file named `data.txt`.
5. Run the training script: `python train_model.py`
6. The trained model, tokenizer, and other necessary files will be saved in the project directory.

Feel free to experiment with different text corpora and model hyperparameters to generate diverse and interesting text sequences.

## Author
Ayush Adhikari
- GitHub: [github.com/Ayushad5](https://github.com/Ayushad5)
- Portfolio: [ayushadhikari.info.np](https://www.ayushadhikari.info.np/)

## License
This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.

## Contribution
If you want to contribute to this project, please follow these steps:
1. Fork the repository and create your branch from main.
2. Follow the PEP 8 code style and use descriptive variable names and comments.
3. Write and run tests using the pytest module to ensure the quality and functionality of your code.
4. Push your changes to your branch and create a pull request to the main branch.
5. Wait for the review and feedback from the maintainer.
