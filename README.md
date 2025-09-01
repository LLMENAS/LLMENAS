# LLMENAS
This is the implementation for the paper: LLMENAS: Evolutionary Neural Architecture Search via Large Language Model Guidance. This repo contains the implementation of the evaluation on CIFAR-10 using our proposed method. The full code will be released after the paper is accepted.

## Architecture Evaluation on CIFAR-10

To evaluate the derived architecture on CIFAR-10, please run

```python
export CUDA_VISIBLE_DEVICES=0
python train.py   \
--data /path/to/cifar10 \
--save train_cifar10   \
--auxiliary \
--cutout    \
