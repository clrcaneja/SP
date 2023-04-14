# SP
Only draft test runs for my network simulations

Network test file contains the completed running code for network SEIR simulations. SIR version has been included only for cross-checking with reference if code works. Bottom part is miscellaneous tests.

Phi test is a file using the epydemic package to solve for \Phi and code for network ODE. Have not yet figured out how to save the network per iteration of the simulation since package automatically trashes the network.

ODE Test is the ongoing file. Have written a code for the ODE itself but plots are incorrect. Phi function needs to be considered as a function of time but network has to be simulated like an epidemic (change states as t --> T) to access classes of infected nodes of degree k (for all degrees k in the network).
