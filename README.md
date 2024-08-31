# ml-challenge

This is a practical challenge about **Machine Learning** with Python.

## Tasks
Analyze a database and, based on it:
* Process the data
* Format (if necessary)
* Train the model
* Predict December sale
* Create a histogram of the data
* Create a scatter plot

## Dictionary to be used
```
data_sales = {
    'month': ['January', 'February', 'March', 'April', 'May', 'June', 'July', 'August', 'September', 'October', 'November', 'December'],
    'sales': [2000, 2200, 2300, 2500, 2600, 2700, 2800, 2900, 3000, 3100, 3200, 3300]
}
```

## Dependencies
### pipenv
pipenv is a dependency management tool for Python that allows creating and managing isolated virtual environments for projects, ensuring that dependencies are consistent and easy to manage.

To install pipenv, run:
```
$ pip install --user pipenv
```

Then, to install pipenv on your project directory, run:
```
$ pipenv install
```

And finally, to activate your new virtual environment, run:
```
$ pipenv shell
```

Learn more about [pipenv](https://pipenv.pypa.io/en/latest/index.html).

---

To install any of the following dependencies on your project **virtual environment**, run:
```
$ pipenv install <name>
```
and replace `<name>` with the correct dependecy name.

If you're not using pipenv or any kind of virtual environment, do the same thing, but with:
```
$ pip install <name>
```

### ipykernel
ipykernel is a kernel for Jupyter Notebook that allows running Python code in an interactive environment, providing features such as autocomplete, debugging, and result visualization.

Learn more about [ipykernel](https://pypi.org/project/ipykernel/).

### pandas
pandas is an open-source library for data manipulation and analysis in Python, providing data structures and operations to work with structured data, including data import/export, merge, groupby, pivot, reshape, and more.

Learn more about [pandas](https://pandas.pydata.org/).

### matplotlib
matplotlib is an open-source library for creating graphs and visualizations in Python, allowing the creation of a variety of charts, including lines, bars, scatter, histograms, and more.

Learn more about [matplotlib](https://matplotlib.org/).

### seaborn
Seaborn is a visualization library based on matplotlib that provides a high-level interface for creating attractive and informative statistical graphics.

Learn more about [seaborn](https://seaborn.pydata.org/).

### scipy
SciPy is a scientific computing library for Python that provides algorithms and functions for tasks such as optimization, linear algebra, integration, interpolation, and more.

Learn more about [SciPy](https://scipy.org/).

### scikit-learn
Scikit-learn is a machine learning library for Python that provides algorithms and tools for tasks such as classification, regression, clustering, feature selection, and more.

Learn more about [Scikit-learn](https://scikit-learn.org/stable/).