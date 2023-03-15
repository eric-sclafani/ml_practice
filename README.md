This repo contains code for my LIN 538 final project, which is an end-to-end machine learning project walkthrough. 

# **Intended audience**

The intended audience is anyone `completely new to machine learning` with little to no math background (it is assumed that you have basic python knowledge, however)

I do include mathematical formulas, but they are never the focus. They are there so you can get used to them. They are also accompanied with hefty explanations and code samples that breakdown what the equations do. 

From my experience, `true understanding` comes from simple explanations and visualizations, as well as personal experimentation. While equations and mathematical theory are very important, they can often deter people new to machine learning.

# **Layout**

Each notebook contains a mixture of notes, visualizations, and code samples for walking you through a machine learning project. Additionally, they contain exercises to test your knowledge. Answers are provided to check your work. 

Alongside my code samples, starting in `02_Data_Selection.ipynb`, you will have the option of writing your own code to use a `dataset of your choice`, or the one I recommend you to use. 

If you'd like, you *can* use the dataset I use for the code samples, but I *`highly`* encourage you to explore things on your own. The point of this is to build up experience through experimentation and to learn the python machine learning tools first hand.

# **What you will learn**

Following these notebooks, you will learn the essence of data science and machine learning: `how to use data to inform decisions`. To do this, you will be walked through the most popular data-related libraries in python and how to use their APIs. This includes:
- [Pandas](https://pandas.pydata.org/about/index.html) - versatile data processing 
- [NumPy](https://numpy.org/) - efficient implementation of arrays and matrices
- [Matplotlib](https://matplotlib.org/stable/gallery/index) + [Seaborn](https://seaborn.pydata.org/) - beautiful data visualizations
- [Sklearn](https://scikit-learn.org/stable/) - powerful machine learning implementantions 

# **Getting started**

## Cloning the repo

If you're new to Github, check out [this](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) tutorial for how to clone repositories. If you haven't done so already, you need to set up an SSH key and add it to your Github account. Check out these two links to do so: [creating a new SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent), [adding the SSH key to Github](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account).

## Environment setup
If you don't already, it's a great idea to start using [python environments](https://www.freecodecamp.org/news/python-virtual-environments-explained-with-examples/). Tldr, they are a way to create self contained python dependency installations so you don't have to install things to your local machine and have potential conflicts. I recommend giving that link a read for more information. 

I recommend also installing [conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) and using [conda environments](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) since they're really simple to setup. Later down the line in your studies/career, if you find yourself writing lots of python scripts with many dependencies, I recommend switching to [Poetry](https://python-poetry.org/docs/) because conda is great for learning, but is also uses a separate package manager (`conda install` instead of `pip3 install`), which can get convoluted and annoying (imo). 

I will be using `conda` for this project, so I recommend you do the same. When you're ready to get started, run `conda install --file requirements.txt` to install the necessary dependencies.

## Juyterlab
For the best experince, these notebooks are best viewed through 

# Data

Below is a list of datasets I either uses, referenced, or planned to use and didn't make the final cut.

- [Car sales](https://www.kaggle.com/datasets/gagandeep16/car-sales?select=Car_sales.csv)
