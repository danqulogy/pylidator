# Pylidity

A very good validation library for Python. It features both decorator and non-decorator based validation.

## Installation & Usage

```[bash]
pip install pylidity
```

<!-- ```[bash]
# code.py
from pylidator import contains

contains("Hello world", "world")
``` -->

## Contributing

Fork the repository

```[bash]
git clone https://github.com/danqulogy/pylidity.git
```

Setup virtual environment

```[bash]
cd pylidator

python -m venv venv
```

* Setup a development branch
* Implement validation functions in ```pylidity\pylidity```
* Write test inside inside ```pylidity\test```
* Add demos showing usage in ```pylidity\demos```
* Make a pull request

```[python]
pip install -q build
python -m build
```

Install library dependency for demos

```[python]
dist/
    pylidator-x.y.x.whl
    pylidator-x.y.z.tar.gz

$ pip install dist/pylidity-x.y.z.whl or dist/pylidity-x.y.z.tar.gz 

```

