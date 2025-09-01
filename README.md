# LLMENAS
This is the implementation for the paper: LLMENAS: Evolutionary Neural Architecture Search via Large Language Model Guidance. This repository provides the complete evaluation pipeline on CIFAR-10; the full code will be released upon paper acceptance.

## Architecture Evaluation on CIFAR-10

To evaluate the derived architecture on CIFAR-10, please run

```python
export CUDA_VISIBLE_DEVICES=0
python train.py   \
--data /path/to/cifar10 \
--save train_cifar10   \
--auxiliary \
--cutout    \
