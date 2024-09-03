# My Python Packages

The functions frequently used in my current work are uploaded to the Python Package Index (PyPI).

! This library is not longer under maintenance. had migrated to another.

## List

- [kswutils](https://pypi.org/project/kswutils/)

## Remarks

### Prerequisites

> pip install setuptools

> pip install twine

### Steps

> cd {package_dir}

> python setup.py sdist

> twine upload dist/*

### Reupload

- Change the version number in setup.py
- Remove the previous dist folder

### To use / upgrade

> pip install {package}

> pip install {package} --upgrade
