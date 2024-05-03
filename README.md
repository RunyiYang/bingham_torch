Pytorch Extension to Bingham Statistics
=================================
### Environment
To start, at least ensure these packages are installed.
```
torch==2.0.0
setuptools
```
####  Cuda version
This code is tested on cuda-11.7 and cuda-11.8, if you are using conda environments, this should work. And remember to link your cuda in the environment.
```
conda install cudatoolkit=11.7
```
#### Quick Start
```
conda env create -f environment.yaml
```
### How to build
1. (optional) if you are using conda, activate an environment that you want to work with
2. If you just want to compile the extension, use `python setup.py build` to build the extension. Uppon sussessfully compilation, you can find the `*.so` file in `build/lib.*/`. You can add this path to your python path or `cd` to this directory, and then start ipython to import the module
3. For installation you can run `python setup.py install`, and the extension will be installed, and then you can access it system-wise.

--------
### Acknowledgement
This is the updated version (torch 2.0.0, cuda 11.7, gcc-9, g++-9) of <a href="https://github.com/Multimodal3DVision/torch_bingham">torch_bingham</a>, which is built upon <a href="https://github.com/sebastianriedel/bingham">Bingham Statistics Library (BSL)</a>. 
