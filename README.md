# fast-ai-machine-learning-1
Fast.ai Machine Learning course work and notes

## Linux Red Hat 7 setup

```
git clone https://github.com/fastai/fastai.git
cd fastai
conda env create -f environment.yml -n fastai-old
# Installs fastai 0.7 environment even if we're on master branch
conda activate fastai-old
python
>>> import torch
>>> torch.cuda.is_available()
True
```
