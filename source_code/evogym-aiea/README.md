# AIEA

Title: Rapidly Evolving Soft Robots via Action Inheritance

ID: TEVC-00157-2023

Authors: Liu, Shulei; Yao, Wen; Wang, Handing; Peng, Wei; Yang Yang

The code of AIEA is placed in examples/SAEA/AIEA.py.



# Evolution Gym

# Installation

Clone the repo and submodules:

```shell
git clone --recurse-submodules https://github.com/EvolutionGym/evogym.git
```

### Requirements

* Python 3.7/3.8
* Linux, macOS, or Windows with [Visual Studios 2017](https://visualstudio.microsoft.com/vs/older-downloads/)
* [OpenGL](https://www.opengl.org//)
* [CMake](https://cmake.org/download/)
* [PyTorch](http://pytorch.org/)

<!--- (See [installation instructions](#opengl-installation-on-unix-based-systems) on Unix based systems) --->

On **Linux only**:

```shell
sudo apt-get install xorg-dev libglu1-mesa-dev
```

Either install Python dependencies with conda:

```shell
conda env create -f environment.yml
conda activate evogym
```

or with pip:

```shell
pip install -r requirements.txt
```

### Build and Install Package

To build the C++ simulation, build all the submodules, and install `evogym` run the following command:

```shell
python setup.py install
``` 

More details can refer to [website](https://evolutiongym.github.io/documentation).
