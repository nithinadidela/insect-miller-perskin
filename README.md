# Fluid-Structure Interaction: Flexible wing performing translation motion

This is a part of our undergraduate project titled 'Aeroelastic modelling of insect flight' carried out in the school of Mechanical sciences, Indian Institute of Technology Goa.

* Authors: Nithin Adidela, Revanth Sharma, Y. Sudhakar

* email: {nithin.adiela.16003,revanth.sharma.16003,sudhakar}@iitgoa.ac.in 

Fluid part of the simulation is performed on OpenFOAM v7. Solid part of the simulation is performed on CalculiX 2.15. Coupling of the simulation is achieved by preCICE-1.6.1

The  simulation is tested in serial mode in a machine running Ubuntu 18.04. The mesh used is coarse and the user is free to make the mesh finer to achieve a better agreement with the standard case after properly understanding the blockMeshdict file.

##Description

The insect wing is idealised to be a 2D flatplate traversing at an angle of attack of 45 degrees.
50% of the wing is rigid. 50% of the wing is elastic.
The wing is smoothly accelerated for a characteritic time of 0.32 seconds and travels with a characteristic velocity 1 until the time scale reaches 7.16 
