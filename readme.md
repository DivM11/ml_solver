## Purpose
The basic ML package is used to run scikit-learn type models with high abstraction, automating repetative tasks in training data preparation such as imputation, encoding etc. and during model tuning such as running CV, tuning and training.

## Steps to run
1. Install basic packages like `pandas`, `scikit-learn` etc. Exclude `tensorflow` if embeddings are not going to be used.
```{sh}
pip install -r requirements.txt
```
2. Move the folder `basic_ml` to the working directory. Import and use!