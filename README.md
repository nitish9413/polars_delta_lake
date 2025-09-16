## Delta Lake Tutorial with Polars

This project is a simple tutorial showing how to use Polars to work with Delta Lake tables in Python.

### Features
- Create and save DataFrames as Delta tables
- Read Delta tables
- Update tables using append, overwrite, ignore, and merge modes

### Requirements
- Python 3.12 or newer
- [uv](https://github.com/astral-sh/uv) (Python package manager)

### Setup Instructions
1. Install [uv](https://github.com/astral-sh/uv) if you don't have it:
	```sh
	pip install uv
	```
2. Install all dependencies:
	```sh
	uv pip install -r requirements.txt
	```
	Or, if using the provided `pyproject.toml`:
	```sh
	uv pip install -r pyproject.toml
	```

### How to Run the Tutorial
1. Open `main.ipynb` in Jupyter or VS Code.
2. Run the cells step by step to see how Delta Lake tables work with Polars.

You can also review the code in `main.py` for a script version.

---
For any issues, check your Python version and make sure all dependencies are installed with uv.
