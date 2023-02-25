# Backpropagation from Scratch

This notebook demonstrates the mathematic principles underlying backpropagation - the prevalent method how to train neural networks. It is based on the [micrograd](https://github.com/karpathy/micrograd) library from Andrej Karpathy.

# Usage
## Google Colab

- Click on the "Open in Colab" badge in the [notebook](Backpropagation_From_Scratch.ipynb)

## Local
### First-Time Setup

1. Install virtualenv: `$ python3 -m pip install --user -U virtualenv`
2. Create python environment: `$ cd <path_to_project>`, `$ python3 -m venv <enviroment_name>`
3. Activate python environment: `$ cd <path_to_project>`, `$ source <enviroment_name>/bin/activate`
4. Install dependencies: `$ python3 -m pip install -U jupyter numpy matplotlib graphviz`
5. Register python environment as kernel: `$ python3 -m ipykernel install --user --name=python3`

### Every Time
#### Before

1. Activate python environment: `$ cd <path_to_project>`, `$ source <enviroment_name>/bin/activate`
2. Start Jupyter: `$ jupyter notebook` (starts webserver on localhost:8888)

#### After

1. Close Jupyter: `Ctrl+C` in terminal
2. Deactivate python environment: `$ deactivate`
