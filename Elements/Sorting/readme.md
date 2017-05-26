
# Overview 

The Sorting Algorithms are aimed at performing a Semantically Oriented Data Organization using 
- the Semantic provided by a Comparison Operator 
- the Position exchange provided by a Switch Operator 

In a pairwise paradigm, these operators are binary and could be designed as follows 
```cpp
template <typename T>
bool isLess(const T& a, const T& b);                                          ///< Comparison Operator 


template <typename Container_T, Index_T>
void switch(Container_T& container, const IndexT& t1, const Index_T& t2);      ///< Exchanges the Position of the Elements in the Container 

```
The additional elements that have been introduced are 
- the `Container_T` which represents the Container for the Items to be sorted and 
- the `Index_t` which represents the Index to uniquely identify an element in the Container 


The Comparison Operator could be used to check the Container is actually sorted 

