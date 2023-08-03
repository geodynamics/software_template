# My Project Title

```{image} _static/cig_logo_dots.png
:alt: My Logo
:width: 25%
:align: center
```

## About *My Project*

 This is provided as a template to create online documentation for your project.  

 Files here are in markdown (md) but you can use  and mix in reStructuredText (rst) as well.

## About this documentation

 This template uses the latest versions of the following python packages:

* sphinx 4.2.0
* sphinx-book-theme 1.0.1
* python 3.9.7
* myst-parser 0.18.1          &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; *if using rst*
* nbsphinx 0.9.2
* sphinxcontrib-bibtex 2.5.0

 If you want to build this documentation locally
 use `conda install` or `pip install` to install the packages. Alternatively,
 you can also use the file [environment.yml](https://github.com/geodynamics/software_template/blob/main/doc/sphinx_template/environment.yml) to create a new conda environment
 with all packages as `conda env create -f environment.yml`.

## Building

To build this html documentation locally, execute in the main directory `sphinx_template`:

```
make html
```

This creates the `_build/html` directory.

Open `index.html` to display your manual in a browser window.

See [https://readthedocs.org/](https://readthedocs.org/) for online hosting of your manual.

## License

*My Project* is published under the GNU GPL v3 or newer license.

---

## Table of Contents

```{toctree}
---
maxdepth: 2
---
user/index.md
notebooks/helloworld
references.md
```
