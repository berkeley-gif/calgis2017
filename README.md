# Cal-Adapt API Workshop at CalGIS|LocationCon 2017

This repository contains materials for the workshop.


## Links
- [Cal-Adapt API Documentation](https://berkeley-gif.github.io/caladapt-docs/index.html)
- [Cal-Adapt website](beta.cal-adapt.org)

## No Setup - Just for this workshop
- Create a single-instace use Jupyter Notebook server using our JupyterHub setup.
	- In your browser, go to [Cal-Adapt website](beta.cal-adapt.org). Login with any username and password.
	- Upload the notebooks (.ipynb files) in this repo to the Jupyter Notebook server you just started.
	- This JupyterHub setup will be accessible till May 26th, 2017.

## Setup - Beginner
- If you are new to Jupyter, we highly reccomend installing the Python 3.x version of [Anaconda](http://jupyter.org/install.html). Anaconda Distribution is a free, easy-to-install package manager, environment manager and Python distribution with a collection of over 720 open source packages with free community support. Installation packages are available for [Windows, Linux and MacOS](https://www.continuum.io/downloads).

- Download this repo. Clicking on the green clone or download button downloads this repo as a zip file. Extract the folder to a location on your computer.

- Use Anaconda Navigator, a graphical user interface to launch Jupyter-Notebook app. Navigate to the folder and open the `index.ipynb` notebook.
`

## Setup - Advanced
- Clone the repo

	```python
	git clone https://github.com/berkeley-gif/calgis2017
	```
- Change directory

	```python
	cd calgis2017
	```
- Create a python3 virtualenv. How you do this will depend on Python3 setup on your computer. Below is an example of how I set it up.

	```python
	python3 -m venv env
	```

- Activate your virtual env

	```python
	source env/bin/activate
	```

- Install libraries. The Jupyter package is not listed in our `requirements.txt` file and is installed separately here because of some JupyterHub configuration issues.

	```python
	pip install -r requirements.txt
	pip install jupyter
	```

- Launch the Jupyter Notebook app

	```python
	jupyter-notebook
	```

- Open the `index.ipynb` notebook.
