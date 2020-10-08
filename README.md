# 2020-INFORMS-Demo

This repository has the example code for my presentation from the 2020 INFORMS Annual Conference

To run this code, you will need to install [Anaconda](https://docs.anaconda.com/anaconda/install/).

After installing anaconda open a terminal/command window to this folder and run the following command:

`conda env create -f environment.yml`

To use this environment run the following command in either the terminal or the command window:

`conda activate informs_demo`

Now that you've activated the environment, if you want to use `jupyter lab` to run the code, you will likely need to update how plotly works, so visit the following website and follow the instructions for [using plotly with `jupyter lab`](https://plotly.com/python/getting-started/)

Once that has been set up, then you can run this command in the same terminal window that you've been using:

`jupyter lab`

which will open up jupyter on your machine and should open up a browser window connecting to the Jupyter server.

To run the model, open the notebook `dev/Run Model.ipynb` and to generate new data for the model use the notebook `dev/Generate Data.ipynb`.