![Project Logo](![70f1804c7aee4bd3ee73ac81aff1ed18c19b9527](https://github.com/OscarRCH/Project_NMR_BA3/assets/160874520/a62fd4f8-8b35-46d8-8642-faf7375fdc1c))


[![Code style: ruff-format](https://img.shields.io/badge/code%20style-ruff_format-6340ac.svg)](https://github.com/astral-sh/ruff)
![Coverage Status](https://raw.githubusercontent.com/OscarRCH/NMRoss/main/coverage-badge.svg)

<h1 align="center">
NMRoss
</h1>

<br>


Hydrogen NMR spectrum predictor

## 🔥 Usage

> TODO show in a very small amount of space the **MOST** useful thing your package can do.
> Make it as short as possible! You have an entire set of docs for later.

## 👩‍💻 Installation

Create a new environment, you may also give the environment a different name. 

```
conda create -n nmross python=3.10 
```

```
conda activate nmross
```

If you need jupyter lab, install it 

```
(conda_env) $ pip install jupyterlab
```


## 🛠️ Development installation

To install, run

```
(conda_env) $ pip install -e ".[test,doc]"
```

To run style checks:

```
(conda_env) $ pip install pre-commit
(conda_env) $ pre-commit run -a
```

### Run style checks, coverage, and tests

```
(conda_env) $ pip install tox
(conda_env) $ tox
```

### Generate coverage badge

Works after running `tox`

```
(conda_env) $ pip install "genbadge[coverage]"
(conda_env) $ genbadge coverage -i coverage.xml
```


