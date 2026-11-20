# Practical Reference to Essential Algorithms in PI

An evolving reference project for learning important computer science concepts through implementations in **[Pilang](https://github.com/rolandbrake/pilang)**, my own programming language.

The goal is not only to collect algorithms. Every topic should explain the underlying idea, justify its correctness, measure its complexity, test edge cases, and demonstrate useful Pi language features.

## Learning path

The project is organized into four levels:

1. **Core**  the essential foundation for every computer scientist.
2. **Intermediate**  common data structures, problem-solving patterns, and algorithms.
3. **Advanced**  specialized algorithms and deeper theory.
4. **Systems and applications**  algorithms used in compilers, operating systems, databases, and distributed systems.


## Topic checklist

### 1. Foundations and algorithm analysis

- [ ] What is an algorithm?
- [ ] Abstract data types and interfaces
- [ ] Correctness, preconditions, postconditions, and loop invariants
- [ ] Proof by induction and proof by contradiction
- [ ] Big-O, Big-Theta, and Big-Omega
- [ ] Best-case, worst-case, amortized, and expected-case analysis
- [ ] Time-space tradeoffs
- [ ] Recursion and recurrence relations
- [ ] Master theorem
- [ ] Lower bounds
- [ ] Comparison-sorting lower bound
- [ ] Testing algorithms and designing edge cases
- [ ] Benchmarking and interpreting performance results

### 2. Arrays, sequences, and problem-solving patterns

- [ ] Dynamic arrays
- [ ] Linear search
- [ ] Binary search
- [ ] Binary search on the answer
- [ ] Two pointers
- [ ] Sliding window
- [ ] Prefix sums
- [ ] Prefix XOR
- [ ] Difference arrays
- [ ] Frequency counting
- [ ] Matrix traversal
- [ ] Kadane's algorithm
- [ ] Quickselect
- [ ] Fast exponentiation

### 3. Sorting

- [ ] Bubble sort
- [ ] Selection sort
- [ ] Insertion sort
- [ ] Merge sort
- [ ] Quicksort
- [ ] Heap sort
- [ ] Counting sort
- [ ] Radix sort
- [ ] Bucket sort
- [ ] Stability, in-place sorting, and adaptiveness
- [ ] External merge sort

### 4. Hashing and probabilistic data structures

- [ ] Hash functions
- [ ] Hash tables
- [ ] Separate chaining
- [ ] Open addressing
- [ ] Hash sets
- [ ] Frequency hashing
- [ ] Prefix sum with a hash map
- [ ] Rolling hash
- [ ] Hash collisions and adversarial input
- [ ] Bloom filters

### 5. Linked lists

- [ ] Singly linked lists
- [ ] Doubly linked lists
- [ ] Circular linked lists
- [ ] Reversing a linked list
- [ ] Fast and slow pointers
- [ ] Floyd's cycle detection
- [ ] Finding the middle node
- [ ] Merging sorted lists
- [ ] Removing the Nth node
- [ ] Linked-list intersection

### 6. Stacks, queues, and deques

- [ ] Stack
- [ ] Queue
- [ ] Deque
- [ ] Circular queue
- [ ] Balanced parentheses
- [ ] Expression evaluation
- [ ] Monotonic stack
- [ ] Monotonic queue
- [ ] Next greater and smaller element

### 7. Trees and binary search trees

- [ ] Binary trees
- [ ] Tree DFS and BFS
- [ ] Preorder, inorder, postorder, and level-order traversal
- [ ] Tree height and depth
- [ ] Binary search tree search, insertion, and deletion
- [ ] Validate a binary search tree
- [ ] Lowest common ancestor
- [ ] Tree diameter
- [ ] Serialize and deserialize a tree

### 8. Balanced trees, heaps, and priority queues

- [ ] AVL trees
- [ ] Tree rotations
- [ ] Red-black trees
- [ ] B-trees
- [ ] B+ trees
- [ ] Min-heaps and max-heaps
- [ ] Heapify
- [ ] Heap insertion and extraction
- [ ] Priority queues
- [ ] Top-K elements
- [ ] Kth largest and smallest element
- [ ] Merge K sorted lists
- [ ] Median from a data stream

### 9. Tries and string algorithms

- [ ] Trie
- [ ] Naive string matching
- [ ] String hashing
- [ ] Knuth-Morris-Pratt (KMP)
- [ ] Prefix function
- [ ] Rabin-Karp
- [ ] Boyer-Moore
- [ ] Z algorithm
- [ ] Aho-Corasick
- [ ] Suffix array
- [ ] Suffix tree
- [ ] Suffix automaton

### 10. Graph fundamentals

- [ ] Graph terminology and abstract graph interfaces
- [ ] Adjacency list, adjacency matrix, and edge list
- [ ] Directed and undirected graphs
- [ ] Weighted graphs
- [ ] Graph DFS and BFS
- [ ] Connected components
- [ ] Cycle detection
- [ ] Bipartite graph detection
- [ ] Topological sorting
- [ ] Kahn's algorithm
- [ ] DAG processing
- [ ] Eulerian paths and circuits
- [ ] Hamiltonian paths and cycles

### 11. Disjoint sets and connectivity

- [ ] Disjoint Set Union (Union-Find)
- [ ] Find and union
- [ ] Path compression
- [ ] Union by rank
- [ ] Union by size

### 12. Shortest paths and graph search

- [ ] BFS shortest path
- [ ] Dijkstra's algorithm
- [ ] Bellman-Ford
- [ ] Floyd-Warshall
- [ ] A* search
- [ ] Bidirectional search

### 13. Minimum spanning trees and network flow

- [ ] Kruskal's algorithm
- [ ] Prim's algorithm
- [ ] Strongly connected components
- [ ] Kosaraju's algorithm
- [ ] Tarjan's algorithm
- [ ] Bridges
- [ ] Articulation points
- [ ] Maximum flow and minimum cut
- [ ] Ford-Fulkerson
- [ ] Edmonds-Karp
- [ ] Bipartite matching

### 14. Recursion, backtracking, and divide and conquer

- [ ] Backtracking
- [ ] Permutation generation
- [ ] Combination generation
- [ ] Subset generation
- [ ] Bitmask subset enumeration
- [ ] N-Queens
- [ ] Sudoku solver
- [ ] Maze and path search
- [ ] Generate parentheses
- [ ] Divide-and-conquer design
- [ ] Closest pair of points

### 15. Greedy algorithms and interval problems

- [ ] Greedy strategy and exchange arguments
- [ ] Activity selection
- [ ] Interval scheduling
- [ ] Fractional knapsack
- [ ] Jump Game
- [ ] Huffman coding
- [ ] Job scheduling
- [ ] Merge intervals
- [ ] Insert interval
- [ ] Interval intersection
- [ ] Meeting-room scheduling
- [ ] Sweep-line algorithms

### 16. Dynamic programming

- [ ] Optimal substructure and overlapping subproblems
- [ ] Memoization
- [ ] Bottom-up DP
- [ ] State design and state transitions
- [ ] 1D DP
- [ ] 2D DP
- [ ] Grid DP
- [ ] Fibonacci and climbing stairs
- [ ] House Robber
- [ ] Coin Change
- [ ] 0/1 knapsack
- [ ] Unbounded knapsack
- [ ] Subset Sum
- [ ] Longest Common Subsequence
- [ ] Longest Increasing Subsequence
- [ ] Edit Distance
- [ ] Matrix Chain Multiplication
- [ ] Partition DP
- [ ] State-machine DP
- [ ] Interval DP
- [ ] Tree DP
- [ ] Bitmask DP

### 17. Bit manipulation

- [ ] Bitwise AND, OR, XOR, and NOT
- [ ] Left and right shifts
- [ ] Bit masks
- [ ] Check, set, clear, and toggle a bit
- [ ] Count set bits
- [ ] Brian Kernighan's algorithm
- [ ] Power-of-two checks
- [ ] XOR techniques
- [ ] Bitmask subset enumeration

### 18. Number theory and mathematics

- [ ] Euclidean algorithm and GCD
- [ ] Extended Euclidean algorithm
- [ ] LCM
- [ ] Sieve of Eratosthenes
- [ ] Prime factorization
- [ ] Modular arithmetic
- [ ] Modular exponentiation
- [ ] Modular inverse
- [ ] Basic probability for algorithms
- [ ] Expected value and indicator variables
- [ ] Linear algebra for algorithms

### 19. Range-query data structures

- [ ] Segment tree
- [ ] Lazy propagation
- [ ] Fenwick tree / Binary Indexed Tree
- [ ] Sparse table
- [ ] Range-query techniques
- [ ] Interval tree

### 20. Computational geometry

- [ ] Points, vectors, and orientation
- [ ] Cross product
- [ ] Line-segment intersection
- [ ] Point-in-polygon
- [ ] Convex hull
- [ ] Graham scan
- [ ] Monotonic chain
- [ ] Closest pair of points

### 21. Randomized algorithms

- [ ] Fisher-Yates shuffle
- [ ] Reservoir sampling
- [ ] Randomized quicksort
- [ ] Randomized quickselect
- [ ] Monte Carlo algorithms
- [ ] Las Vegas algorithms
- [ ] Expected complexity and probability of failure

### 22. Caching and replacement policies

- [ ] LRU cache
- [ ] LFU cache
- [ ] FIFO replacement
- [ ] Clock / second-chance algorithm

### 23. Compression

- [ ] Run-length encoding
- [ ] Huffman coding
- [ ] LZ77
- [ ] LZ78
- [ ] LZW

### 24. Parsing, compilers, and automata

- [ ] Lexing and tokenization
- [ ] Recursive-descent parsing
- [ ] Pratt parsing
- [ ] Shunting-yard algorithm
- [ ] LL parsing
- [ ] LR parsing
- [ ] LALR parsing
- [ ] Regular expressions and finite automata
- [ ] Thompson's construction
- [ ] DFA minimization
- [ ] Abstract syntax trees
- [ ] Type-checking basics

### 25. Operating systems, concurrency, and memory

- [ ] FCFS scheduling
- [ ] Shortest Job First
- [ ] Round Robin scheduling
- [ ] Priority scheduling
- [ ] Earliest Deadline First
- [ ] FIFO, LRU, and Clock page replacement
- [ ] Mutexes and semaphores
- [ ] Deadlocks and deadlock detection
- [ ] Reference counting
- [ ] Mark-and-sweep garbage collection
- [ ] Mark-and-compact garbage collection
- [ ] Copying garbage collection
- [ ] Generational garbage collection

### 26. Databases and storage

- [ ] B-tree and B+ tree operations
- [ ] External merge sort
- [ ] Nested-loop join
- [ ] Hash join
- [ ] Sort-merge join
- [ ] LSM-tree compaction
- [ ] Write-ahead logging basics
- [ ] Bloom-filter indexing

### 27. Distributed systems

- [ ] Consistent hashing
- [ ] Rendezvous hashing
- [ ] Lamport logical clocks
- [ ] Vector clocks
- [ ] Gossip protocols
- [ ] Raft consensus
- [ ] Paxos
- [ ] Replication and quorum basics

### 28. Numerical algorithms

- [ ] Bisection method
- [ ] Newton-Raphson method
- [ ] Gaussian elimination
- [ ] LU decomposition
- [ ] Numerical integration
- [ ] Fast Fourier Transform
- [ ] Gradient descent
- [ ] Numerical stability and floating-point error

### 29. Security and cryptographic foundations

- [ ] Cryptographic hash functions
- [ ] Symmetric encryption concepts
- [ ] Public-key cryptography concepts
- [ ] Digital signatures
- [ ] Key-exchange concepts
- [ ] Password hashing and salts
- [ ] Secure random-number generation

### 30. Algorithmic theory

- [ ] P versus NP
- [ ] NP problems
- [ ] NP-hard and NP-complete problems
- [ ] Polynomial-time reductions
- [ ] Approximation algorithms
- [ ] Online algorithms
- [ ] Heuristics and tradeoffs

## Pi language learning track

Learn more about the language in the [Pi programming language repository](https://github.com/rolandbrake/pilang).

Each completed topic should teach at least one Pi feature. The examples should gradually introduce Pi instead of assuming readers already know it.

### Beginner Pi concepts

- [ ] Values, variables, and expressions
- [ ] Functions and return values
- [ ] Conditionals and loops
- [ ] Arrays, tuples, and indexing
- [ ] nil and failure results
- [ ] Ranges and iteration
- [ ] Basic modules and imports

### Intermediate Pi concepts

- [ ] Recursion
- [ ] Nested functions and closures
- [ ] Higher-order functions
- [ ] Mutable data structures
- [ ] Custom data types
- [ ] Generics or reusable interfaces
- [ ] Error handling
- [ ] Iterators and lazy sequences
- [ ] Testing and assertions
- [ ] Benchmarking

### Advanced Pi concepts

- [ ] Memory representation
- [ ] References and ownership, if supported
- [ ] Garbage-collection internals
- [ ] Concurrency primitives
- [ ] Parser and AST implementation
- [ ] FFI or interoperability
- [ ] Performance profiling

## Recommended implementation format

Every algorithm should have a short page or section containing:

1. **Problem**  what the algorithm solves.
2. **Idea**  an intuitive explanation.
3. **Pi concepts**  the language features demonstrated.
4. **Implementation**  readable Pi code.
5. **Correctness**  an invariant, proof sketch, or justification.
6. **Complexity**  time and space complexity.
7. **Edge cases**  empty input, duplicates, invalid input, and large input.
8. **Tests**  normal, boundary, and adversarial cases.
9. **Alternatives**  when another algorithm is preferable.
10. **Benchmark**  where performance comparisons are meaningful.

Suggested repository layout:

~~~text
Algorithms/
├── README.md
├── 01 Foundations/
├── 02 Arrays/
├── 03 Sorting/
├── 04 Hashing/
├── 05 Linked Lists/
├── 06 Stacks/
├── 07 Trees/
├── 08 Balanced Trees/
├── 09 Strings/
├── 10 Graphs/
├── 11 Union Find/
├── 12 Shortest Paths/
├── 13 Network Flow/
├── 14 Recursion/
├── 15 Greedy/
├── 16 Dynamic Programming/
├── 17 Bit Manipulation/
├── 18 Number Theory/
├── 19 Range Queries/
├── 20 Geometry/
├── 21 Randomized/
├── 22 Caching/
├── 23 Compression/
├── 24 Parsing/
├── 25 Operating Systems/
├── 26 Databases/
├── 27 Distributed Systems/
├── 28 Numerical/
├── 29 Security/
├── 30 Theory/
├── 31 Pi Language/
├── Projects/
├── Tests/
└── Benchmarks/
~~~

## Quality standards

- Prefer clear, idiomatic Pi over compressed code.
- Keep explanations next to the implementation they describe.
- State assumptions explicitly, such as sorted input or non-negative edge weights.
- Test empty, singleton, duplicate, negative, and very large inputs where applicable.
- Include both a straightforward and an optimized implementation when the contrast teaches something important.
- Do not hide complexity inside library calls without explaining the underlying operation.
- Record Pi-specific limitations or implementation details honestly.
- Use benchmarks to support claims, not to replace complexity analysis.


This roadmap is intentionally larger than the first version of the project. Implement it incrementally, and make each completed section useful reference material rather than merely a checklist.
