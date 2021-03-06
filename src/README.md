src
###

There are 6 folders contained within the src folder, dist, func, opt, rl, shared, and util.

 - dist
    - a collection of distribution functions
        - Discrete Dependency Tree (for MIMIC)
        - Discrete Distribution
        - Fixed Component Mixture Distribution
        - Mixture Distribution
        - Multivariate Gaussian Distribution
        - ...
 - func
    - a collection of functions and tools for classification and clustering
    - classifications
        - decision trees (with multiple forms of pruning and rating)
        - decision stumps (for boosting)
        - adaboost
        - KDTrees (for use with K-NN) for efficiency
        - K-nearest neighbor
        - support vector machines
            - a number of common kernel functions
        - neural networks (with backprop)
    - clustering
        - k-means
        - expectation-maximization
 - opt
    - a collection of randomized optimization algorithms and supporting functions
    - Simulated Annealing
    - Randomized Hill Climbing
    - Genetic Algorithms (ga)
    - MIMIC
    - Interfaces for evaluation and neighbor functions
 - rl
    - a collection of reinforcement learning algorithms
        - QLambda
        - Sarsa Lambda
 - shared
    - functions and tools shared between multiple tools
    - filters
        - ICA
        - PCA
        - ...
    - Distance and error functions
        - Euclidian Distance
        - Hamming Distance
        - SSE
        - DataSet and DataSetDescription
        - Instance
        - ...
 - util
    - a collection of utility functions
    - maxHeap
    - ABIGAILArrays, an array utility class
        - printing
        - partitioning
        - searching
        - sorting (why?!?...Arrays.sort exists)
    - graph algorithms
        - Kruskals
        - DFS
    - linear algebra utility functions
        - Decompositions (LU, QR, Cholesky, SVD, Bidiag, Tridiag, RealSchur, Hessenberg)
        - lower-, upper-, triangular etc. matrices

