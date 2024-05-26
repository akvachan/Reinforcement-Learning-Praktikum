# Reinforcement-Learning-Praktikum
Reinforcement Learning Praktikum 2024 


GENERAL SETUP STEPS FOR PYTHON ENVIRONMENT:
============================================

1) Install PyENV: https://github.com/pyenv/pyenv

2) Download / Make sure that PyEnv has instance of Python 3.10.1 environment
  => pyenv update
  => pyenv install 3.10.1

3) Create local directory for the lecture exercise and CD into it, e.g. c:\exercise\1
  => cd c:\exercise\1
  
4) Copy lecture files (requirements.txt and Python-Notebook) into it

5) Create instance of Python 3.10.1 
  5.1) creates .python-version file containing the desired version number
    => pyenv local 3.10.1
  5.2) create the virtual Python environment
    => python -m venv .venv

6) Activate created virtual env  
  => (on Windows) .venv\scripts\activate
  => (on Linux)   source .venv/bin/activate

7) Install required packages from requirements.txt into .venv
  => pip install -r requirements.txt

=====================================================================================

WORK WITH THE PYTHON NOTEBOOK: 
==============================

From now on you can use the created Python environment for working on the exercise ipynb. 

1) Make sure Python environment is activated 
  => (on Windows) .venv\scripts\activate
  => (on Linux)   source .venv/bin/activate

2) Start Python-Notebook
  => jupyter notebook

