# Data-Structure-Learning
the implemention of data structures in java

Info: try to learn the data structure and apply to normal algorithm with java.  
Refer to the book -- **Fundamentals of Data Structure in C**
  
## Chapter 1
Attention: the most important thing, in this chapter, is the difference between iteration and recursive.  
1. Selection sort  
2. Binary search: iteration and recursive  
3. Permutation  
4. **Magic square**  

## Chapter 2
Attention: in this chapter, how to define ADT and how to realise it by java will be learned. Especially, I just accomplish  
the ADT of sparse polynomial and sparse matrix by array list. Then I will give the method, by linked list, to finish them  
in the next chapter. Finally, pattern matching algorithm for string will be introduced.
1. Sparse polynomial  
2. Sparse matrix  
3. Pattern Matching & KMP pattern matching algorithm  

## Chapter 3  
Attention: in this chapter, to learn the ADT of stack and queue, and using array list to accomplish them.
1. Stack  
2. Queue & Circular queue  
3. **the problem of maze**

## Chapter 4  
Attention: in this chapter, to introduce the linked list, and to re-accomplish stack, queue, polynomial, and matrix by linked
list. In addition, learning to use inner class to construct node class.
1. linked natural number  
2. dynamic linked stack  
3. dynamic linked queue  
4. linked polynomial  
5. linked-list's utility & circular-list's utility  
6. two-way linked list  
7. equivalence relation  
8. linked matrix  

## Chapter 5  
Attention: in this chapter, to learn the tree and try to use generics programming. As binary tree, you should pay more attention on
the ordering -- preorder, inorder, postorder and level-order. The thread tree make full use of **NULL** node to order the tree as list.
The heap is mainly used to sort the array. The binary search tree can search the given key by half-hold. The selection tree can sort the massive data by IO. 
1. binary tree  
2. thread binary tree: **preorder**, inorder and **postorder** thread binary tree  
3. heap: max heap & min heap  
4. binary search tree  
5. **selection tree**  
6. forest: equivalence class  

## Chapter 6  
Attention: in this chapter, to learn the graph and to focus on dfs & bfs. And I find that the part of biconnected graph, in the book -- page 278-279, has some errors, for example coding 6-4 & 6-6. The articulation point and biconnected component is caclulating by graph but not the spanning tree of graph. Then, to introduce the application of graph -- minimum cost spanning tree & the shortest path & activity network.     
1. graph: dfs & bfs & spanning tree  
2. biconnected component: articulation point & biconnected graph  
3. minimum cost spanning tree: greedy algorithm -- Kruskal & Prim & **Sollin**  
4. the shortest path and transitive closure: dijkstra & allcosts algorithm  
5. AOV: topological order
6. AOE: earliest time & latest time  

## Chapter 7  
Attention: in this chapter, to pay more attention on sorting. Effective sorting method can obviously improve the speed of searching and verifying.  
1. search & verify
2. internal sort: insertion sort & quick sort & merge sort & radix sort  
3. external sort: merge k sorted arrays  

## Chapter 8
Attention: in this chapter, to focus on hashing. Hashing includes static hashing and dynamic hashing. Static hashing's application scenario is that hash-entry can be loaded to memory, but hash-entry of dynamic hashing can not be totally loaded to memory. As for handleing overflow or collision, linear open addressing & chainging can be applied to static hashing and directory & deirectoryless hashing can be used in dynamic hashing. Finally, I think, when using hahsing, that how to get uniform hash funciton is very important.  
1. symbol table  

## Chapter 9
Attention: to focus on heap structure. Min-max heap & double-ended heap can support double-ended priority queue. And they can realize by array. Height-biased leftist tree, by linked list, can not only support the basic operations of double-ended priority queue, but also support combination of two double-ended priority queues. Binomial heap optimizes the height-biased leftist tree, and fibonacci heap expands binomial heap.  
1. **min-max heap**  
2. **deap(double-ended heap)**  
3. **height-biased leftist tree**  
4. **binomial heap**  
5. **fibonacci heap**  

## Chapter 10  
Attention: in this chapter, to pay more attention on search structure.In order to balance the height of binary tree, AVL tree, by LL & LR & RR & RL rotating, is the complete binary tree. 2-3 & 2-3-4 tree simplify the inserting and deleting operations of AVL tree. Red-black tree is the binary-tree form of 2-3-4 tree. B tree is mainly used to search elements by IO.  
1. **AVL tree**  
2. **2-3 & 2-3-4 tree**  
3. **red-black tree**  
4. **B tree**  
5. **splay tree**  
6. **digital search tree**  
7. **trie**  
