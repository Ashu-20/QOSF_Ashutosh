# QOSF_Ashutosh
This contain my solution for the QOSH cohort test question number 2.

I have encode the list onto a quantum circuit using a orcle. Number of qubits required to encode is equal to the length of the list. Oracle flip the qubit with index corresponding to positive element in the list. Total 
number of qubits required for the algoritm is equal to lenght of the list + 1. Last qubit is the measurement qubit on which the measurement operation will be performed. Multi qubit toffoli gate is applied with control
qubits as the encoded qubits using the oracle and measurement qubit is the target qubit. If the target qubit is in state |0> after the measurement, it emplied that there are one or more negative element in the list.
Otherwise there are not negative elements in the list. 
For a list of N integers, number of qubits required for the algorithm is N+1 and number of measurement performed is 1.
