# Datastructures

## Datastructures:definition
***
1. A data structure is a specialized format for organizing, processing, retrieving and storing data.
2. Any of the methods or formats (such as an array, file, or record) for organizing data in a computer
3. A data structure is a storage that is used to store and organize data.
4. Data Structure can be defined as the group of data elements which provides an efficient way of storing and organising data in the computer so that it can be used efficiently. 

## What are the 4 forms of data structure
***
1. Linear: arrays, lists
2. Tree: binary, heaps, space partitioning etc.
3. Hash: distributed hash table, hash tree etc
4. Graphs: decision, directed, acyclic etc. 


## Stack 

> Last In First Out and First In Last Out.
> Insertion and deletion happens on same end.

***
Basic operations on stack
1. **push()** - To insert an element into the stack.
2. **pop()** - To remove an element from the stack.
3. **top()** - To Return the top element of the stack.
4. **isEmpty()** - To return true is stack is empty else false.
5. **size()** - Returns the size of stack

### Push
Adds an item in to the stack, if the stack is full it is said to be overflow

```
Begin
if stack is full
return 
end if
else
increment top
stack[top] assign value
end else
end procedure
```

### Pop
Removes an item from the stack, if the stack is empty it is said to be underflow

```
Begin
if stack is empty
return
else
print stack[top]
decrement top
return value
end else
end procedure
```
### Top
Returns the top element of the stack
```
begin
return stack[top]
end procedure
```
