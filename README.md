# Creative approaches to problem solving[$^1$](https://qz.com/192071/how-one-college-went-from-10-female-computer-science-majors-to-40/) in neuroscience using Python

## Introduction to (Scientific) Progamming

### featuring Neurons and Maths

by [Christopher Brian Currin](https://chriscurrin.com)

A _functional approach_ to learning code. _Why-based_ in contrast to _fact-based_.

![Cape Town](https://images.unsplash.com/photo-1563656157432-67560011e209?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=900&h=300&q=80)

# Setup

## Install Python

1. Download MambaForge from https://github.com/conda-forge/miniforge#mambaforge
2. Create an environment

   ```bash
   conda create -n imbizo python
   ```

3. Install dependencies

   ```bash
   pip install matplotlib numpy jupyter
   ```

   or

   ```bash
   pip install -r requirements.txt
   ```

   or locally on linux

   ```bash
   pip install -r requirements --no-index --find-links dependencies/<OS>
   ```
   where `<OS>` is `linux` or `macos` or `windows`.

# Colab

1. https://colab.research.google.com/github/ChrisCurrin/imbizo_2023_creative_approaches/blob/main/1%20-%20the%20neuron.ipynb
2. https://colab.research.google.com/github/ChrisCurrin/imbizo_2023_creative_approaches/blob/main/2%20-%20synapses.ipynb
3. https://colab.research.google.com/github/ChrisCurrin/imbizo_2023_creative_approaches/blob/main/3%20-%20simulator.ipynb