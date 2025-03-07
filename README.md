# CogModels

## Quick Start

### Prerequisites

Please ensure that you have the following packages installed in your environment:

- [`torch`](https://github.com/pytorch/pytorch)
- [`torchvision`](https://github.com/pytorch/vision)

If you want to finetune CogVideo series, please install the following packages as well:

- [`opencv-python`](https://github.com/opencv/opencv-python) or [`opencv-python-headless`](https://github.com/opencv/opencv-python)
- [`decord`](https://github.com/dmlc/decord) (Please build from source to enable GPU acclerator.)

### Installation

```bash
pip install 'cogmodels @ https://github.com/zRzRzRzRzRzRzR/cogkits.git@test'
```

### Finetune

The training script is located at `src/cogmodels/finetune/diffusion/train.py`.
See scripts in the `src/cogmodels/finetune/diffusion/scripts/` to start finetuning tasks.
