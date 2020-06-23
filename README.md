# baseline-pointpillars
when do pointpillars configuration, need to change some files

pip install fire, tensorboardX, Shapely, pybind11, protobuf, scikit-image, numba, Pillow

export PYTHONPATH='/home/zhwang/second.pytorch:$PYTHONPATH'
export NUMBAPRO_CUDA_DRIVER=/usr/lib/x86_64-linux-gnu/libcuda.so
export NUMBAPRO_NVVM=/usr/local/cuda/nvvm/lib64/libnvvm.so
export NUMBAPRO_LIBDEVICE=/usr/local/cuda/nvvm/libdevice

Pytorch version: Stable(1.5)+Linux+Pip+Python+10.1

voxelnet.py, line 911, dir_labels.bool()
