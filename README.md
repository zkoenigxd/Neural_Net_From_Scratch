# Neural Network Mathematical Basis

### Background

This code was originally authored by myself as the experimental component of a paper I wrote in conjunction with Colin Crippen. The paper explored the mathmatical basis of Nueral Networks. In short, it highlights that NN prediction results are generated from presupposing that there exists some function that maps a data set to some category space, and attempts to approximate said function by generating a function, using the function on the data, comparing the difference between the predicted and expected outcomes, then modifying the function's terms accordingly to improve its predictive ability. Given this purpose, the project uses only the numpy library for the NN calculations, to make the matrix operations explicit and easier to follow.

The code has been modified to support a wider variety of experimental NN setups.

### Getting Started

This project is designed using jupyter notebooks, meaning it is intended to have each code block run sequentially. If you already have notebook support on your machince, the core dependancies are only matplotlib, scikit-learn, and numpy. I am using Python 3.11.3, but this project should run with 3.9 and above. Please leave a bug report if you find an unsupported version.

Each code block has a markdown section above it which details what the block does.

The Neural network class has a`thourough definition of the mathematics of the core steps, namely the forward and backward "pass" throught the network. The training loop description notes in broad strokes how these functions are used.

To test some predefined Neural Networks, you can "Run All" without modifying any blocks.

### Defining Your Own Network

Once you have run the code, you can define your own Neural Network by creating a new code block and following the example formats provided.