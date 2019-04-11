# Pytorch Dockers
Repository with dockerfiles for Pytorch Container.

The images can be found at: [sbinnani/pytorch](https://hub.docker.com/r/sbinnani/pytorch).

The tags starting with VNC also has a headless VNC server installed in the container. The VNC Server runs on the port `5901`. The vnc password is `vncpassword`. The VNC Server can also be access from http://IP:6901/?password=vncpassword. 

The tag name follows the format:
`v{PYTORCH_VER}-py{PYTHON_VER}-cuda{CUDA_VER}-cudnn{CUDANN_VER}-runtime-ubuntu{DISTRO-VER}`.

## Without VNC Server
* `v1.0-py3.7-cuda10.0-cudnn7-runtime-ubuntu18.04`
* `v1.0-py3.6-cuda10.0-cudnn7-runtime-ubuntu18.04`
* `v1.0-py2.7-cuda10.0-cudnn7-runtime-ubuntu18.04`
* `v1.0-py3.7-cuda10.0-cudnn7-runtime-ubuntu16.04`
* `v1.0-py3.6-cuda10.0-cudnn7-runtime-ubuntu16.04`
* `v1.0-py2.7-cuda10.0-cudnn7-runtime-ubuntu16.04`

## With VNC Server
* `vnc-v1.0-py3.7-cuda10.0-cudnn7-runtime-ubuntu18.04`
* `vnc-v1.0-py3.6-cuda10.0-cudnn7-runtime-ubuntu18.04`
* `vnc-v1.0-py2.7-cuda10.0-cudnn7-runtime-ubuntu18.04`
* `vnc-v1.0-py3.7-cuda10.0-cudnn7-runtime-ubuntu16.04`
* `vnc-v1.0-py3.6-cuda10.0-cudnn7-runtime-ubuntu16.04`
* `vnc-v1.0-py2.7-cuda10.0-cudnn7-runtime-ubuntu16.04`
