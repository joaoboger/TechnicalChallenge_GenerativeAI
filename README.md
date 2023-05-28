# Generative AI Meander Channel Generator

This repository contains the code and resources for a technical challenge of generative AI focused on generating new images of meander-type geological channels. Given a dataset of 50,000 cutouts of meander channels, the objective is to use 2D neural networks to generate new images by sampling from a random latent vector.

## Repository Structure

The repository is organized as follows:

- `notebooks/`: This folder contains the Jupyter Notebook used for exploring the dataset, preprocessing the data, and evaluating the trained models.
    - `train.ipynb`: This Jupyter Notebook contains the main code for the generative AI challenge. It provides an end-to-end implementation and demonstrates the process of training the neural network models and generating new meander channel images.

- `models/`: This folder is intended to store the trained models. However, it is currently empty due to the large file size of the models.

- `data/`: This folder is intended to store the dataset of 50,000 meander channel cutouts. However, it is currently empty due to the large file size of the dataset. You should place the dataset files in this directory before running the notebook. Dataset available at: 

- `requirements.txt`: This file lists the required libraries and their versions necessary to run the code in the notebook (Python 3.9.13). Before running the notebook, please install the specified versions of the libraries mentioned in this file.

## Setup Instructions

To set up the environment and run the generative AI challenge, follow these steps:

1. Clone the repository:

```shell
git clone https://github.com/joaoboger/TechnicalChallenge_GenerativeAI.git
```

2. Navigate to the repository's directory:

```shell
cd TechnicalChallenge_GenerativeAI
```

3. Create a virtual environment and activate it (optional but recommended):

```shell
python3 -m venv env

# Linux/Mac
source env/bin/activate

# Windows (PowerShell)
.\env\Scripts\Activate.ps1
```

4. Install the required libraries:

```shell
pip install -r requirements.txt
```

5. Place the dataset files in the data/ directory. Ensure that the dataset is in a compatible format and contains 50,000 cutouts of meander-type geological channels.

6. Open the `train.ipynb` notebook in a Jupyter Notebook environment from the `notebooks/` folder and follow the instructions and code comments within the notebook to train the models and generate new meander channel images.

After training the models, you can save them in the `models/` directory for future use.
