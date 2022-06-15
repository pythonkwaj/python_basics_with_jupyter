# Python Basics with a jupyter notebook.

This is a juypter notebook to introduce the concept of notebooks an provide some basics on [python](https://www.python.org/about/gettingstarted/)

** You can run this online, by clicking on the below link, nothing to install or follow, try it here:**
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/techsolx/python_basics_with_jupyter/HEAD?labpath=Jupyter_Practice.ipynb)

### Prerequisites

* Nothing really, just click on the link above.

If you prefer to run it locally:
* python3 (Python is an open source general progarmming language https://wiki.python.org/moin/)
* git (Git is a version control system https://en.wikipedia.org/wiki/Git)
* A default web browser, any one will do

## Getting Started

1. Follow the guidelines here to satisfy the getting started prerequisites.
	* https://wiki.python.org/moin/BeginnersGuide/Download

### Clone this repository

2. If you know git you can clone the repository by using this command.

```
git clone https://github.com/PythonTriCities/jupyter_intro.git
```
* If you had trouble with the git install or just want to download the files as a zip, click this link [starthere](https://github.com/techsolx/python_basics_with_jupyter/archive/main.zip)

### The next 2 steps are optional but recommended

3. Create the virtual environment if it doesn\'t exist:
  * [What/'s a virtual environment?](https://docs.python.org/3/library/venv.html)

* On Linux/Mac it is: python3 -m venv /path/to/new/virtual/environment

 * I like to set the path to be in the directory with a folder that shows the version of Python that I am running, so I include the python version I am using in the path.
 * This exaple is using python 3.10 but anything > 3.8 should work fine


```
python3 -m venv ./.venv/python3.10
```
* On Windows it is c:\>c:\Python310\python -m venv c:\path\to\myenv

```
c:\>c:\Python35\python -m venv c:\path\to\myenv
```

4. Start your virtual environment.

* Linux/Mac:

```
source ./.venv/bin/activate
```

* Windows:

```
c:\path\to\myenv\Scripts\activate.bat
```


 * and then for both Linux/Mac and Windows import the requirements file
```
pip install -r requirements.txt
```

5. Test that it is not legacy Python, ie 2.7

```
python --version
```
* You should see something like this:
```
Python 3.10.2
```

6. Now start the jupyter notebook by entering
```
jupyter notebook Jupyter_Practice.ipynb
```

## Authors

* **John MacTavish** - *Initial work* -
[TechSolX](https://github.com/techsolx)

See also the list of
[contributors](techsolx/python_basics_with_jupyter/graphs/master)
who participated in this project.

## License

This project is licensed under the MIT License - see the
[LICENSE](LICENSE) file for details

## Acknowledgments

* Stack Overflow for all the other stuff I can't remember.
