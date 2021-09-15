# Assignment: Heaps using Comptency-Based Grading

**NOTE:** This is an abridged version of the lab handout, to see the full version, [please visit the course site](https://vcc-csc212.github.io/sp21-archive/lab11/).

#### Motivation (Why are we doing this?) {#motivation}
The goal of this lab is to provide background on `Heaps`. 

---

#### Background Info {#bgi}

Please [see full lab handout](https://vcc-csc212.github.io/sp21-archive/lab11/) for this section.

---

#### Your Task {#task}

Similar to last week's lab, we give you a makefile, a unit test file, a doctest header file and a header file with class definitions for `HeapNode` and `HeapTree` classes (plus a couple other things). 
We have supplied ```heap.cpp``` to house your class definitions, and `test.cpp` will serve as your main file. 

- [heap.h](https://vcc-csc212.github.io/sp21-archive/labs/lab-11/template-code/heap.h)
- [heap.cpp](https://vcc-csc212.github.io/sp21-archive/labs/lab-11/template-code/heap.cpp)
- [test.cpp](https://vcc-csc212.github.io/sp21-archive/labs/lab-11/template-code/test.cpp)
- [doctest.h](https://vcc-csc212.github.io/sp21-archive/labs/lab-11/template-code/doctest.h)
- [makefile](https://vcc-csc212.github.io/sp21-archive/labs/lab-11/template-code/makefile)

---

#### Requirements {#reqs}
Your goal for this lab is to complete the following tasks **in order**:

1. Diagram the following operations for a min heap:
   - insert: 5, 3, 7, 2 , 4, 6, 8
   - remove_min
   - delete: 4
2. Implement 'min_heapify()', 'find_last()', 'remove_min()', and 'delete_element()'
3. Copy your entire solution to a new Directory, and modify everything to create a max_heap
   - You will need to re-do the test cases in `test.cpp`!

---

#### Handing in {#submit}
Please call a TA over to get checked off before leaving your lab section (regardless of how far you got). If you want to continue working on your lab after your lab section, come to hours to get checked off.

---

#### Grade Breakdown {#grading}
This assignment covers `heaps` and `balanced trees` and your level of knowledge on them will be assessed as follows: 
- To demonstrate an `awareness` of these topics, you must:
    - Successfully meet [requirements](#reqs) **1**
- To demonstrate an `understanding` of these topics, you must:
    - Successfully meet [requirements](#reqs) **1 and 2**
- To demonstrate `competence` of these topics, you must:
    - Successfully meet [requirements](#reqs) **1 through 3**