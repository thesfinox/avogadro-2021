# Applying Machine Learning to String Theory

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/thesfinox/avogadro-2021/blob/main/demo_cv.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/thesfinox/avogadro-2021/HEAD?labpath=demo_cv.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/thesfinox/avogadro-2021/blob/main/demo_cv.ipynb)

**Speakers**: Riccardo Finotello, Veronica Guidetti

**Code**: Riccardo Finotello <[riccardo.finotello@cea.fr](mailto:riccardo.finotello@cea.fr)>

**Venue**: [XVII Avogadro Meeting](https://www.ggi.infn.it/showevent.pl?id=407), 20 - 22 December 2021, [Galileo Galilei Institute for Theoretical Physics](https://www.ggi.infn.it/), Arcetri, Italy

## Synopsis

This repository contains complementary material and code for the course "Applying Machine Learning to String Theory".
In this small demo, we introduce some technical instruments to deploy a simple AI for the recognition of handwritten digits.
The main idea is to showcase the use of convolutional neural networks and autoencoders in a simple realisation, and to show possible generalisations and applications.

## Installation using Conda

First, make sure to clone the repository:

```bash
git clone https://github.com/thesfinox/avogadro-2021.git avogadro2021
cd avogadro2021
```

The [environment.yml](./environment.yml) should contain all the necessary information to install the Conda environment correctly.
To create it, use

```bash
conda env create -f environment.yml
```

If you prefer to manually create the environment, use

```bash
conda create -n avogadro2021 tensorflow-gpu numpy seaborn notebook
```

from the command line.

## Installation using Pip

If you prefer to use the native `pip` package manager, and notably if you use [Google Colab](https://colab.research.google.com/github/thesfinox/avogadro-2021/blob/main/demo_cv.ipynb), you may want to create a dedicated virtual environment:

```bash
python -m venv ./avogadro2021
source ./avogadro2021/bin/activate
pip install tensorflow numpy seaborn notebook
```

If you use [Google Colab](https://colab.research.google.com/github/thesfinox/avogadro-2021/blob/main/demo_cv.ipynb), make sure to add and run a cell containing

```bash
!python -m venv ./avogadro2021
!source ./avogadro2021/bin/activate
!pip install tensorflow numpy seaborn notebook
```

at the beginning of the notebook.

## Visualisation and Shared Notebooks

You can also simply visualise the notebook using [NBviewer](https://nbviewer.org/github/thesfinox/avogadro-2021/blob/main/demo_cv.ipynb) by clicking on the badge at the beginning of this file.
Otherwise, the notebook can also be run interactively using [Binder](https://mybinder.org/v2/gh/thesfinox/avogadro-2021/HEAD?labpath=demo_cv.ipynb) through the corresponding badge.
Notice that, in this case, quite some time may be dedicated to the automatic installation of the packages.
