![AITU](https://static.tildacdn.com/tild3764-6633-4663-b138-303730646233/aitu-logo__2.png)
# Assignment 2
## **Zhanbyrbai Zhigitali** (*SE-2202*) 

### MyList (Interface)
- ```size()```- Returns the number of elements in the list.
- ```contains(Object o)```- Returns true if the list contains the specified object.
- ```add(T item)```- Adds the specified element to the end of the list.
- ```add(T item, int index)```- Inserts the specified element at the specified position in the list.
- ```remove(T item)```- Removes the first occurrence of the specified element from the list, if it is present.
- ```remove(int index)```-  Removes the element at the specified position in the list and returns it.
- ```clear()```-  Removes all elements from the list.
- ```get(int index)```- Returns the element at the specified position in the list.
- ```indexOf(Object o)```- Returns the index of the first occurrence of the specified element in the list, or -1 if the list does not contain the element.
- ```lastIndexOf(Object o)```-  Returns the index of the last occurrence of the specified element in the list, or -1 if the list does not contain the element.
- ```sort()```- Sorts the elements of the list in ascending order.
### MyArrayList (Class)
- ```increaseBuffer()```- Increases the capacity of the list by doubling its current size.
- ```swap(Object[] arr, int i, int j)```- Swaps the elements at the specified positions in the list.
- implements the  MyList (Interface).
- The list is iterable using the Iterable interface.
### MyLinkedList (Class)
- ```removeNode(MyNode node)```-  Removes the specified node from the list.
- The list is iterable using the Iterable interface.
### Main (Class)
- Tests all methods of MyArrayList and MyLinkedList using both <Integer> and <String> data types.

