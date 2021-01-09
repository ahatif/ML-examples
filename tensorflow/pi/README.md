
## Update system
$ sudo apt-get update
$ sudo apt-get upgrade

## remove old versions
$ sudo pip uninstall tensorflow
$ sudo pip3 uninstall tensorflow

## install the dependencies 
$ sudo apt-get install gfortran
$ sudo apt-get install libhdf5-dev libc-ares-dev libeigen3-dev
$ sudo apt-get install libatlas-base-dev libopenblas-dev libblas-dev
$ sudo apt-get install liblapack-dev cython
$ sudo -H pip3 install pybind11
$ sudo -H pip3 install h5py==2.10.0

## Install TensorFlow
$ sudo -H pip3 install tensorflow-2.1.0-cp37-cp37m-linux_armv7l.whl
## reboot
$ sudo reboot
