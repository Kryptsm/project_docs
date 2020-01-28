
# Memory Allocator

Project 1 - CS 3353 - Spring 202
Due: Feb YY, YYYY at YY:YY. 


## Project Description
Implement a custom memory manager in C++ that compares the performance/efficiency of three different allocation strategies/algorithms:
    1. **Best Fit** - The allocator chooses the smallest area of memory that is available that is large enough for the desired allocation.
    2. **First Fit** - The allocator chooses the first area of memory that is of sufficient size for the desired allocation 
    3. **Custom Designed** - The algorithm chooses a location for the allocation based on a scheme you design yourself. 

The custom allocator should overload the `new`, `new[]`, `delete`, `delete[]` operators as well as any other versions of those operators you see fit.  They should be overloaded at the global scope.  

The allocation and deallocation operators should make use of a custom Allocator class whose functionality is exposed through an `AllocatorSingleton` object using the [Singleton Design Pattern](https://en.wikipedia.org/wiki/Singleton_pattern).  The implementation of each allocation strategy should be through a subclass of Allocator.  Implementing the relationship between the allocator and its subclasses should be done using the [Strategy Design
Pattern](https://en.wikipedia.org/wiki/Strategy_pattern). Note: Allocator and AllocatorSingleton are different classes. 

-to add:
    - stress testing
        - frequency of allocation and deallocation
        - sizes of allocations
        - 
    - data collection
    - contrived stress vs. wild stress
    

## Deliverables

### Implementation 
- You should submit a complete implementation of your memory manager along with the relevant stress testing code.  
- Your code base should adhere to the following standards and guiding principles:
    1. To the extent possible, your code should be self documenting. 
    2. Use code documentation (comments) where needed to contextualize or otherwise explain challenging or dense blocks
       of code. 
    3. Your code should build without warnings when using the `-Wall` flag with g++. 

### Analysis Paper
Compose an analysis paper to include the following:
    - An introduction to the project in your own words. Include any hypotheses you have regarding the performance of the
      various strategies in different allocation environments or conditions. 
    - An explanation of your specific implementation of the three placement strategies. You may include pseudocode to
      help your explanation, but no code can be included.  
    - A detailed methodology of how you stress-tested your allocator and various strategies.  This should be in
      sufficient detail that another student in the class or Dr. Fontenot could reproduce your testing methodology
      absent your actual source code. 
    - Describe the results of your tests.  To the extent possible, use proper mathematical and statistical strategies
      for characterizing the data you collected. Graphs and tables are appropriate for this section.  Note that this should communicate what data was collected, but not veer
          into the analysis of the results. 
    - In narrative form, provide an analysis of results of the experiments. Other graphs and tables may be needed or you
      may refer to tables or graphs from results description. 
- 
