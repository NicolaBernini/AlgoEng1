
# Overview 

The Sorting Algorithms are aimed at performing a Semantically Oriented Data Organization using 
- the Semantic provided by a Comparison Operator 
- the Position exchange provided by a Switch Operator 

In a pairwise paradigm, these operators are binary and could be designed as follows 
```cpp
template <typename T>
bool isLess(const T& a, const T& b);                                          ///< Comparison Operator 


template <typename Container_T, Index_T>
void switch(Container_T& container, const IndexT& t1, const Index_T& t2)      ///< Exchanges the Position of the Elements in the Container 

```
