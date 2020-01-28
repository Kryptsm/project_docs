

## Project Description
Implement a custom memory manager in C++ that compares the performance/efficiency of three different allocation strategies/algorithms:
    1. **Best Fit** - The allocator chooses the smallest area of memory that is available that is large enough for the desired allocation.
    2. **First Fit** - The allocator chooses the first area of memory that is of sufficient size for the desired allocation 
    3. **Custom Designed** - The algorithm chooses a location for the allocation based on a scheme you design yourself. 

The custom allocator should overload the `new`, `new[]`, `delete`, `delete[]` operators as well as any other versions of those operators you see fit.  They should be overloaded at the global scope.  

The allocation and deallocation operators should make use of a custom Allocator class whose functionality is exposed through an `AllocatorSingleton` object using the [Singleton Design Pattern](https://en.wikipedia.org/wiki/Singleton_pattern).  
    

## Deliverables

### Analysis Paper

- 
