# **Decomposition of Toffoli gates for MCX optimization**
## **QOSF Mentorship Program** 

**Task 3:** Decompose

The project [report](https://github.com/SoumikSamanta10/QOSF-Decomposition-of-Toffoli-gates-for-MCX-optimization/blob/b3ea4f57a7d62dadc543ac8f93e51728c01622fd/Decomposition%20of%20Toffoli%20gates%20for%20MCX%20optimization.pdf) in the folder `Report'.

## **Project Description:**

The multi-controlled Toffoli(MCX) gate is essential to many quantum operations including the Glover operator, logical AND, various state preparation algorithms and arithmetic comparators. The decomposition of complex controlled operations (like CCX, CCCX) can be implemented using circuit built from elementary operations. But it is very complicated to constract MCX in minimum depth which being helpful in practical large scale designs.
<br>   In this project, we report standard decomposition of CCX & CCCX gates using the unitary U & CX gate and Ry(θ) based decomposition using qiskit library. We proposed reduced Toffoli gates without preserving control qubits and to find the best way to construct n-controlled MCX gate automatically, we used classical optimizer. We also discussed the spectral decomposition of MCX using qiskit pulse.
   

## **Key Results:**
1) Simulated standard decomposition of CCX & CCCX gates using the unitary U & CX gate and Ry(θ) based decomposition using qiskit library.
2) Defined problem of using MCX in current transpiler qiskit library.
3) Proposed a optimal solution by introducing reduced Toffoli gate decomposition.
4) Constructed a general n-controlled MCX gate.
5) Discussed the extension this work using spectral decomposition with qiskit pulse.



## **References:**

[1] Michael A Nielsen and Isaac L Chuang. Quantum computation and quantum information. Phys. Today, 54(2):60, 2001.

[2] D. Maslov, Phys. Rev. A 93, 022311 (2008).

[3] Classiq Coding Competition Spring 2022

[4] Pulse (qiskit.pulse) - Qiskit 0.44.2 documentation
