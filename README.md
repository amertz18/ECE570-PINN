# ECE570-PINN

## Video Link
The Demo Video associated with this final project is located here: https://youtu.be/q7uN6WrscoY

## Summary
The Jupyter notebook in this repository features a Physics-Informed Neural Network that is intended to solve the heat equation with associated initial and boundary conditions. These solutions are also compared to a standard numerical solution to check the fidelity of the output.

There is also a grid-search implemented that is intended to find the optimal hyperparameters for the Adam optimizer. The grid search spans over 4 key inputs, and performs 2000 epochs of training for each set of parameters, and returns the parameters with the lowest final losses. A model is then fully trained using these hyperparameters, and also compared to the numerical output. The two training losses are also compared.

This procedure is performed for two sets of initial and boundary conditions to compare performance. 

## Code Execution
The provided Jupyter notebook file can be run without any prior setup besides the installation of the requisite packages in the `requirements.txt` file. Most of the packages required are included in the standard Google Colab environment, which is the recommended environment to run the code. No special hardware is required to run the code, although performing the full grid search for both sets of conditions will take about an hour total on the standard Google Colab cpu runtime. No additional datasets are required.
