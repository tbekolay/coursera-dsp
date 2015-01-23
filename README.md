Digital Signal Processing
=========================

This is work relating to [dsp-005](https://class.coursera.org/dsp-005).

Installation
------------

To work with this repo, you must have Python installed.
Then, make a new virtualenv and do

```console
pip install -r requirements.txt
```

Running notebooks
-----------------

Most of the work is in IPython notebooks.
In the top-level of this repo, run

```console
ipython notebook
```

to open and run the notebooks.

Accessing course materials
--------------------------

The actual course materials aren't stored in this repo;
instead, they are downloaded with
[`coursera-dl`](https://pypi.python.org/pypi/coursera-dl).
To download the materials, run

```console
coursera-dl -u <username> -p <password> -d . dsp-005
```
