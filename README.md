# ML Projects

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

> All projects in this folder are git submodules.

These projects were made during CSS Internship 2021 ( Machine Learning )

Related Work : [View ML-Notebooks Repo](https://github.com/CSS-AMU/ML-Notebooks)

## Clone Repo

* --recurse-submodule

```
$ git clone --recurse-submodules https://github.com/CSS-AMU/ML-Projects-2021 
```

* Otherwise, you can update the submodules after cloning. 

```
$ git clone --recurse-submodules https://github.com/CSS-AMU/ML-Projects-2021

$ git submodule init

$ git submodule update
```

## Setup project locally
> Use a virtual env

* ```$ cd <project-folder>```
* Create a virtualenv: ```$ mkvirtualenv env``` or ```$ python -m venv env```
* Activate env : ```$ workon env``` or ```$ source env/bin/activate```
* Install dependencies : ```$ pip install -r requirements.txt```
* Run project : ```$ uvicorn main:app --reload```