# Prediction of nace-codes based on the description of enterprise's purpose as expressed in natural language

## Requirements

You should work in a virtual environment. To do that, install [venv](https://docs.python.org/3/library/venv.html)

```
sudo apt-get install python3-venv
```

To work with the large datasets and git, you need to install Git Large File Support:

```
sudo apt-get install git-lfs
git lfs pull
```

## Create and use a virtual environment

```
cd <your environment folder>
python3 -m venv .venv
source .venv/bin/activate
```

## Install software

```
pip3 install wheel
pip3 install --no-cache-dir -r requirements.txt
```

## Usage

To work interactively with the notebooks, you need to install a ipykernel inside your virtual environment

```
python -m ipykernel install --user --name .venv --display-name "Python (.venv)"
cd notebooks
jupyter notebook
```

You then need to choose you the kernel you installed.

## Deactivate your virtualenv

```
deactivate
```
