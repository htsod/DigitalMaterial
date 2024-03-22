# DigitalMaterial
DigitalMaterial is a molecular dynamics simulation program that was made in 2006. It provides a framework for running simple and efficient molecular dynamics experiment. The version that the author works on is a simplified python version of the original software. Hence, it is aiming more on the education aspect than the functional aspect. 

## Preface
The original file is downloaded from [here](https://cac.cornell.edu/myers/teaching/ComputationalMethods/ComputerExercises/MolecularDynamics/MolecularDynamics.html)
which provides the MD software as a mean to solve several statistical mechanics problem. However, the files provided there is outdated and hence the format and compatibility issue are remain to be resolved.

The author intends to provide some updates to the original program such that it is compatible with the current version of python packages. Additionally, the author hopes to add in new functionality and more examples for demonstration.

## Modification to the Original file (2024/03/22)
- To made compatible with vpython
1. systematize variable type to vpython.vector. 
2. remove vpython.scene.range

- To made compatibble with Scipy
1. Scipy.sum change to numpy.sum 


## For Developer
The core design of the MD software could be found in the following paper [here](https://arxiv.org/pdf/cond-mat/0601236.pdf). 


## Copy Right
The original software has a APACHE LICENSE, VERSION 2.0. All rights reserved to the original author of DigitalMateterial.
