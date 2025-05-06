# DLH Final Project

This project reproduces the [SAMIL](https://github.com/tufts-ml/SAMIL) framework for training and evaluating view classification models on echocardiogram data. All model training and evaluation code is contained in a single Jupyter notebook: `dlh_final.ipynb`.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/selenaalu/dlh-final-project.git
cd dlh-final-project
````

### 2. Install dependencies

We recommend creating a virtual environment before installing dependencies.

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use venv\Scripts\activate
pip install -r requirements.txt
```

> **Note**: If you're using a CUDA-enabled GPU, ensure your CUDA and PyTorch versions are compatible.

### 3. Download pretrained view classifiers

You can download the pretrained model checkpoint here:

👉 [Pretrained View Classifier (Box)](https://tufts.app.box.com/s/c5w8123j7h3dpls75jye1363uh8qv8us/file/1256335932040)

Save the file into your working directory or update the paths in the notebook to point to the downloaded checkpoint.

## Notebook

All the code needed for training and evaluation is located in the notebook:

* [`dlh_final.ipynb`](dlh_final.ipynb)

The notebook includes:

* Data loading and preprocessing
* Model setup and training using SAMIL
* Evaluation of model performance
* Visualization of classification results

## Acknowledgments

This project leverages the [SAMIL](https://github.com/tufts-ml/SAMIL) library for supervised attention in multi-instance learning.

## Citation

If you use this codebase or the SAMIL library, please cite the original paper:

> Ding, Y., Zhang, Y., & Ghosh, J. (2023). Supervised Attention in Multi-Instance Learning. *arXiv preprint arXiv:2310.03013*.
> [https://arxiv.org/abs/2310.03013](https://arxiv.org/abs/2310.03013)

