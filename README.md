# Conditional Random Sampling (CRS), a.k.a. Smallest-K Sketch (The work in 2005) 

For sparse data, the inverted index is routinely used. To improve efficiency and storage, we directly sample the front of each inverted index vector, hence the name "Small-K Sketch" although the "K" does not need to be the same for each vector. In the estimation stage, for any pair (or any group) of sketches, we can retrospectively construct a uniform random sample for that pair (or group). With a random sample, one can use it to compute any similarities and summary statistics. Therefore, it is a "one-sketch-for-all" scheme. 

The drawback of this scheme is that the sample size differs for each pair (group) and hence it can not be used for directly building large-scale learning models and hash tables for sub-linear time approximate near neighbor search. On the other hand, there are plenty applications which can benefit from this method, for example, computing similarities within HNSW or during the re-ranking stage of ANN methods. 

# 2005 Words Dataset
The Words dataset contains 2,702 samples, and each instance is a word count in 2^16 different documents. In the other word, each data point is a 2^16 dimensional vector representing the number of occurrences of an English word in a repository of 2^16 documents. 
The word vectors are in the zipped file `words.zip`. Each file is a word vector in a two-column sparse representation: the first column is the vector value (the number of occurrences) and the second column is the vector index.

## Reference for the Words dataset
* Ping Li and Kenneth Church. [Using Sketches to Estimate Associations](https://aclanthology.org/H05-1089.pdf). EMNLP 2005.

## Recent Papers which used this dataset
* Xiaoyun Li and Ping Li. [C-MinHash: Improving Minwise Hashing with Circulant Permutation](https://proceedings.mlr.press/v162/li22m/li22m.pdf). ICML 2022.

# References for Conditional Random Sampling (CRS), a.k.a. Smallest-K Sketch 
* Ping Li, Kenneth Church, and Trevor Hastie. [One Sketch For All: Theory and Application of Conditional Random Sampling](https://proceedings.neurips.cc/paper/2008/file/fe7ee8fc1959cc7214fa21c4840dff0a-Paper.pdf). NIPS 2008.
* Ping Li and Kenneth Church. [A Sketch Algorithm for Estimating Two-Way and Multi-Way Associations](https://direct.mit.edu/coli/article/33/3/305/1955/A-Sketch-Algorithm-for-Estimating-Two-Way-and). Computational Linguistics 2007.
* Ping Li, Kenneth Church, and Trevor Hastie. [Conditional Random Sampling: A Sketch-based Sampling Technique for Sparse Data](https://proceedings.neurips.cc/paper/2006/file/aa6b7ad9d68bf3443c35d23de844463b-Paper.pdf). NIPS 2006.
* Ping Li and Kenneth Church. [Using Sketches to Estimate Associations](https://aclanthology.org/H05-1089.pdf). EMNLP 2005.


