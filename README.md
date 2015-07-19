#Word2Vec

======

C++ version of google [word2vec](http://code.google.com/p/word2vec/)

=====

### Requirements

* C++11
* Eigen
* OpenMP (for multithread)

### Build

g++ -I/usr/include/eigen3 -fopenmp -std=c++11 -o w2v main.cpp Word2Vec.cpp

### Running

./w2v