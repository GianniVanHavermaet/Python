# Virtual Environment Guide

## Create a working directory
```
mkdir project
cd project
```

## Creating a virtual environment on Python 3 
Python 3 comes with the virtualenv module built in since version 3.3.
```
python3 -m venv env
```


## Activate the environment

You will need to use the 'source' command to load it into your shell environment.
```
source env/bin/activate
```

## Start working in the virtual environment
Make sure you have an updated version of pip installed in your environment.
```
pip install --upgrade pip
pip install packagename
pip uninstall packagename
```

## Leaving the virtual environment
```
(env)$ deactivate 
```