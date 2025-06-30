# AuSRoS Control Lectorial 3
In this lectorial, we will be going through some examples that make use of several open-source robotics packages.
For convenience, we will be using [Anaconda]() to manage and collect the necessary packages and install them in a container, so that we can run them in an environment.

# Installing Anaconda
Anaconda allows us to create an environment where all our necessary packages are located and accessible. If you do not have anaconda on your machine, you can install it by following the information [here](https://docs.anaconda.com/anaconda/install/).

# Setting Up the Environment
After installing anaconda, move to the directory containing the ``env.yaml`` file and run the following command

```
conda env create -f env.yaml
```

This will create a new environment called ``ausros_control`` that contains all the necessary Python packages for this lectorial, such as the rigid-body dynamics library Pinoccchio, automatic differentiation library Casadi and model visualiser Meshcat.

Within a terminal, to switch to the newly created environment, run the command

```
conda activate ausros_control
```

# Starting Jupyter Notebook
If you would like to run our Jupyter notebook in a lab instance, you can start it by running
```
jupyter-lab
```
