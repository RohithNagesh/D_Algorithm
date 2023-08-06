# Implementation of D Algorithm using python. 
# Automatic Test Pattern Generation (ATPG):
ATPG is a technique used in digital circuit design to generate test patterns for detecting faults or defects in integrated circuits. The ATPG algorithm works by modeling the circuit as a set of logic gates and generating input patterns that will cause the circuit to produce specific output patterns. The output patterns are then compared to the expected output patterns to detect any faults or defects in the circuit.
# D ALGORITHM 
The D algorithm is a type of deterministic ATPG (Automatic Test Pattern Generation) algorithm used to generate test patterns for digital circuits. The algorithm is based on the concept of D-notation, which is a compact representation of a set of input patterns that can detect a particular fault in the circuit.

The main advantage of the D algorithm is its ability to generate complete and efficient test sets that can detect all faults in the circuit. The D algorithm is particularly useful for large and complex circuits because it reduces the number of input patterns needed to detect faults.
# The D algorithm follows the following basic steps:
1. **Circuit Modeling:** The circuit is modeled as a set of logic gates using a standard description language such as VHDL or Verilog.
2. **Fault Simulation:** Fault simulation is used to determine which faults or defects are present in the circuit.
3. **D-notation Generation:** The D algorithm generates D-notation for each fault in the circuit. D-notation is a compact representation of a set of input patterns that can detect a particular fault in the circuit.
4. **Test Pattern Generation:** The ATPG-D algorithm generates test patterns by iteratively modifying the input patterns and checking the resulting output patterns until all the faults have been detected. The algorithm uses a deterministic search strategy that ensures that all possible test patterns are considered.
5. **Test Application:** The generated test patterns are then applied to the actual circuit to verify that it is functioning correctly and to detect any remaining faults.


