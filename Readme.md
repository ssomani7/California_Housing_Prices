# California Housing Prices: End-to-End Machine Learning Project

This project is based on the Stalib repository. This dataset is based on data from the 1990 California census. The machine learning models built in this project helps in determining whether to invest or not in the given area. The final prediction is made for a district's median housing price.</br>

This data has metrics such as the population, median income, median housing price, and so on for each block group in California. Block groups are the smallest geographical unit for which the US Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people).

## Performance Measure

System uses multiple features to make a prediction (it will use the district’s population, the median income, etc.). This classifies for a **Multivariate Regression Problem**. Hence the performance measure choosen for this is **_RMSE_** (Root Mean Square Error).

## Dependencies


[Python3](https://www.python.org/downloads/)
[Anaconda Distribution (Jupyter Notebook)](https://conda.io/docs/user-guide/install/index.html)

The libraries required are mentioned in requirements.txt

## Installing

* Once you have installed Python3 and Anaconda Distribution on your machine, you can either run the notebook directly from the root directory, which contains all the required libraries.

* Or you can create a **Virtual Environment** and install only the required libraries for the project (recommended) so that when there is a upgrade in the dependancy library/package your project doesn't break down unexpectedly.

**Step 1**: Install virtual environment at your root (global) directory
```
$ pip install virtualenv
```
**Step 2**: Change directory to the location where you want to execute/store your project. You can change directory with command 'cd destination'

**Step 3**: Once you are in the directory you need for your project, you need to create a virtual environment inside it.
```
$ virtualenv name_of_the_environment_you_want_to_give
```
This will install setup tools and pip for you, which enables you to install packages at later stage.

**Step 4**: Activate the virtual environment.
```
$ source name_of_the_environment_you_gave/bin/activate
```
Now you're inside the virtual environment.

**Step 5**: Install packages you want.
```
$ pip install package_name
```

**Step 6**: Once you are done installing and using the virtual environment & you want to return to the global (root) environment just type
```
$ deactivate
```

### Acknowledgments

* O'Reilly Hands on Machine Learning with Scikit Learn and Tensorflow. 
* The original dataset appeared in R. Kelley Pace and Ronald Barry, “Sparse Spatial Autoregressions,” Statistics & Probability Letters 33, no. 3 (1997): 291–297.

