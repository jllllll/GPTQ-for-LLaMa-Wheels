# GPTQ-for-LLaMa-Wheels
Precompiled Wheels for [GPTQ-for-LLaMa](https://github.com/qwopqwop200/GPTQ-for-LLaMa/tree/cuda)

Currently not using the latest commits. This wheel is compatible with this fork: https://github.com/oobabooga/GPTQ-for-LLaMa.git 

Conda environment created using:
```
conda install python=3.10.9 torchvision torchaudio pytorch-cuda=11.7 cuda-toolkit conda-forge::ninja conda-forge::git -c pytorch -c nvidia/label/cuda-11.7.0 -c nvidia
```
Specifically without explicitly specifying `pytorch`. Intended for use with [text-generation-webui](https://github.com/oobabooga/text-generation-webui).
