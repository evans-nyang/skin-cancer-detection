# Project Prerequisite

## Contents

- [Setting up](#setting-up)
  - [Local Machine Setup](#local-machine-setup)
    - [Install Python](#install-python)
    - [Install Git](#install-git)
  - [Virtual Environment Setup](#virtual-environment-setup)
    - [Conda](#conda)
    - [Pip](#pip)
  - [Project Setup](#project-setup)
    - [Clone repo](#clone-the-repository)
    - [Install dependency](#install-dependencies)
- [Issues](#issues)
- [Extras](#extras)

## Setting up

### Local Machine Setup

To run the project in a linux os environment, you need to have Anaconda or Miniconda installed on your machine.
You can download Miniconda from the [official website](https://docs.conda.io/en/latest/miniconda.html).
For windows users, you can download Anaconda from the [official website](https://www.anaconda.com/products/distribution).

You can also use windows subsystem for linux (WSL) to run the project. Visit the [official website](https://docs.microsoft.com/en-us/windows/wsl/install) to install WSL.

Check out [`bin`](../bin/) directory at the project root for miniconda installation.

#### Install Python

To run the project, you need to have Python installed on your machine. You can download Python from the [official website](https://www.python.org/downloads/).

#### Install Git

You need to have Git installed on your machine to clone the project repository. You can download Git from the [official website](https://git-scm.com/downloads).

### Virtual Environment Setup

#### Conda

To create a conda virtual environment for the project, run the following command:

```bash
conda create --name skin-cancer-detection python=3.10
```

To activate the virtual environment, run the following command:

```bash
conda activate skin-cancer-detection
```

To deactivate the virtual environment, run the following command:

```bash
conda deactivate
```

#### Pip

To create a pip virtual environment for the project, run the following command:

```bash
python -m venv skin-cancer-detection
```

To activate the virtual environment, run the following command:

```bash
source skin-cancer-detection/bin/activate
```

To deactivate the virtual environment, run the following command:

```bash
deactivate
```

### Project Setup

#### Clone the Repository

To clone the project repository, run the following command:

```bash
git clone https://github.com/evans-nyang/skin-cancer-detection.git
```

#### Install Dependencies

To install the project dependencies, run the following command:

```bash
pip install -r requirements.txt
```

## Issues

We used `pydot` in the notebook to visualize our keras model. `pydot` is a Python interface to Graphviz and its DOT language. You can use pydot to create, read, edit, and visualize graphs.

`pydot` dependencies include:

- pyparsing: used only for loading DOT files, installed automatically during pydot installation.
- GraphViz: used to render graphs in a variety of formats, including PNG, SVG, PDF, and more. Should be installed separately, using your system's package manager, something similar (e.g., MacPorts), or from its source.

`pydot` may not work correctly if `graphviz` is installed via `pip` command in python. To solve this, install `graphviz` in your linux environment using `apt-get` as shown below:

```bash
sudo apt-get install graphviz
```

The code below is extracted from the notebook cell, keras leverages pydot for model visualization:

```python
keras.utils.plot_model(model, show_shapes=True, show_layer_names=True, dpi=60)
```

## Extras

- Check out the pydot documentation here: [pydot documentation](https://pypi.org/project/pydot/)
- To see what Graphviz is capable of, check the [Graphviz Gallery!](https://graphviz.org/gallery/)
