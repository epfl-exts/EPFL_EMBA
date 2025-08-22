
### EMBA - hands-on session

&nbsp;
&nbsp;

This repository contains the material for the hands-on session of Day 2 of the EMBA workshop weekend 22-23.August 2025.


**Objective:** Provide a simple use case that allows participants to gain experience with some of the key stages of developing an AI-project and of the data science pipeline. The aim is to do this in an interactive way without requiring coding knowledge or domain knowledge. For that reason, the topic is kept purposefully simple and the emphasis is on the different stages and the decision processes that connect them.  

**Data:**  A large collection of raw email text containing both normal mail and spam.

**Your tasks:** 
1. Prepare the raw data for data analysis
2. Analyse the data to identify patterns and potential problems
3. Use the insights to build a model that classifies the emails into “normal” and “spam”. 


## Hands-On Session

To get started with the hands-on session you have the following 3 options:

### 1. Use Google Colab   

You may need a gmail account or similar to register. Below you need to click on the individual icons to load the relevant files to Colab, each in their own browser tab.

#### --->> START HERE 
Notebook to practice using Colab:
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/epfl-exts/EPFL_EMBA/blob/main/notebooks/colab_practice.ipynb) 

**Main project**

Notebook for data preparation ([source code](notebooks/data_preparation.ipynb)) or
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/epfl-exts/EPFL_EMBA/blob/main/notebooks/data_preparation.ipynb) 

Notebook for exploratory data analysis ([source code](notebooks/EDA.ipynb)) or
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/epfl-exts/EPFL_EMBA/blob/main/notebooks/EDA.ipynb) 

Notebook for building and evaluating different models ([source code](notebooks/supervised_learning.ipynb)) or:
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/epfl-exts/EPFL_EMBA/blob/main/notebooks/supervised_learning.ipynb) 


### 2. Offline view without interactivity

You can always explore the executed notebooks here: 
[![Offline](https://img.shields.io/badge/Offline_View-Open-Blue.svg)](https://github.com/epfl-exts/EPFL_EMBA/blob/main/static)

Pro:
* You can access the material and study the executed results.

Con:
* There is no interactivity.

### (3. Run session locally)

Some people prefer to run the hands-on session locally on their own machine. There are three steps to follow:

1. **Clone or download the content**: Clone this repository from Github to your local machine using the following `git` command in your terminal. Or if you prefer to download the content manually, you can click on the ![](https://placehold.co/60x25/green/white?text=<>+Code) button on the top right of this page and then click on the Download ZIP.
```
git clone https://github.com/epfl-exts/EPFL_EMBA.git
```
<br>

1. **Install Miniconda**: Once the content of the repository is on your machine and is extracted, you can install the relevant Python dependencies with `conda`. But before that you need to install `Miniconda` on your system, if you don't have `conda` installed already. Install Miniconda on your system using this [link](https://docs.conda.io/en/latest/miniconda.html).

2. **Installation with conda**: To install the relevant Python dependencies with conda, use the following code in your terminal. This will create a virtual environment called `environment` and install all the necessary packages in it. You can then launch the jupyter notebooks within this environment and run the code interactively.

```
conda env create -f environment.yml
```

**Note**: you need to be in the same folder as the environment.yml file to run this command.