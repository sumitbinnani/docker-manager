# Pytorch Dockers
Repository with dockerfiles for Pytorch Container.

The images can be found at: [sbinnani/pytorch](https://hub.docker.com/r/sbinnani/pytorch).

The tags starting with VNC also has a headless VNC server installed in the container. The VNC Server runs on the port `5901`. The vnc password is `vncpassword`. The VNC Server can also be access from http://IP:6901/?password=vncpassword. 

The tag name follows the format v`PYTORCH_VER`-py`PYTHON_VER`-cuda`CUDA_VER`-cudnn`CUDANN_VER`-runtime-ubuntu`DISTRO-VER`.
