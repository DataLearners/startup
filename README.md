# startup

Functions and classes for loading csv files into the workspace. The module cleans the files as it loads them.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install bst.

```
cmd> cd 'C:\...\dist'
cmd> python -m pip install startup-1.0.0-py3-none-any.whl
```



## Usage

```python
import startup
files = startup.Load(dirpath)
files
```
