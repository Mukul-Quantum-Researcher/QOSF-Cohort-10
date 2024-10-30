# QOSF-Cohort-10
QOSF Cohort 10 screening task
** Problem Statement :** 
Task 4 Decomposition
 A common challenge in the design and implementation of quantum circuits is that they become
 too extensive and complex due to the large number of qubits required.
 The number of quantum operations and the interdependence between qubits can further
 complicate the problem, making some traditional optimization methods ineffective or insufficient
 for reducing the complexity. Additionally, as the number of qubits increases, the fidelity of the
 circuit may be affected, which implies a greater need for advanced techniques to maintain the
 precision of operations.
 On the other hand, some quantum computing frameworks offer predefined optimization methods
 that may seem like a convenient option. However, they are not always the best alternative if one
 has a deep understanding of the quantum hardware structure. Customizing the circuits by taking
 advantage of the specific features of the quantum device in use can result in a more efficient
 design, better adapted to the physical limitations of the system. Therefore, having a solid
 understanding of the hardware can make the difference between a generic quantum circuit and
 one that is highly optimized for performance.
 Challenge:
$ |\psi\rangle = \frac{1}{2}(|01100\rangle + |10001\rangle + |10110\rangle + |11011\rangle $
 Find a quantum circuit that represents the state vector with a depth less than 50, using the
 basis_gates=[x,h,rz,cx] and the following architecture
