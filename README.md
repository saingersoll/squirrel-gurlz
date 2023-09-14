# Seaborn Penguins!
Is a basic repository with an environment (squirrelgurlz), .gitignore, and a few organizational folders for data, figures, and jupyternotebooks.
Contained in the nbs folder are each teammates individual jupyternotebook work. This code was then copied into seabornpenguins.ipynb 

## Seaborn Website + Github
#### Seaborn Website: 

https://seaborn.pydata.org/index.html

Contains a ton of tutorials about the installation process, how to apply different powerful statistical visualization tools, and galleries demonstrating reproducible examples.

#### Seaborn Github:

https://github.com/mwaskom/seaborn

Contains a link to the seaborn website and a detailed README document that details the Python 3.8+ system library dependenices required to use Seaborn. (These included numpy, pandas, and matplotlib). Notes on citaiton, testing, and development are additionally included.  

### Reading in the data

The survey data was originally collected and stored in to files available at this link:

https://allisonhorst.github.io/palmerpenguins/

However, Python has adpated the R "palmerpenguins" dataset and created "penguins" for Python. Using the following code, this built in dataset was loaded using the following code:

penguins = sns.load_dataset("penguins")

Once read in, the data was cleaned and organized so the variables were assigned as proper types to produce tidy, quaility visualizations.

### Setting up for particular penguin analyses:

1. Create a notebook for your group members in a new repository for this exercise. Clone the repo to your local machines. 

2. Load the datafile using sns.load_dataset("penguins").

3. Use standard `df.info()`, `df.head()`, `df.describe()` to explore the data. 

4. Clean the data columns and types to match desired categories.

5. Explore the various data visualization tools seaborn has to offer!

6. Work together to combine everyones code a new `.ipynb` in your repo that contains an analysis and visualizations of the data!

### Citations
seaborn scientific pub. citation: @article{Waskom2021,
    doi = {10.21105/joss.03021},
    url = {https://doi.org/10.21105/joss.03021},
    year = {2021},
    publisher = {The Open Journal},
    volume = {6},
    number = {60},
    pages = {3021},
    author = {Michael L. Waskom},
    title = {seaborn: statistical data visualization},
    journal = {Journal of Open Source Software}
 }

 https://seaborn.pydata.org/index.html

https://github.com/mwaskom/seaborn

https://joss.theoj.org/papers/10.21105/joss.03021

https://matplotlib.org/stable/tutorials/colors/colormaps.html

https://chat.openai.com/c/c8f56284-204e-4fdb-aae5-43e3db03e3a0


