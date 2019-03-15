# Bike Sharing Predictions With Neural Networks

This project was developed as a part of Udacity's Deep Learning Nanodegree. In this project, i have created neural networks from scratch by using numpy only.

## Getting Started

Just run the ipynb notebook. Tune the hyper parameters for better accuracy.

### Prerequisites

* Python 3.
* Numpy 
* Pandas
* MatPlotLib. 

### Output

<img src="/assets/output.jpg" width= 500 px/>

### Architecture

<img src="/assets/neural_network.png" width=500 px/>

### Instructions

 1. Download the project materials from my GitHub repository. You can download the repository with
  ```
  git clone https://github.com/vickipedia6/Bike-Sharing-Deep-Learning.git
  ```
 2. Download anaconda or miniconda based on the instructions in the [Anaconda documentation](https://docs.anaconda.com).
 
 3. Create a new conda environment:
  ```
  conda create --name deep-learning python=3
  ```
 4. Enter your new environment:
  * Mac/Linux: >> ``` source activate deep-learning ```
  * Windows: >>  ```activate deep-learning ```
 5. Ensure you have numpy, matplotlib, pandas, and jupyter notebook installed by doing the following:
  ```
  conda install numpy matplotlib pandas jupyter notebook
  ```
 6. Run the following to open up the notebook server:
  ```
  jupyter notebook Your_first_neural_network.ipynb
  ```
 7. Execute all the cells in the code
 
### Project results

This project met the following specifications:
* All the code in the notebook runs in Python 3 without failing, and all unit tests pass.
* The sigmoid activation function is implemented correctly
* The forward pass is correctly implemented for the network's training.
* The run method correctly produces the desired regression output for the neural network.
* The network correctly implements the backward pass for each batch, correctly updating the weight change.
* Updates to both the input-to-hidden and hidden-to-output weights are implemented correctly.
* The number of epochs is chosen such the network is trained well enough to accurately make predictions but is not overfitting to the training data.
* The number of hidden units is chosen such that the network is able to accurately predict the number of bike riders, is able to generalize, and is not overfitting.
* The learning rate is chosen such that the network successfully converges, but is still time efficient.
* The number of output nodes is properly selected to solve the desired problem.
* The training loss is below 0.09 and the validation loss is below 0.18.

## Losses

Training loss: 0.058 ... Validation loss: 0.142

### Tests

Unit tests for testing the neural network

## Built With

* Python 3

## License

This project is licensed under the MIT License - see the [License.md](License.md) file for details

## Acknowledgments

* The data comes from the UCI Machine Learning Database.
