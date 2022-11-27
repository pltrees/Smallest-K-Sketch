# Words Dataset
The Words dataset contains 2,702 samples, and each instance is a word count in 2^16 different documents. In the other word, each data point is a 2^16 dimensional vector representing the number of occurrences of an English word in a repository of 2^16 documents. 
The word vectors are in the directory `words`. Each file is a word vector in a two-column sparse representation: the first column is the vector value (the number of occurrences) and the second column is the vector index.

## Citation Request
When you use Words in your paper, please cite
```
[EMNLP'05](https://aclanthology.org/H05-1089.pdf)
@inproceedings{DBLP:conf/naacl/LiC05,
  author    = {Ping Li and
               Kenneth Ward Church},
  title     = {Using Sketches to Estimate Associations},
  booktitle = {{HLT/EMNLP} 2005, Human Language Technology Conference and Conference
               on Empirical Methods in Natural Language Processing, Proceedings of
               the Conference, 6-8 October 2005, Vancouver, British Columbia, Canada},
  pages     = {708--715},
  year      = {2005},
}

```
Examples of recent papers which used this dataset include: 
```
[Commun. ACM](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/CACM_hashing.pdf)
@article{DBLP:journals/cacm/LiK11,
  author    = {Ping Li and
               Arnd Christian K{\"{o}}nig},
  title     = {Theory and applications of \emph{b}-bit minwise hashing},
  journal   = {Commun. {ACM}},
  volume    = {54},
  number    = {8},
  pages     = {101--109},
  year      = {2011},
}

[KDD'15](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.1089.5968&rep=rep1&type=pdf)
@inproceedings{DBLP:conf/kdd/Li15,
  author    = {Ping Li},
  title     = {0-Bit Consistent Weighted Sampling},
  booktitle = {Proceedings of the 21th {ACM} {SIGKDD} International Conference on
               Knowledge Discovery and Data Mining, Sydney, NSW, Australia, August
               10-13, 2015},
  pages     = {665--674},
  year      = {2015},
}

[NeurIPS'19](https://proceedings.neurips.cc/paper/2019/file/9f067d8d6df2d4b8c64fb4c084d6c208-Paper.pdf)
@inproceedings{DBLP:conf/nips/LiLZ19,
  author    = {Ping Li and
               Xiaoyun Li and
               Cun{-}Hui Zhang},
  title     = {Re-randomized Densification for One Permutation Hashing and Bin-wise
               Consistent Weighted Sampling},
  booktitle = {Advances in Neural Information Processing Systems 32: Annual Conference
               on Neural Information Processing Systems 2019, NeurIPS 2019, December
               8-14, 2019, Vancouver, BC, Canada},
  pages     = {15900--15910},
  year      = {2019},
}

[WWW'21](https://dl.acm.org/doi/abs/10.1145/3442381.3449955)
@inproceedings{DBLP:conf/www/LiLSZ21,
  author    = {Ping Li and
               Xiaoyun Li and
               Gennady Samorodnitsky and
               Weijie Zhao},
  title     = {Consistent Sampling Through Extremal Process},
  booktitle = {{WWW} '21: The Web Conference 2021, Virtual Event / Ljubljana, Slovenia,
               April 19-23, 2021},
  pages     = {1317--1327},
  year      = {2021},
}

[AAAI'21](https://ojs.aaai.org/index.php/AAAI/article/view/16543)
@inproceedings{DBLP:conf/aaai/Li021,
  author    = {Xiaoyun Li and
               Ping Li},
  title     = {Rejection Sampling for Weighted Jaccard Similarity Revisited},
  booktitle = {Thirty-Fifth {AAAI} Conference on Artificial Intelligence, {AAAI}
               2021, Thirty-Third Conference on Innovative Applications of Artificial
               Intelligence, {IAAI} 2021, The Eleventh Symposium on Educational Advances
               in Artificial Intelligence, {EAAI} 2021, Virtual Event, February 2-9,
               2021},
  pages     = {4197--4205},
  year      = {2021},
}
```
