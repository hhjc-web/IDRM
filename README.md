# IDRM
This is the code for iterative deep Ritz method (IDRM)

Environment requirements:

1.Set up Anaconda at: https://www.anaconda.com/

2.Build Python environment

3.Creating a Virtual Environment by running conda create -n env_name python=3.10 (python version)

4.Download environment.txt and running pip install -r environment.txt to the environment you create.

5.Activate the environment by running conda activate env_name

Then you may run the python file in the zip file.

example_optimal_source.py is the main function. example_optimal_source.yml is the main parameter file.

The files in Nonsys are some functions and classes.

Nonsys/Nonsys/model: problem model

Nonsys/Nonsys/loss: loss function

Nonsys/Nonsys/problem_nonlineardiffusion: solution and pde

Nonsys/utils/nn: neural network

Nonsys/utils/data: sampling data
Nonsys/utils/optimize: optimization method
