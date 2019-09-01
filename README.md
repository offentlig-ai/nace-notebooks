# Prediction of nace-codes based on the description of enterprise's purpose as expressed in natural language

## Requirements

You should work in a virtual environment. To do that, install [virtualenv](https://docs.python.org/3/library/venv.html)

```
sudo apt-get install virtualenv
```

To work with the large datasets and git, you need to install Git Large File Support:

```
sudo apt-get install git-lfs
git lfs pull
```

## Create and use a virtual environment

```
cd <your environment folder>
virtualenv my_env
. my_env/bin/activate
```

## Install software

```
cd <into project folder>
pip3 install -r requirements.txt
```

## Usage

To work interactively with the notebooks

```
cd notebooks
jupyter notebook
```
