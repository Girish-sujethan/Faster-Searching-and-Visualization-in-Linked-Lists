# Faster Searching in Linked Lists and Linked List Visualization
Part 1 creates three heuristics for linked lists. Heuristic 1 (move to front), Heuristic 2 (swap), and Heuristic 3 (count). Part 2 is an interactive visualization using pygame for our linked list data.

__Heuristic 1__ (move to front): move the item being searched for to the front of the list. (Do nothing if the item is already at the front of the list.)

__Heuristic 2__ (swap): swap the item being searched for with the item immediately before it. (Do nothing if the item is already at the front of the list.)

__Heuristic 3__ (count): have each node keep track of the number of times its item has been searched for, and sort the nodes in non-increasing count order. When we search for an item in the list, increase its count by 1, and then move its node so that it is before all items with a smaller count, but after all items with a greater or equal count. The order of the other items does not change.


![Visualization](https://github.com/Girish-sujethan/Faster-Searching-and-Visualization-in-Linked-Lists/blob/main/a1_part2.gif)
