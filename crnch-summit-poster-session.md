# CRNCH Summit Poster Session
The CRNCH Student Poster Session will be held on February 8th, 2024 from 4:40 - 6 PM. We are excited to have a large number of posters from our CRNCH students, and we also are thrilled to be able to feature the work of some of our [CRNCH PhD Fellowship winners](https://crnch.gatech.edu/content/crnch-fellowship).

We note that in some cases, we have not linked posters due to work being under submission or at the presenter's request. 

### 2023-2024 Fellowship Winners

| Student Presenter, Student Authors | Poster Title | Advisor(s) | GT Department | [Poster] [Abstract] |
| ---------------------------------- | ------------ | ---------- | -------------|-------------------|


| Student Presenter, Student Authors | Poster Title | Advisor(s) | GT Department | [Poster] [Abstract] |
| ---------------------------------- | ------------ | ---------- | -------------|-------------------|
| Yongnuo Yang, Jeremy Wang, Alexander Contratti | Efficiency and Parallelism on the Lucata Pathfinder with the HPCG Benchmark | Jeffrey Young, Aaron Jezghani | ECE, SCS | [Poster]() [Abstract](#yy) |


## Student Abstracts:

<a id="yy">**Yongnuo Yang, Jeremy Wang, Alexander Contratti - "Efficiency and Parallelism on the Lucata Pathfinder with the HPCG Benchmark"**</a>

In a post-Moore era of computing, near-memory architecture offers an alternative path for continuing to improve processor performance. By placing compute elements closer to memory and forgoing a cache hierarchy, near-memory systems address the memory wall problem, where a large disparity exists between processor speed and memory access. The Lucata Pathfinder platform is a multi-node, massively multithreaded system that uses lightweight migratory threads across a Partitioned Global Address Space such that every memory access occurs locally. It is especially well suited for applications involving sparse matrices, where caches struggle, such as the High Performance Conjugate Gradient (HPCG) benchmark. HPCG applies the Conjugate Gradient algorithm to a generated problem and consists of four main mathematical operations: dot product (DDOT), weighted vector sum (WAXPBY), sparse matrix-vector multiplication (SPMV), and the symmetric Gauss-Seidel method (SYMGS). Through program runs on the Pathfinder and emusim, a simulated environment for the Pathfinder, the performance and parallelization of the system are assessed for each of the operations and the benchmark as a whole. The Pathfinder achieves good utilization and load distribution for smaller problem sizes of HPCG. Further work is being done for larger problem sizes to test the scalability and power efficiency of the system.
