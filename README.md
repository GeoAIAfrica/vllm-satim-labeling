# Labeling Satellite imagery in Africa using VLLMs

This repository contains the starter code to label satellite imagery using Vision-LLMs in Africa.

## Setup

### Google Colab

You can run the notebook using a GPU with Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Akramz/vllm-satim-labeling/blob/main/notebooks/starter_colab.ipynb)

### Local

Install `mamba` from [here](https://github.com/conda-forge/miniforge).

Setup a new environment and install the required dependencies as follows:

```bash
mamba create -n vllm_satim python=3.10
conda activate vllm_satim
pip install -r requirements.txt
```

## Dataset

You can obtain the competition dataset as follows:

```bash
cd data/
gdown https://drive.google.com/uc?id=1jw8vz6KvBm5u0RZExTEB4Zk1zjklEvea
unzip dataset.zip
```
