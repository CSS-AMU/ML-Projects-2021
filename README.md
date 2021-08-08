# ML Projects

> All projects in this folder are git submodules.

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