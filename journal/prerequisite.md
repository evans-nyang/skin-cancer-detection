# Project Prerequisite

## Contents

## Setup

### Local Machine Setup

To run the project in a linux os environment, you need to have Anaconda or Miniconda installed on your machine.
You can download Miniconda from the [official website](https://docs.conda.io/en/latest/miniconda.html).
For windows users, you can download Anaconda from the [official website](https://www.anaconda.com/products/distribution).

You can also use windows subsystem for linux (WSL) to run the project. Visit the [official website](https://docs.microsoft.com/en-us/windows/wsl/install) to install WSL.

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
