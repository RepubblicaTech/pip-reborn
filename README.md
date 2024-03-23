# Pip-Reborn

A new implementation of pip to integrate in your code!
### 03/2024 Update: now you can call the function and install more packages at once, e.g.: `pip.install('tqdm', 'wget', 'customtkinter')`

# Easy instructions

1. Download the pip.py file you find in the `Releases` section.

2. Move it to your Python project

3. `import` it and enjoy

## Practical example

![image](https://user-images.githubusercontent.com/76620155/201388406-fa3a7895-8693-4731-b730-2c487a93e37b.png)

1. Importing the pip file (i've put it in a `py_libs` folder inside my code)

2. Executing the `pip.install()` function

# Functions

## `pip.install('package-name')`

Installs the package in parenthesees

## `pip.upgrade('package-name')`

Upgrades the package in parenthesees

# Future projects

- [x] Implementing `upgrade` function
- [ ] Add the possibility to install/upgrade multiple packages at once (e.g `pip.install('wget', 'tqdm', 'requests')`)
