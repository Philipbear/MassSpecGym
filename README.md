# MassSpecGym: A benchmark for the discovery and identification of molecules

<p>
  <a href="https://github.com/pytorch/pytorch"> <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white" height="22px"></a>
  <a href="https://github.com/Lightning-AI/pytorch-lightning"> <img src="https://img.shields.io/badge/-Lightning-792ee5?logo=pytorchlightning&logoColor=white" height="22px"></a>
  <a href="https://github.com/psf/black"><img alt="Code style: black" src="https://img.shields.io/badge/code%20style-black-000000.svg" height="22px"></a>
<p>

[![Dataset on Hugging Face](https://huggingface.co/datasets/huggingface/badges/resolve/main/dataset-on-hf-md-dark.svg)](https://huggingface.co/datasets/roman-bushuiev/MassSpecGym)  

📣 A paper will be available soon!

## Installation

Installation for development:

```bash
conda create -n massspecgym python=3.11
conda activate massspecgym
git clone https://github.com/pluskal-lab/MassSpecGym.git; cd MassSpecGym
pip install -e .[dev,notebooks]
```

For AMD GPUs, you may need to install PyTorch for ROCm:

```bash
pip install -U torch --index-url https://download.pytorch.org/whl/rocm6.0
```

## TODO

- [ ] Croissant.
- [ ] Refactor `transforms.py` -> `data/transforms.py`
- [ ] Optimize de novo evaluation metrics to run in parallel by workers initialized in the corresponding pl.Module constructor
- [ ] Link to documentation.
- [ ] Link to Papers With Code leaderboard.
