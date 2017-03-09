# Enrupture Analysis Framework


**Enrupture Analysis Framework (EAF) is an interactive tool for exploration, visualization and comparison of Policrack databases, built upon a Jupyter Notebook.**


Copyright &copy; 2012 - 2014, 2017 Dimitar Danov<br>
Copyright &copy; 2012 - 2014, 2017 Prof. Mario Guagliano<br>
Distributed under the terms of MIT License.


## Overview

Enrupture Analysis Framework (EAF) aims to explore the capabilities and limitations of FEM and XFEM fracture analyses of elliptic cracks modeled with different strategies and element types.


## Installation

Copy the `enrupture` directory in the directory of the Policrack database repository you wish to analyze. The directory tree should look like this:

<pre>
parent_directory
├ db
| ├ database_1
| ├ ...
| └ database_n
└ enrupture</pre>


### Requirements

EAF requires [NumPy](http://www.numpy.org/), [SciPy](https://www.scipy.org/), [Jupyer](http://jupyter.org/) and [Matplotlib](http://matplotlib.org/) and comes with [shardlib](https://github.com/fracturica/shardlib). We recommend using [virtualenv](https://virtualenv.pypa.io/en/stable/) to deal with the dependencies.


### Linux Instructions

#### Installation

After creating the directory structure above, open a terminal in the `enrupture` directory and run the commands:

<pre>
$ virtualenv -p python2 venv
$ source venv/bin/activate
$ pip install -r requirements
$ deactivate</pre>

Now EAF is ready to run.


#### Starting EAF

To start the EAF Jupyter Notebook, open a terminal in the `enrupture` directory and run the following commands:

<pre>
$ source venv/bin/activate
$ jupyter notebook</pre>


### Windows and MacOS Instructions

EAF should work on Windows and Mac.


## Documentation

[Documentation](docs) is provided in the `docs` directory.
