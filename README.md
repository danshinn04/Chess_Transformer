**Chess Transformer**

Chess Transformer is a machine learning project that utilizes a neural network based on the Transformer architecture to predict chess moves from historical game data. This project not only allows training of a Transformer model on chess games recorded in Portable Game Notation (PGN) but also provides an interactive interface to play chess against the trained model.

**Features**

PGN Reader: Parse and extract chess games from PGN files.

Move Tokenization: Convert chess moves into numerical indices suitable for neural network processing.

Transformer Model: A neural network model designed specifically for sequential data like chess moves.

Training Routine: Optimized training routines with loss tracking and epoch management.

Interactive Play: Play against the trained model in real-time, entering moves and viewing the model's responses.

**Prerequisites**

Python 3.8 or higher

PyTorch

numpy

python-chess (You can pip install these)

