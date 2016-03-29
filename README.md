# InfOli
Demo of the InfOli project, an accurate biological-neuron simulator.
The code aims at creating a network of inferior olivary nuclei and simulate its biophysical behaviour
for the specified amount of time.

This demo contains a single-threaded version of the main code, along with two tools. One generator for
the network's connectivity map (an adjacency matrix) and one generator for feeding the network with 
current (optional).

The full repository is private and hosts multiple methods used for parallelizing the code, its porting
on Xeon Phi accelerators, as well as multiple tools for creating connectivity maps and generating input.

This repository was mostly created as a proof-of-concept. We mostly aim at sharing this repository when
applying for access to supercomputing clusters across Europe, in hopes of testing and optimizing our codebase.
