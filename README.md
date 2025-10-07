Nested Grover's Algorithm  for Tree Search

See the paper at: http://arxiv.org/abs/2509.07041

We investigate optimizing quantum tree search algorithms by employing a nested Grover Algorithm. This approach seeks to enhance results compared to previous Grover-based methods by expanding the tree of partial assignments to a specific depth and conducting a quantum search within the subset of remaining assignments. The study explores the implications and constraints of this approach, providing a foundation for quantum artificial intelligence applications.
Instead of utilizing conventional heuristic functions that are incompatible with quantum tree search, we introduce the partial candidate solution, which indicates a node at a specific depth of the tree. By employing such a function, we define the concatenated oracle, which enables us to decompose the quantum tree search using Grover’s algorithm.


The software runs with qiskit 2.2. If you have an older version

and get an error at result=simulator.run(qc.decompose().decompose(),shots=10000).result() 

just add another decompose(), if still the error is present, add another decompose() repeat till error disappears.
