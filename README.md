# Platzi Data Science Challenge

## We have to read a .csv document and then, we have to solve three questions.

The document´s name is "books.csv".
Questions are the following:

 1. **¿Qué libro obtuvo el mayor número de "reviews"?** 
 2. **¿Qué libro tiene mejor puntuación?**
 3. **¿Qué libro tiene mayor número de "reviews" con mejor puntuación?**

# File
This file contains the .csv document and my Jupyter Notebook.

## Steps to use my Jupyter Notebook

 1. Download this project
 2. Install Anaconda in your computer
 3. [Anaconda for Mac Os](https://docs.anaconda.com/anaconda/install/mac-os/)
 4. [Anaconda for Windows](https://docs.anaconda.com/anaconda/install/windows/)
 5. [Anaconda for Linux](https://docs.anaconda.com/anaconda/install/linux/)
 6. Once, you downloaded and installed Anaconda. Go into the file **goodreads-books-challenge.**
 7. Activate Anaconda as follows:
 8. `conda activate`
 9. `conda env list` to see your virtual environments
 10. `source activate goodreads-challenge` to activate your environment
 11. `jupyter notebook` and you are ready to play with Jupyter Notebook
## How to read a .csv?
### Import libraries

    import pandas as pd
    import numpy as np
    import matplotlib.pyplot as plt
    import searbon as sns
 ### Fore more information about these libraries go to:
 [Pandas documentation](https://pandas.pydata.org/docs/)
 [Numpy documentation](https://numpy.org/doc/)
 [Matplotlib documentation](https://matplotlib.org/3.2.1/contents.html)
 [Seaborn documentation](https://seaborn.pydata.org/)

## Reading and showing the .csv document

    df = pd.read_csv('books.csv', error_bad_lines = False)
    pd
 With this line of code, you can read the .csv
## Showing the columns

    pd.info()
 ## Showing all table
 

    df.describe(include = 'all')
### Start playing with this document. You can consult the documentation aforementioned.

> **Credits:** Kaggle and goodreads.

