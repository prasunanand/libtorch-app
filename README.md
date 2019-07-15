# libtorch-app
Using libtorch c++ api

## Using the prebuilt libtorch:
Follow instructions in the [link](https://pytorch.org/cppdocs/installing.html) to use libtorch C++ api. However the binary available runs only on CPU.

## Using libtorch built from source.

1. Follow instructions in the [link](https://github.com/pytorch/pytorch/blob/master/docs/libtorch.rst).
2. Now while calling cmake command `cmake -DCMAKE_PREFIX_PATH=/absolute/path/to/libtorch ..`, there are errors.

The error is with regard to building caffe2. So, are we missing any instructions. Even after setting caffe2 path there are issues with missing files in Cafe2Config.cmake.
