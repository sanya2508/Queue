# Queue
 * Data structure that follows FIFO.
 * Linear data strucutre.
 * Basic opetaions: 
   * Enqueue.
   * Dequeue.
   * Empty
   * Full
   
   
 * Applications:
   * Operating system algorithms.
   * Async. data transfer.
   
<hr/>

## Types of implementation of queue
 * <a href="https://github.com/sanya2508/Queue/blob/master/circularImplementation.cpp">Circular array based</a>
 * <a href="https://github.com/sanya2508/Queue/blob/master/linkedlistImplementation.cpp">Linked list based</a>
 
<hr/>

## <a href="https://github.com/sanya2508/Queue/blob/master/maxElementInWindowOfSizeK.cpp">Maximum element in every window  of size k</a>
* Implemented using `deque` data structure.

      Double ended queues are sequence containers with the feature of expansion and contraction on both the ends.
      
 * Using concept of sliding window.

<hr/>

## <a href="https://github.com/sanya2508/Queue/blob/master/firstNonRepeatingCharacterInAStream.cpp">First non repeating character in a stream.</a>

<hr/>

## Stack using Queue
 * ### Push Efficient
    * Take two queue primary and secondary.
    * push: directly call enqueue on primary queue.
    * pop: pop the primary queue till the point the size of queue becomes one. push the popped element in the secondary queue.
    * swap the namings of the primary and secondary array.
    
 * ### Pop Efficient
    * Take two queue primary and secondary.
    
    
<hr/>

## Queue using Stack
 * ### Enqueue Efficient
    * Take two stacks primary and secondary.
  
