# Univariate-time-series-analysis-of-cryptocurrency-data-with-ARIMA-and-SARIMA-and-hypergrid-search
<p align="justify">In this repository, a time series analysis is conducted using both regular and seasonal ARIMA models. The study is led on the historical price of the XRP coin with Python. A hypergrid search of optimal parameters for both models is also presented.</p>

## Getting Started

<p align="justify">These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.</p>

### Prerequisites

<p align="justify">You need Python 3.x to run the following code.  You can have multiple Python versions (2.x and 3.x) installed on the same system without problems. Python needs to be first installed then SciPy, and finally Seaborn as there are dependencies on packages.</p>

In Ubuntu, Mint and Debian you can install Python 3 like this:

    sudo apt-get install python3 python3-pip

Alongside Python, the SciPy packages are also required. In Ubuntu and Debian, the SciPy ecosystem can be installed by:

    sudo apt-get install python-numpy python-scipy python-matplotlib ipython ipython-notebook python-pandas python-sympy python-nose

For pipelining and parallel tasks, the joblib library can be installed using the <a href="https://pypi.org/project/pip/">pip</a> package manager:

    pip install joblib

Finally, the Jupyter Notebook which can be installed through Python's package manager:

    pip3 install --upgrade pip
    pip3 install jupyter

For other Linux flavors, OS X and Windows, packages are available at:

http://www.python.org/getit/ for Python    
https://www.scipy.org/install.html for the SciPy ecosystem    
https://joblib.readthedocs.io/en/latest/installing.html for the joblib library    
https://jupyter.readthedocs.io/en/latest/install.html for the Jupyter Notebook    


### File descriptions
<ul>
    <li><p align="justify">"<em>Univariate_analysis_classic_methods.ipynb</em>" in which the univariate time series analysis using ARIMA and SARIMA models is carried out. A rolling forward window approach (walk-forward validation) is used on a weekly period to forecast the price of the currency on the next week.</p></li>
    
<li><p align="justify">"<em>Grid_search_models_hyperparameters.ipynb</em>" shows a procedure to find the best hyperparameters for the ARIMA and SARIMA models, for the time series analysis approach used in the file above.</p></li>

</ul>

### Running the files

<p align="justify">Both notebooks can directly be opened on GitHub. Alternatively, you can also use the Jupyter Notebook. This can be done by executing the following command at the Terminal (Mac/Linux) or Command Prompt (Windows):</p>

    jupyter notebook

<p align="justify">This will print some information about the notebook server in your terminal, including the URL of the web application (by default, http://localhost:8888):</p>

    $ jupyter notebook
    [I 11:47:00.830 NotebookApp] Serving notebooks from local directory: C:\Users\EC-PM-3
    [I 11:47:00.830 NotebookApp] The Jupyter Notebook is running at:
    [I 11:47:00.830 NotebookApp] http://localhost:8888/?token=d22181d47f4826316a37161bb8c8469d77a5851bf9ab2c1f
    [I 11:47:00.830 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).

It will then open your default web browser to this URL.

<p align="justify">When the notebook opens in your browser, you will see the Notebook Dashboard, which will show a list of the notebooks, files, and subdirectories in the directory where the notebook server was started. The notebook can then be chosen by navigating in the Notebook Dashboard.</p>

<p align="justify">For more information on how to run a specific jupyter notebook, you can go to the <a href="https://jupyter.readthedocs.io/en/latest/running.html#running">following link</a>.</p>

## Contributing

Please read [CONTRIBUTING.md](https://github.com/DavidCico/Univariate-time-series-analysis-of-cryptocurrency-data-with-ARIMA-and-SARIMA-and-hypergrid-search/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. 

## Authors

* **David Cicoria** - *Initial work* - [DavidCico](https://github.com/DavidCico)

See also the list of [contributors](https://github.com/DavidCico/Univariate-time-series-analysis-of-cryptocurrency-data-with-ARIMA-and-SARIMA-and-hypergrid-search/graphs/contributors) who participated in this project.
