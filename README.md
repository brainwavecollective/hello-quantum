# Hello Quantum! 

This repo contains a [simple example](hello-world.ipynb) that will walk you thorough a basic use case for quantum computing. There are two main parts; you will first create a quantum program and run it on a quantum processing unit (QPU), and then scale it up to a larer number of qubits. Much of this comes from the Hello World [video](https://youtu.be/93-zLTppFZw) in the Coding with Qiskit 1.0 YouTube series. The video contains some outdated code that will not exactly line up with this example, but the concepts are the same so it may still be helpful to reference.

# Getting Started

## Prerequisites

Although it is possible to run qiskit locally, we will run these examples on an actual quantum computer. You will need an account on the [IBM Quantum Platform](https://quantum.ibm.com/?utm_source=brainwavecollective&utm_medium=referral&utm_campaign=hello-quantum). Once your account is created, take note of your API key that will be available on the main page.

This example also expects that you have installed [conda](https://docs.conda.io/projects/conda/en/stable/user-guide/install/index.html)(miniconda is adequate) and [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).  

## Installation & Setup 
```
# Download this repository  
git clone https://github.com/brainwavecollective/hello-quantum.git

# Create the environment 
conda env create -f hello-quantum/environment.yml

# Activate the environment 
conda activate hello-quantum

# Run this notebook 
jupyter notebook hello-quantum/hello-world.ipynb
```
The notebook will open in a browser, and will walk you through the rest of the steps.

## Attribution Notice:

This project, developed by the Brain Wave Collective, incorporates code/documentation adapted from the Qiskit documentation repository, originally licensed under the [Apache License 2.0](https://github.com/Qiskit/documentation/blob/aa8e078dcf04d644d1a2877a7c54b46463b8a637/LICENSE). The adapted material, which can be found [here](https://github.com/Qiskit/documentation/blob/aa8e078dcf04d644d1a2877a7c54b46463b8a637/docs/guides/hello-world.ipynb), serves as a foundational element.

This repository's main license is the MIT License, but portions derived from the Qiskit repository are governed by the Apache License 2.0.

## Next steps
  *   Learn how to [build quantum circuits](https://docs.quantum.ibm.com/guides/map-problem-to-circuits) in more detail.
  *   Try a [tutorial](https://learning.quantum.ibm.com/catalog/tutorials) in IBM Quantum Learning.
  *   [Contact Daniel at the Brain Wave Collective](mailto:daniel@brainwavecollective.ai) with any questions.

