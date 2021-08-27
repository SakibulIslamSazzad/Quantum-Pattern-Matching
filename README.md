
This work is an effort to verify a quantum alogorithm for pattern matching proposed by UMD, IonQ [1].
Here, a 8-bit classical bit string is verified using IBM qiskit platform. So far the coding works for any bits pattern by
0 to 8 bits. Speciality of the proposed algo is that it introduced a **Cyclic shift operator**- a conditional left cyclic rotation
and it was implemented by ***cswap*** gate. Then Grovers algorithm is implemented on it. 







**References**

[1] Niroula, P., Nam, Y. A quantum algorithm for string matching. npj Quantum Inf 7, 37 (2021). https://doi.org/10.1038/s41534-021-00369-3