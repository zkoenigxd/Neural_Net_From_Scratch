# Neural Network Mathematical Basis

### Getting Started

This project is designed using notebooks, meaning it is intended to have each code block run sequentially. You may ablready have notebook support on your machince, in which case the core dependancies are only matplotlib, scikit-learn, and numpy. I am using Python 3.11.3, but this project should run with 3.9 and above. Please leave a bug report if you find an unsupported version.

Each code block has a markdown section above it which details what the block does.

The Neural network class has a`thourough definition of the mathematics of the core steps, namely the forward and backward "pass" throught the network. The training loop description notes in broad strokes how these functions are used.

To test some predefined Neural Networks, you can "Run All" without modifying any blocks. The code will create two neural nets and run them sequentially. The first uses a Sigmoid function as it's activation function, the second the reLU function. Each has two hidden layers of (x) "neurons" and runs for 10,000 epochs on the CPU. When complete they will each plot some relevant data from the run (see the code block descriptions for more detail).

### Defining Your Own Network

Once you have run the code, you can define your own Neural Network.