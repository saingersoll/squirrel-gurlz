# Seaborn Penguins!
![image](https://github.com/saingersoll/squirrel-gurlz/assets/141206781/9c2086aa-0e63-46ec-973d-e7d65f94e03b)

Is a basic repository with an environment (squirrelgurlz), .gitignore, and a few organizational folders for figures (figs), and jupyternotebooks (nbs).
Contained in the nbs folder are each teammates individual jupyternotebook work. This code was then copied into seabornpenguins.ipynb 

## Seaborn Website + Github
#### Seaborn Website: 

https://seaborn.pydata.org/index.html

Contains a ton of tutorials about the installation process, how to apply different powerful statistical visualization tools, and galleries demonstrating reproducible examples.

#### Seaborn Github:

https://github.com/mwaskom/seaborn

Contains a link to the seaborn website and a detailed README document that details the Python 3.8+ system library dependenices required to use Seaborn. (These included numpy, pandas, and matplotlib). Notes on citaiton, testing, and development are additionally included.  

### Reading in the data

The survey data was originally collected and stored in files available at this link:

https://allisonhorst.github.io/palmerpenguins/

However, Python has adpated the R "palmerpenguins" dataset and created "penguins" for Python. This built in dataset was read in, cleaned, and organized so the variables were assigned as the proper types to produce tidy, quaility visualizations.

### Setting up for particular penguin analyses:

1. Create a notebook for your group members in a new repository for this exercise. Clone the repo to your local machines. 

2. Load the datafile using sns.load_dataset("penguins").

3. Use standard `df.info()`, `df.head()`, `df.describe()` to explore the data. 

4. Clean the data columns and types to match desired categories.

5. Explore the various data visualization tools seaborn has to offer!

6. Work together to combine everyones code a new `.ipynb` in your repo that contains an analysis and visualizations of the data!

![image](https://github.com/saingersoll/squirrel-gurlz/assets/141206781/bd2a607c-e368-4139-a06d-ee8c3a605c2b)

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

https://chat.openai.com/

https://www.gabemednick.com/post/penguin/
