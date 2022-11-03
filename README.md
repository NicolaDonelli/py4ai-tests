py4ai core
====

[![PyPI](https://img.shields.io/pypi/v/py4ai-tests.svg)](https://pypi.python.org/pypi/py4ai-tests)
[![Python version](https://img.shields.io/badge/python-3.7+-blue.svg)](https://pypi.python.org/pypi/py4ai-tests)
[![Documentation](https://img.shields.io/badge/docs-latest-brightgreen.svg)](https://py4ai.github.io/py4ai-tests/)
![Python package](https://github.com/NicolaDonelli/py4ai-tests/workflows/CI%20-%20Build%20and%20Test/badge.svg)

--------------------------------------------------------------------------------


A Python library of unit-test utilities for py4ai framework. 


## What is it ?
**py4ai-tests** is the Python package of the py4ai framework that provides utilities for unit testing.

## Features
The main feature of this package is an extended TestCase class to natively assert equality of lists, dictionaries, 
pd.DataFrames, pd.Series and np.arrays. 

## Installation
From pypi server
```
pip install py4ai-tests
```

From source
```
git clone https://github.com/NicolaDonelli/py4ai-tests
cd py4ai-tests
make install
```

## Tests 
```
make tests
```

## Checks 
To run predefined checks (unit-tests, linting checks, formatting checks and static typing checks):
```
make checks
```

## How to contribute ? 

We are very much willing to welcome any kind of contribution whether it is bug report, bug fixes, contributions to the 
existing codebase or improving the documentation. 

### Where to start ? 
Please look at the [Github issues tab](https://github.com/NicolaDonelli/py4ai-tests/issues) to start working on open 
issues 

### Contributing to py4ai-tests 
Please make sure the general guidelines for contributing to the code base are respected
1. [Fork](https://docs.github.com/en/get-started/quickstart/contributing-to-projects) the py4ai-tests repository. 
2. Create/choose an issue to work on in the [Github issues page](https://github.com/NicolaDonelli/py4ai-tests/issues). 
3. [Create a new branch](https://docs.github.com/en/get-started/quickstart/github-flow) to work on the issue. 
4. Commit your changes and run the tests to make sure the changes do not break any test. 
5. Open a Pull Request on Github referencing the issue.
6. Once the PR is approved, the maintainers will merge it on the main branch.