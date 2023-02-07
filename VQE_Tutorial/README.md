# Electronic Structure on Quantum Computer with VQE, ADAPT-VQE and Application to Custom Hamiltonian Tutorial, by Delmar Cabral and Brandon Allen

Classical computers use a bit representation to encode information and instructions. Each of these bits encode 1 or 0 depending on whether they are on or off. Analogously, a quantum computer can encode information in terms of $|0\rangle$ and $|1\rangle$ states, but also allows entanglement between each of the states. This entanglement is beneficial to chemistry problems as electrons interact with other electrons and these interactions are often correlated and an important factor in molecular properties. While quantum chemistry frameworks exist to address the problem of electronic correlation, these methods are often computationally expensive due to poor scaling with system size. Thus, a quantum computer framework to solve chemical problems may allow more efficient calculations for properties of chemical interest and higher accuracy (due to the possibility of entanglement between different quantum computer states).

Thus, this tutorial focuses on

*   Solving an electronic structure in a classical computer, with a primer on Electronic Structure
*   Encoding a problem into a quantum computer form (3 steps)

    *  Molecular Orbital Basis Transformation
    *  Second Quantization
    *  Qubit Encoding - Jordan-Wigner Map
  
*   Ansatz representation - Unitary Coupled Cluster with Singles, Doubles Excitations (UCCSD)

with each step exemplified by application to $H_2$. Finally the last section will also demonstrate an application to NEO-VQE.
