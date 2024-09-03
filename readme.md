# My Python Package Index (PyPI) Packages

<!-- - [kswutils](https://pypi.org/project/kswutils/) -->

## [Package projects](https://packaging.python.org/en/latest/tutorials/packaging-projects/)

```
packaging_tutorial/
├── LICENSE
├── pyproject.toml
├── README.md
├── src/
│   └── example_package_YOUR_USERNAME_HERE/
│       ├── __init__.py
│       └── example.py
└── tests/
```

> python3.10 -m pip install --upgrade pip

> python3.10 -m pip install --upgrade build 

> cd {package_dir}

> python3.10 -m build

> python3 -m pip install --upgrade twine

> python3.10 -m twine upload --repository pypi dist/*

## Reupload

- Change the version number in setup.py
- Remove the previous dist folder

## To use / upgrade

> pip install {package}

> pip install {package} --upgrade
