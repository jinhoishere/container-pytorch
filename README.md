# PyTorch Container(Docker) Dev Environment

* This repository provides a PyTorch development environment using a Docker container.

* If you have NVIDIA GPU(s), install [NVIDIA CUDA Toolkit](https://developer.nvidia.com/cuda-downloads) to use your GPU(s) for the faster computing. Check [here](https://developer.nvidia.com/cuda-gpus) if they are compatible with NVIDIA CUDA Toolkit.

* The file [requirements.txt](./app/assets/requirements.txt) has a list of other installed dependencies.

### Things to consider for the future
* TensorFlow is currently installed in a separate container, but they will be merged into this container in the future so that both PyTorch and TensorFlow can be used interchangeably within a single container.
* Other dependencies will be added if necessary.

