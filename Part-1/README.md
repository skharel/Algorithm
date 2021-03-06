# [Introduction to Algorithm](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/)

# [Lecture notes](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/lecture-notes/)

# [Lecture videos](https://www.youtube.com/watch?v=HtSuA80QTyo&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)

# [Recitation videos](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/recitation-videos/)

- Links to recitation handouts: in every recitation video in MIT website, there is section recitation notes which has the handouts + notes + codes

![recitation notes](extras/recitation-notes.png)

# [Assignment problems with solutions](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/assignments/)

# [Programming assingment with solutions](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/assignments/)

# [Exam with solutions](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/exams/)

# Section notes

## [Chapter 2. Getting Started](./2) - Lecture 3

- [Insertion sort](https://youtu.be/Kg4bqzAqRBM?list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&t=606)
  - Binary Insertion sort - Insertion sort where you find correct position using binary search
- [Merge Sort](https://youtu.be/Kg4bqzAqRBM?list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&t=1485)

## [Chapter 6. Heapsort](./6) - Lecture 4

- [Priority Queues](https://youtu.be/B7hVxCmfPtM?list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&t=120)
- [Heaps](https://youtu.be/B7hVxCmfPtM?list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&t=375)
  - [Heap As a tree](https://youtu.be/B7hVxCmfPtM?list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&t=562)
  - [Max and Min heap](https://youtu.be/B7hVxCmfPtM?list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&t=630)
  - [Heap operations](https://youtu.be/B7hVxCmfPtM?list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&t=1000)
  - [max_heapify & complexity analysis](https://youtu.be/B7hVxCmfPtM?list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&t=1192)
  - [build max_heap & complexity analysis](https://youtu.be/B7hVxCmfPtM?list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&t=1799)
- [Heap sort](https://youtu.be/B7hVxCmfPtM?list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&t=2883)

## Chapter 10 & 12 - Lecture 5

- 10.4: Representing rooted trees
- 12: Binary Search Trees

# Lecture comments

> L: means lecture video;

> R: means recitation video

1. R1

   - covers O, ?? & ?? analysis
   - Example of Asymptotic analysis for multiple random functions
   - `Important to understand how to analyze; what matters and what can be dropped`

2. L2
   - Covers the model of computation which helps in thinking about what to look for when analyzing cost
   - `cost of algorithm = sum of cost`
   - Algorithm taught: `Document Distance`
     - Applications: find similar documents, detect duplicates and plagiarism
     - Idea: compare documents and quantify the similarity
   - `Important to understand in order to really understand how to compute cost of algorithm`

# Algorithms & Complexity tables

| ??????????????????Algorithm                                     | ??????????????????????????????????????????????????????Runtime |
| --------------------------------------------------- | ------------------------- |
| Insertion sort:                                     |                           |
| &nbsp;??????With Pairwise swaps                         | O(n<sup>2</sup>)          |
| &nbsp;??????With Binary search (Binary insertion sort ) |                           |
|                                                     | comparisons: O(n log n)   |
|                                                     | swaps: O(n<sup>2</sup>)   |
| Merge Sort                                          | O(n log n)                |
| Heaps:                                              |                           |
| &nbsp;??????Build Max Heap                              | O(n)                      |
| &nbsp;??????max_heapify                                 | O(log n)                  |
| &nbsp;??????Heap Sort                                   | O(n log n)                |

## Strongly recommended to watch again:

- [R1](https://www.youtube.com/watch?v=P7frcB_-g4w)
- [L2](https://www.youtube.com/watch?v=Zc54gFhdpLA&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
