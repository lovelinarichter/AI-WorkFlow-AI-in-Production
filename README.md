# AI-WorkFlow-AI-in-Production

## Table of contents

- [Installation](#installation)
- [Review Criteria](#review-criteria)
- [Solution Guidance-License](#solution-guidance-license)

## Installation

The code is implemented using Python and the following libraries.
- pandas
- numpy
- sklearn
- Flask

To install go to the following links for download and instruction details. <br>
https://www.python.org/downloads/ <br>
https://numpy.org/install/ <br>
https://scikit-learn.org/stable/install.html <br>

To Run the codes:
1. Copy the data to \data folder
2. Run the following commands in the project's root directory
- python app.py
- python model.py
- pthon run-tests.py

## Review Criteria
- Are there unit tests for the API?: **unittests/ApiTests.py**
- Are there unit tests for the model?: **unittests/ModelTests.py**
- Are there unit tests for the logging?: **unittests/LoggerTests.py**
- Can all of the unit tests be run with a single script and do all of the unit tests pass?: **/run-tests.py**
- Is there a mechanism to monitor performance?: **logger.py**
- Was there an attempt to isolate the read/write unit tests From production models and logs? **sl as prefix**
- Does the API work as expected?: **app.py**
- Does the data ingestion exists as a function or script to facilitate automation?: **cslib.py**
- Where multiple models compared?: **model_performance.py**
- Did the EDA investigation use visualizations?: **notebook/Part1.ipynb**
- Is everything containerized within a working Docker image?: **Dockerfile**

## Solution Guidance-License
Two code files provided through the course:
* **cslib.py**: A collection of functions that will transform the data set into features you can use to train a model.
* **model.py**:  Provides you with a working solution
