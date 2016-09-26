# Optimization of OpenJDK8 for ARMv8 64 bit

OpenJDK is the official implementation of the Java Platform and therefore very popular and frequently used.
ARMv8 is an architecture introduced in 2013, which is constantly gaining popularity, notably the 64 bit execution mode is called aarch64.
The ARM architecture is very popular in the field of embedded systems but there are also implementations targeted to server applications.
In this work, an overview of OpenJDK8 for ARMv8 is given and methods to measure and analyze the performance are explained.
Furthermore, ways of optimizing the generated code are shown and are illustrated on a concrete example, which increases the performance up to 15.2% on certain benchmarks.
The evaluation of the respective performance is done by comparing the results of the SPECjbb2005 benchmark.
Finally the advantages of this optimization and future work are discussed.

