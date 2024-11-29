# AdaptiveTainer

## Components

- [AdaptiveCpp](https://github.com/AdaptiveCpp/AdaptiveCpp)
- [CUDA Toolkit](https://developer.nvidia.com/cuda-toolkit)

## Build

```shell
apptainer build adaptivetainer.sif adaptivetainer.def
```

## Shell

```shell
apptainer shell adaptivetainer.sif        # without NVIDIA GPU
apptainer shell adaptivetainer.sif --nv   # with NVIDIA GPU
```
