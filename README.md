# fashion-MNIST

This is our model for the [Fashion MNIST Kaggle competition](https://www.kaggle.com/c/mais202-fall2019/) for the MAIS 202 bootcamp organized by the McGill Articificial Intelligence Society. 
Our final submission to the competition can be found at `submissions/competition_submission.csv`.

## How to run

Our code is written in a Jupyter Notebook. There are two ways to run it:

- You can run the notebook directly in Google Colab by clicking on the following badge: 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/atotschnig/fashion-MNIST/blob/master/model.ipynb).
Make sure that the first cell contains `colab = True`, then run all the cells in the notebook.

- The other option is to clone the repository to your computer, unzip `data.zip`, launch Jupyter Notebook, open `model.ipynb`,
then set `colab = False` in the first cell and run all the cells in the notebook. 
For this option, you need to install the following packages: `numpy`, `pandas`, `sklearn`, and `tensorflow`.

For both options, the code will generate a `submission.csv` file which can be found in the `submissions` folder.
