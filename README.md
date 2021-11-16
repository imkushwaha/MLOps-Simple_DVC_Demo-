### create env

- conda create -n wineq python=3.7 -y

### activate env

- conda activate wineq

### created a req file

### install the req

- pip install -r requirements.txt

### download the data from

- https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing

### Open Git Bash

- git init
- dvc init 
- dvc add data_given/winequality.csv
- git add .
- git commit -m "first commit"

### oneliner updates for readme

- git add . && git commit -m "update Readme.md"
- git remote add origin https://github.com/imkushwaha/MLOps-Simple_DVC_Demo-.git
- git branch -M main
- git push origin main

### tox command

- tox

### for rebuilding -
- tox -r 

### pytest command

- pytest -v

### setup commands -

- pip install -e .

### build your own package commands-

- python setup.py sdist bdist_wheel


### DVC Command

- dvc repro (To run pipeline again and again if some change is there)
- dvc metrics show (To show eval metrics)
- dvc metrics dif (Give comparison between previous and current params and metrics)

### After making setup.py
pip install -e .

## To see your package get installed
  174  pip freeze

## To make distribution tar.gz file of your package to share
  175  python setup.py sdist bdist_wheel         (sdist: standarddistribution and bdist: builddistribution)