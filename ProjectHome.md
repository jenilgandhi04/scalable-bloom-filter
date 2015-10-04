This project is a java implementation of Scalable Bloom Filters as discussed in [Scalable Bloom Filters](http://asc.di.fct.unl.pt/~nmp/pubs/ref--04.pdf).

To have k hash-function, I refer to Adam Kirsch and Michael Mitzenmacher who wrote a paper entitled [Less hashing, same performance: Building a better Bloom filter](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.152.579&rep=rep1&type=pdf) in which it is shown that we only need two hash functions, since we can derive as many hash values as we need as a linear combination of two without compromising the performance of a Bloom filter.