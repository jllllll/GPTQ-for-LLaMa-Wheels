# GPTQ-for-LLaMa-Wheels
Precompiled Wheels for GPTQ-for-LLaMa

Conda environment created using:
```
conda install python=3.10.9 torchvision torchaudio pytorch-cuda=11.7 cuda-toolkit conda-forge::ninja conda-forge::git -c pytorch -c nvidia/label/cuda-11.7.0 -c nvidia
```
Specifically without explicitly specifying `pytorch`. Intended for use with [text-generation-webui](https://github.com/oobabooga/text-generation-webui).
