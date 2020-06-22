# query_ibmq
In  **Efficient Learning of quantum Noise** [arXiv:1907.13022](https://arxiv.org/abs/1907.13022)  (https://github.com/rharper2/Juqst.jl) we  show how to analyse data gathered by doing simultaneous Clifford twirls on the qubits of the device. The data gathered allows extensive reconstruction (of the locally averaged) probability vector of the device. Lending itself to, for example, charactersising unexpected correlations between the qubits.

In this workbook I show (in python) how to query IBM devices using standard qiskit tools. The workbook is for the 14 qubit machine, but can be easily adapted for larger devices. If the device size is larger than, say, 28 qubits then the workbook discusses how to save the data in a scalable way.

