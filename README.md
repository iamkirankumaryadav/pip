# `pip`
- A package manager / installer for Python.
- It is used to install and manage software packages from the Python Package Index (PyPI).
- `PyPI` is a repository of Python packages.
- Pip is a command-line tool.
- Pip can also be used with a graphical user interface (GUI)

Useful Pip Commands:

### 1. Install a package:
```python
pip install package_name
```
- Installs the specified package and all its dependencies.

### 2. Show package information:
```python
pip show package_name
```
- Displays detailed information about specified package.
- Version, location, dependencies and installed files.

### 3. Upgrade a package:
```python
pip install --upgrade package_name
```
- Upgrades the specified package to the latest version.

### 4. Search a package:
```python
pip search package_name
```
- Searches the Python Package Index (PyPi) for packages.

### 5. Uninstall a package:
```python
pip uninstall package_name
```
- Removes the specified package and all its dependencies.

### 6. Check for outdated packages:
```python
pip list --outdated
```
- Displays a list if all the packages installed in Python environment that have newer versions available.

### 7. Install packages from a requirements.txt file:
```python
pip install -r requirements.txt
```
- Installs the packages list in the requirements.txt file in current directory.

### 8. Create a requirements.txt file:
```python
pip freeze > requirements.txt
```
- Creates a requirements.txt file that lists all the packages installed with their versions in your Python environment.

### 9. List installed packages:
```python
pip list
```
- Displays a list if all the packages installed in Python environment.

### 10. Install a package in editable mode:
```python
pip install -e path/to/package_name
```
- Installs the specified package in editable mode.
- Any changes made in the source code of the package are immediately reflected in our Python environment.


