# Pylidator

A very good validation library for Python. It features both decorator and non-decorator based validation.

## Installation & Usage

```[bash]
pip install pylidator
```

<!-- ```[bash]
# code.py
from pylidator import contains

contains("Hello world", "world")
``` -->

## Contributing

Fork the repository

```[bash]
git clone https://github.com/danqulogy/pylidator.git
```

Setup virtual environment

```[bash]
cd pylidator

python -m venv venv
```

* Setup a development branch
* Implement validation functions in ```pylidator\pylidator```
* Write test inside inside ```pylidator\test```
* Add demos showing usage in ```pylidator\demos```
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

$ pip install dist/pylidator-0.0.1.whl or dist/pylidator-0.0.1.tar.gz 

```

