# Module 04 - Sorted Linked List
For the Module 04 project, the task was to leverage the built in Java utilities to create a Linked List that takes in a set of integers from the user and returns a Linked List that has been sorted in ascending order.

## Running Instructions
Running this program requires compilation of the .java file first using
```
javac SortedLinkedList.java
```
After compilation, the program can be run using:
```
java SortedLinkedList
```

## Software Documentation
The recommended way to view the documentation for this particular program is to leverage javadocs:
```
javadoc -d doc -private SortedLinkedList.java
```

Then, you can navigate to the doc/index.html file to view the detailed documentation.

## Providing Integers
The instructions in the progam ask for integers followed by the word "done" to indicate the end of the numbers to read. It will not accept non-integer values. This list can be in a space separated list such as:
```
1 2 5 3 2 6 4 7 1 done
```
Or can be separated by hitting `enter` between each integer:
```
1
2
3
5
3
2
5
4
done
```

## Example Usage and Output
Consider the following input:
```
1 2 3 4 3 2 1 5 3 4 5 234 done
```
You will receive the following output:
```
Sorted Stack: [1, 1, 2, 2, 3, 3, 3, 4, 4, 5, 5, 234]
```
**NOTE:** placing "done" early will prevent the program from reading any numbers after that "done" indictator. Consider this input:
```
1 2 3 4 3 2 1 5 3 4 5 234 done 39999 3993209324089 482903840283 
```
You will receive the following output:
```
Sorted Stack: [1, 1, 2, 2, 3, 3, 3, 4, 4, 5, 5, 234]
```

Notice how the items after done are not considered.
