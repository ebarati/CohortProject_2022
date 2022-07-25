# Business Application of the gate model Shor's algorithm
## Technical problem you solved in this exercise:
Shor's factoring algorithm is one of the first (and few) textbook quantum algorithms with known exponential speedup.  In other words, it computes quantumly
something that is extremely difficult (if not impossible) to compute classically. Peter Shor developed this algorithm to find the prime factors of an 
integer.  Two features of Shor's algorithm render its quantum advantage in factoring - the quantum Fourier transform, and repeated squaring by modular 
exponentiation.  Three common public-key cryptography schemes in use today are vulnerable to quantum computer breakage (via Shor's algorithm) - RSA, Finite Field 
Diffie-Hellman key exchange, and Elliptic Curve Diffie-Hellman key exchange. 

## Real-world problems this solution can solve.
Since quantum computing has the potential to be both good and evil, it is necessary to prepare for the inevitable "Y2K moment". Our company proposes a 
quantum-safe cryptographic solution that will protect your sensitive data (whether it be financial data, health-care data, etc) from hackers and malicious
actors. There is wide range of potential customers for this problem. Whatever we deal with in the world can be expressed in the form of data. 
Thus, any company or organization (banks, heathlcare organizations, research institutes, ...) for which data is essential is a potential customer. 

## Identify at least one potential customer for this solution - ie: a business who has this problem and would consider paying to have this problem solved.


# Business Application of the gate model Shor's algorithm

As mentioned above, any company dealing with data security and cryptography will be a potential customer for quantum algorithms including Shor's.
Such as:
- https://protocol.ai/
- https://baffle.io/
- https://www.replicated.com/
- https://www.checkpoint.com/ ,

 to name a few.

# Compilation (Processor design / gate implementation) and analysis
We run the Shor's algorithm on two different platforms: the IBM cloud and our local memory. Figures [1-3] depicts the different values of N (factorized) versus the Runtime. 
The results of the two runs (cloud and local memory) shows that the runtime of factorized on N to its prime factors increases with increasing N for the both cases. 
Although, comparing the two runtimes may not make sense, due to the different crowd on the IBM cloud at the time of running, we also plot the Runtime versus N, 
and one can see the Runtime is smaller when running the code on the IBM cloud. 

We also plot the number of input and output qubit required for the Shor's algorithm for different N. 
As seen the number of qubits increases (N=8 --> 14) as N increases from N=15 to N=91 and they scale roughly as log (N).
 

# Real-world problems
- Cryptography in finance: Banks and financial institutes spend 1000s of dollars every year to avoid their losses. 
According to the Federal Trade Commission, despite all the security protocols American consumers loss to fraud is increasing. 
The loss was more than $5.8 billion in 2021, and up from $3.4 billion in 2020 (an increase of more than 70%).
Such loss can be prevented by quantum algorithm. 
That is why not only they are seeking help from quantum scientist, but also investing on quantum computing themselves by setting up separate departments working on quantum computations.


# References

[1] Shor, P. W. Polynomial-time algorithms for prime factorization and discrete logarithms on a quantum computer. SIAM review 41,
303–332 (1999).

[2] Learn Quantum Computation using Qiskit, https://qiskit.org/textbook/ch-algorithms/shor.html

[3] "Shor's Algorithm", https://en.wikipedia.org/wiki/Shor%27s_algorithm#Discrete_logarithms.

[4] https://scottaaronson.blog/?p=208

[5] https://github.com/PacktPublishing/Quantum-Computing-in-Practice-with-Qiskit-and-IBM-Quantum-Experience/blob/master/Chapter10/ch10_r2_shor_aqua.py

