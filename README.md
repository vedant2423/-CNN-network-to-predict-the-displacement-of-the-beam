# -CNN-network-to-predict-the-displacement-of-the-beam.

Generateed the random topologies of the beam by altering the positions, sizes, and quantities of the holes in a random manner using the FEM code of the beam and trained CNN to predict displacement of the beam for random position of forces.

Given the Fem code we had data file with the coefficient of elasticity for elements of the beam, and the load applied on the beam.

We had to randomize the position of hole in the beam, generate he data for testing and validating and predict displacement of the beam in the first part.

Then using the original data file and changing the position of load among more than 1200 nodes to predict displacemnt of the beam in the secind part.

The third and the final part was to find maximam stress node and perform the prediction of displacement for the same by again generating data for the corresponding fornce and changing material properties.
