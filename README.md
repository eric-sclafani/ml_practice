This repo contains code for my LIN 538 final project, which is an end-to-end machine learning project walkthrough. These note will eventually be transferred over to my planned learning website.


# **Intended audience**

The intended audience is anyone `new to machine learning`.

From my experience, `true understanding` comes from simple explanations and visualizations, as well as personal experimentation. While equations and mathematical theory are very important, they can often deter people new to machine learning.

# **Prerequisite knowledge**

- Python basics

# **Layout**

Each notebook contains a mixture of notes, visualizations, and code samples for walking you through a machine learning project. 

The point of this is to build up experience through experimentation and to learn the python machine learning tools first hand. The Iris dataset is often described as the "Hello, World!" of data-related endeavors since it contains good quantitative and qualitative examples, as well as statistical correlations between features (you'll learn what these terms mean later!).

# **What you will learn**

Following these notebooks, you will learn the essence of data science and machine learning: `how to use data to inform decisions`. To do this, you will be walked through the most popular data-related libraries in python and how to use their APIs. This includes:
- [Pandas](https://pandas.pydata.org/about/index.html) - versatile data processing 
- [Matplotlib](https://matplotlib.org/stable/gallery/index) + [Seaborn](https://seaborn.pydata.org/) - beautiful data visualizations
- [Sklearn](https://scikit-learn.org/stable/) - powerful machine learning implementantions 

# **Getting started**

## Cloning the repo

If you're new to Github, check out [this](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) tutorial for how to clone repositories. If you haven't done so already, you need to set up an SSH key and add it to your Github account. Check out these two links to do so: [creating a new SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent), [adding the SSH key to Github](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account).

## Environment setup
If you don't already, it's a great idea to start using [python environments](https://www.freecodecamp.org/news/python-virtual-environments-explained-with-examples/). Tldr, they are a way to create self contained python dependency installations so you don't have to install things to your local machine and have potential conflicts. I recommend giving that link a read for more information. 

Create an environment by running:
```bash
python3.11 -m venv venv/
source venv/bin/activate
```
Which will create a directory called `venv/` to store all the dependencies and then activate the environment. Now run:
```bash
pip3 install -r requirements.txt
```
to install all the dependencies for the project.


## Juyterlab
For the best experience, these notebooks are best viewed through [JupyterLab](https://jupyter.org/install) because certain cells will be hidden by default. I am unsure if other viewing options (Jupyer notebook, Github preview) preserve this code hiding feature, so I recommend `using JupyterLab`.

After activating your python environment outlined in the previous section, type into the terminal `jupyter-lab` to open it.

# Data

Below is a list of datasets I either use or reference in my notebooks:

- [Car sales](https://www.kaggle.com/datasets/gagandeep16/car-sales?select=Car_sales.csv)
- [Iris](https://archive.ics.uci.edu/ml/datasets/iris)
- [California housing dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices)
