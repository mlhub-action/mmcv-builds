## Intro
Community [mmcv](https://github.com/open-mmlab/mmcv) builds with Github Actions

## Installation

### Windows

#### Python 3.10
##### torch2.0.0+cu118
```bash
pip install -U https://github.com/mlhub-action/mmcv-builds/releases/download/v1.7.1/mmcv_full-1.7.1+git.7a13f99+torch2.0.0+cu118-cp310-cp310-win_amd64.whl
```
##### torch1.13.1+cu117
```bash
pip install -U https://github.com/mlhub-action/mmcv-builds/releases/download/v1.7.1/mmcv_full-1.7.1+git.7a13f99+torch1.13.1+cu117-cp310-cp310-win_amd64.whl
```

#### Python 3.9
##### torch2.0.0+cu118
```bash
pip install -U https://github.com/mlhub-action/mmcv-builds/releases/download/v1.7.1/mmcv_full-1.7.1+git.7a13f99+torch2.0.0+cu118-cp39-cp39-win_amd64.whl
```
##### torch1.13.1+cu117
```bash
pip install -U https://github.com/mlhub-action/mmcv-builds/releases/download/v1.7.1/mmcv_full-1.7.1+git.7a13f99+torch1.13.1+cu117-cp39-cp39-win_amd64.whl
```

### Linux

#### Python 3.10
##### torch2.0.0+cu118
```bash
pip install -U https://github.com/mlhub-action/mmcv-builds/releases/download/v1.7.1/mmcv_full-1.7.1+git.7a13f99+torch2.0.0+cu118-cp310-cp310-manylinux2014_x86_64.whl
```
##### torch1.13.1+cu117
```bash
pip install -U https://github.com/mlhub-action/mmcv-builds/releases/download/v1.7.1/mmcv_full-1.7.1+git.7a13f99+torch1.13.1+cu117-cp310-cp310-manylinux2014_x86_64.whl
```

#### Python 3.9
##### torch2.0.0+cu118
```bash
pip install -U https://github.com/mlhub-action/mmcv-builds/releases/download/v1.7.1/mmcv_full-1.7.1+git.7a13f99+torch2.0.0+cu118-cp39-cp39-manylinux2014_x86_64.whl
```
##### torch1.13.1+cu117
```bash
pip install -U https://github.com/mlhub-action/mmcv-builds/releases/download/v1.7.1/mmcv_full-1.7.1+git.7a13f99+torch1.13.1+cu117-cp39-cp39-manylinux2014_x86_64.whl
```

## Support
 - Python : 3.9, 3.10
 - Package : Python Wheel
 - OS compatibility : [manylinux2014_x86_64](https://github.com/pypa/manylinux)
 - [CUDA Application Compatibility](https://docs.nvidia.com/deploy/cuda-compatibility/index.html#use-the-right-compat-package) : 11.7 11.8
 - [PyTorch](https://pytorch.org/get-started/locally/) : 1.13.1 2.0.0
 - [GPU Compute Capability](https://developer.nvidia.com/cuda-gpus) : 7.0 7.5 8.0 8.6 8.9

## Credits
 - https://github.com/open-mmlab/mmcv
