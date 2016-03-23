# caffe-lstm-lisa
Dockerfile for docker image containing a compiled version of a fork of Caffe offered by Lisa.

Inspired by tleyden5iwx/caffe-gpu-master : https://hub.docker.com/r/tleyden5iwx/caffe-gpu-master

Run me with proper parameters:
nvidia-docker run -i -t --device=/dev/nvidia0:/dev/nvidia0 --device=/dev/nvidiactl:/dev/nvidiactl matthieudelaro/caffe-lstm-lisa

Your devices may change depending on your hardware. Use those returned by:
ls /dev | grep nvidia
