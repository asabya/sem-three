# Data Structure & Algorithm (PCC-CS301)

**Contact Hours:** 3L  
**Credits:** 3  
**Semester:** III

## Course Objectives
* To understand the fundamentals of abstract data types. [cite: 15]
* To learn the principles of both linear and nonlinear data structures. [cite: 15]
* To be able to build an application that utilizes sorting and searching algorithms. [cite: 15]

## Pre-Requisites
* CS 201 (Basic Computation and Principles of C). [cite: 15]
* M101 & M201 (Mathematics), along with the basics of set theory. [cite: 15]

## Examination Scheme

| Component | Marks |
|-----------|-------|
| Mid Semester Exam | 15 [cite: 15] |
| Assignment and Quiz | 10 [cite: 15] |
| Attendance | 5 [cite: 15] |
| End Semester Exam | 70 [cite: 15] |
| **Total** | **100** [cite: 15] |

## Syllabus

| Unit | Content | Hours/Unit |
|------|---------|-----------|
| 1 | Introduction to data structures, analysis of algorithms, Asymptotic Notations, Time-Space trade-off. Searching techniques: Linear and Binary Search with complexity analysis. [cite: 16] | 10 [cite: 16] |
| 2 | Stacks and Queues (ADT), operations, complexity analysis. Applications of Stacks: Expression conversion and evaluation. Types of Queues: Simple, Circular, Priority, and their operations. [cite: 16] | 9 [cite: 16] |
| 3 | Linked Lists (Singly, Doubly, Circular), operations, and complexity analysis. Linked representation of Stack and Queue. Trees (Binary, Threaded Binary, Binary Search, AVL, B Tree, B+ Tree), tree operations, and their analysis. [cite: 16, 19] | 10 [cite: 16] |
| 4 | Sorting algorithms (Selection, Bubble, Insertion, Quick, Merge, Heap), performance comparison. Hashing. Graph terminologies, representations, and traversal algorithms. [cite: 19] | 9 [cite: 19] |

## Course Outcomes
* PCC-CS301.1: Differentiate how the choice of data structures and algorithms impacts program performance. [cite: 22]
* PCC-CS301.2: Solve problems using different data structures and write corresponding programs. [cite: 23]
* PCC-CS301.3: Identify the most suitable data structure and algorithmic methods for solving a given problem. [cite: 24]
* PCC-CS301.4: Discuss the computational efficiency of major sorting, searching, and hashing algorithms. [cite: 25]
* PCC-CS301.5: Compare and contrast the benefits of dynamic versus static data structure implementations. [cite: 25]

## Unit 1 – Two-Week Curriculum (Designed for Below-Average Learners)

### Overview
Unit 1 spans **≈ 10 lecture hours**. We distribute the topics across **10 class-days (≈ 2 weeks)** to give struggling learners time for repetition and hands-on activities.

* **Theory (standard explanation)**  
* **ELI5 version (Explain-Like-I'm-Five)**  
* **Activities / practice**

| Week | Day | Topics |
|------|-----|--------|
| 1 | 1 | What is a Data Structure? ADT Concept |
|   | 2 | Real vs Abstract Data Types – Arrays & Lists Preview |
|   | 3 | Algorithm Analysis Steps & Measuring Time |
|   | 4 | Asymptotic Notations: Big-O, Θ, Ω |
|   | 5 | Time-Space Trade-off & Simple Loop Analysis |
| 2 | 6 | Searching Basics & Linear Search Algorithm |
|   | 7 | Binary Search Concept & Implementation |
|   | 8 | Recursion in Binary Search & Complexity Comparison |
|   | 9 | Empirical Timing with Code – Linear vs Binary |
|   | 10 | Integrated Mini-Project & Unit-1 Review |

---

### Detailed Daily Breakdown

#### Day 1 – What Is a Data Structure? ADT Concept
* **Theory:** Define data structures, need for organisation, difference between physical DS and Abstract Data Type (ADT); examples (Stack ADT).
* **ELI5:** "A data structure is like different kinds of boxes to keep toys—some boxes have dividers, some are bags—you pick the right one so toys are easy to find."
* **Activity:** Students group classroom objects into 'structures' (pile, ordered row, labelled shelves) and discuss pros/cons.
* **Homework:** List 3 real-life ADTs.

#### Day 2 – Real vs Abstract Data Types – Arrays & Lists Preview
* **Theory:** Static vs dynamic storage, array memory layout, random access vs sequential; preview of linked list for motivation.
* **ELI5:** "An array is a row of seats with fixed numbers; a linked list is friends holding hands—you can insert a new friend anywhere but must walk from the start to find them."
* **Hands-on:** Draw memory block diagram for an integer array; estimate size.
* **Quiz:** True/false on array characteristics.

#### Day 3 – Algorithm Analysis Steps & Measuring Time
* **Theory:** Steps: input size identification, primitive operations count, machine-independent analysis; difference between actual time and step count.
* **ELI5:** "Counting algorithm steps is like counting how many Lego moves to build a house instead of how long it takes—because your friend may build faster or slower."
* **Lab:** Trace pseudocode to count operations; introduce Python `time` module demo.
* **Self-study:** Count steps for summing elements of an array.

#### Day 4 – Asymptotic Notations: Big-O, Θ, Ω
* **Theory:** Formal definitions, graphical intuition, common orders (O(1), O(log n), O(n), O(n²)); rules for dropping constants.
* **ELI5:** "Big-O is like saying 'at worst the homework will take you this many minutes'; Θ is exact; Ω is at least this long."
* **Activity:** Match everyday tasks to complexity cards.
* **Quiz:** Identify complexity of nested loops.

#### Day 5 – Time-Space Trade-off & Simple Loop Analysis
* **Theory:** Memory vs speed examples (lookup table vs computation); analyse constant, linear, quadratic loops; introduction to auxiliary space.
* **ELI5:** "Keeping a cheat-sheet (extra paper) makes homework faster but your desk messier—that's time-space trade-off."
* **Practice:** Write small C snippet, predict time & space, verify via compiler size.
* **Assessment:** 5 MCQs + 1 short answer.

#### Day 6 – Searching Basics & Linear Search Algorithm
* **Theory:** Problem of search, pseudo-code for linear search, best/average/worst-case analysis O(n); sentinel optimisation.
* **ELI5:** "Looking for a book on a messy shelf one by one until you find it."
* **Lab:** Implement linear search in C/Python; measure time for varying n.
* **Homework:** Explain why linear search works on unsorted data.

#### Day 7 – Binary Search Concept & Implementation
* **Theory:** Requirement of sorted list, divide-and-conquer idea, iterative vs recursive code; complexity O(log n).
* **ELI5:** "Like guessing a number between 1-100 by asking 'higher or lower' and halving choices each time."
* **Hands-on:** Step through binary search on paper with 15-element list; record indices checked.
* **Quiz:** 6 quick questions.

#### Day 8 – Recursion in Binary Search & Complexity Comparison
* **Theory:** Recursion stack, base/recursive cases; memory overhead; compare iterative vs recursive binary search.
* **ELI5:** "Recursion is like Russian dolls—each doll asks a smaller doll until tiniest answers."
* **Activity:** Code both versions; inspect call stack diagram.
* **Self-study:** Fill table comparing O(n) vs O(log n) for n = 10, 100, 1000.

#### Day 9 – Empirical Timing with Code – Linear vs Binary
* **Theory:** Experimental setup, plotting runtime vs n; discuss cache effects; reconcile empirical with theoretical curves.
* **ELI5:** "We race two friends: one walks every step, the other takes giant leaps—see when leaps save time."
* **Lab:** Python/Excel plot of runtime; interpret.
* **Assessment:** Short write-up summarising findings.

#### Day 10 – Integrated Mini-Project & Unit-1 Review
* **Mini-Project:** Build a simple phone-book CLI that supports add/display/search using both linear and binary search; measure performance.
* **ELI5 Wrap-Up:** "We built smart shelves: first messy shelf (linear), then alphabetised shelf (binary) to find phones faster."
* **Unit-1 Test:** 20 marks (MCQ, step count, coding snippet).
* **Feedback:** Address common errors; preview Unit 2 (Stacks & Queues).

---

### Expected Outcomes after 2 Weeks
* Define data structures and ADTs with everyday analogies.  
* Perform step-count analysis and apply Big-O, Θ, Ω notations.  
* Explain time-space trade-off with examples.  
* Implement and analyse linear & binary search algorithms, recognising best/average/worst cases.  
* Collect empirical timing data and relate to theoretical complexity.  
* Communicate technical ideas through intuitive ELI5 explanations. 

## Unit 2 – Two-Week Curriculum (Designed for Below-Average Learners)

### Overview
Unit 2 focuses on **Stacks and Queues**, including their implementations and applications. Total contact time ≈ **9 lecture hours**, but we stretch content over **10 class-days (≈ 2 weeks)** for extra practice and reflection.

* **Theory (standard explanation)**  
* **ELI5 version (Explain-Like-I'm-Five)**  
* **Activities / practice**

| Week | Day | Topics |
|------|-----|--------|
| 1 | 1 | Stack ADT: Concept, Push/Pop/Peek |
|   | 2 | Stack Implementation: Array vs Linked List |
|   | 3 | Expression Basics: Infix, Prefix, Postfix |
|   | 4 | Algorithm: Infix → Postfix Conversion |
|   | 5 | Algorithm: Postfix Evaluation |
| 2 | 6 | Queue ADT & Simple Queue Implementation |
|   | 7 | Circular Queue: Overcoming Space Waste |
|   | 8 | Linked Queue & Complexity Review |
|   | 9 | Priority Queue & Real-World Uses |
|   | 10 | Mini-Project & Unit-2 Review |

---

### Detailed Daily Breakdown

#### Day 1 – Stack ADT: Concept, Push/Pop/Peek
* **Theory:** LIFO nature, basic stack operations, overflow/underflow conditions; use-cases (undo, call stack).
* **ELI5:** "A stack is like a pile of plates; you add or remove only from the top."
* **Activity:** Students simulate stack with paper cups; illustrate push/pop.
* **Homework:** Write pseudo-code for `isEmpty()`.

#### Day 2 – Stack Implementation: Array vs Linked List
* **Theory:** Fixed-size array stack (top index), dynamic linked-list stack (top pointer); complexity O(1) for push/pop.
* **ELI5:** "Array stack is a bookshelf with numbered slots; linked stack is friends forming a conga line—new friend goes to front."
* **Lab:** Implement both in C/Python; test overflow/underflow.
* **Quiz:** Identify scenarios favoring linked over array stack.

#### Day 3 – Expression Basics: Infix, Prefix, Postfix
* **Theory:** Operators, operands, precedence, associativity; why computers prefer postfix.
* **ELI5:** "Infix is how we talk: 2 + 3. Postfix is robot language: 2 3 + where the robot adds when it sees +."
* **Activity:** Card game arranging tokens to form infix/prefix/postfix.
* **Self-study:** Convert given expressions manually.

#### Day 4 – Algorithm: Infix → Postfix Conversion
* **Theory:** Shunting-yard algorithm using stack; precedence table; step-by-step walk-through.
* **ELI5:** "Like sorting laundry: stack is temporary basket holding clothes until the right moment."
* **Hands-on:** Trace conversion of `(A+B)*C-D` on board; students replicate.
* **Assessment:** 6 MCQs on algorithm steps.

#### Day 5 – Algorithm: Postfix Evaluation
* **Theory:** Scan tokens, push operands, pop two operands on operator; handle multi-digit and variables.
* **ELI5:** "Robot reads numbers, keeps them in pockets; when it sees + it pulls two numbers out, adds, and puts result back."
* **Lab:** Code evaluator; test on sample expressions; show stack trace.
* **Homework:** Evaluate `5 1 2 + 4 * + 3 -` manually.

#### Day 6 – Queue ADT & Simple Queue Implementation
* **Theory:** FIFO nature, enqueue/dequeue, front/rear indices; array implementation & issue of wasted space.
* **ELI5:** "Queue is like a line at an ice-cream truck—first kid served first."
* **Activity:** Classroom queue demo; discuss what happens if line goes beyond array length.
* **Quiz:** True/false on queue operations.

#### Day 7 – Circular Queue: Overcoming Space Waste
* **Theory:** Modulo arithmetic for front/rear wrap-around; detecting full vs empty; complexity O(1).
* **ELI5:** "Circular queue is a merry-go-round: kids hop on/off but platform rotates so empty spots get reused."
* **Lab:** Implement circular queue in array; trace enqueue/dequeue after wrap.
* **Self-study:** Draw state diagram after series of operations.

#### Day 8 – Linked Queue & Complexity Review
* **Theory:** Node with data & next, front/rear pointers; memory efficiency; complexity same O(1).
* **ELI5:** "Linked queue is like train carriages coupled together; you can keep adding cars without resizing track."
* **Hands-on:** Convert array queue code to linked version; run tests.
* **Assessment:** Compare memory usage for 1,000 enqueues in both versions.

#### Day 9 – Priority Queue & Real-World Uses
* **Theory:** Definition, min-heap / max-heap implementation overview; applications (CPU scheduling, Dijkstra).
* **ELI5:** "VIP line: people with higher priority cut ahead politely based on number badges."
* **Demo:** Visual heap insertion/deletion using online tool.
* **Quiz:** Identify which data structure fits given scenario (printer spool, undo stack, CPU scheduler).

#### Day 10 – Mini-Project & Unit-2 Review
* **Mini-Project:** Implement arithmetic expression calculator: infix input → postfix → evaluate; plus menu-driven queue simulation.
* **ELI5 Wrap-Up:** "We built smart plate piles and ice-cream lines for our computer."
* **Unit-2 Test:** 20 marks (MCQ, coding, dry-run).
* **Feedback:** Address doubts; preview Unit 3 (Linked Lists & Trees).

---

### Expected Outcomes after 2 Weeks
* Implement stacks using arrays and linked lists, handling overflow/underflow.  
* Use stacks to convert infix expressions to postfix/prefix and evaluate postfix expressions.  
* Implement simple, circular, linked, and priority queues, analysing their complexities.  
* Select appropriate linear data structure for real-world scenarios.  
* Articulate concepts with intuitive ELI5 analogies. 

## Unit 3 – Two-Week Curriculum (Designed for Below-Average Learners)

### Overview
Unit 3 (≈ 10 lecture hours) introduces **Linked Lists** and **Trees**—key nonlinear data structures. The material is distributed across **10 class-days (≈ 2 weeks)** to reinforce concepts with hands-on practice.

* **Theory (standard explanation)**  
* **ELI5 version (Explain-Like-I'm-Five)**  
* **Activities / practice**

| Week | Day | Topics |
|------|-----|--------|
| 1 | 1 | Linked List Basics & Node Structure |
|   | 2 | Singly Linked List Operations (Insert/Delete/Traverse) |
|   | 3 | Doubly & Circular Linked Lists |
|   | 4 | Linked Representation of Stack & Queue |
|   | 5 | Linked List Mini-Lab & Recap |
| 2 | 6 | Tree Fundamentals & Binary Tree Traversals |
|   | 7 | Binary Search Tree (BST): Insert/Delete/Search |
|   | 8 | Balanced Trees: AVL Rotations |
|   | 9 | Multi-way Trees: B & B+ Trees |
|   | 10 | Integrated Project & Unit-3 Review |

---

### Detailed Daily Breakdown

#### Day 1 – Linked List Basics & Node Structure
* **Theory:** Dynamic memory, `struct Node {data, next}`; advantages over arrays; pointer basics.
* **ELI5:** "A linked list is like a treasure hunt—each clue (node) tells where the next clue is."
* **Activity:** Paper chain demo: students pass index cards with arrows pointing to next student.
* **Homework:** Draw 4-node linked list diagram.

#### Day 2 – Singly Linked List Operations
* **Theory:** Insertion (head, tail, middle), deletion, traversal; complexity O(1) for head insert, O(n) search.
* **ELI5:** "Adding a new clue at front is easy—just put it on top of the pile; finding a clue means following arrows one by one."
* **Lab:** Implement SLL in C/Python; visualise with print statements.
* **Quiz:** Predict pointer updates for tail deletion.

#### Day 3 – Doubly & Circular Linked Lists
* **Theory:** Doubly list with `prev` pointer; bidirectional traversal; circular list (last node points to first); pros/cons.
* **ELI5:** "Doubly list is like a two-way street—you can walk forward or back; circular list is a race track—no real end."
* **Hands-on:** Modify SLL to DLL; test reverse traversal.
* **Self-study:** Draw pointer changes for inserting after a given node in DLL.

#### Day 4 – Linked Representation of Stack & Queue
* **Theory:** Push/pop using head pointer for stack; enqueue at tail, dequeue at head for queue.
* **ELI5:** "Stack with links is like adding/removing beads at the top of a necklace without worrying about necklace length."
* **Lab:** Convert previous array stack/queue code to linked versions; measure memory.
* **Assessment:** MCQ on complexity.

#### Day 5 – Linked List Mini-Lab & Recap
* **Project:** Build menu-driven program supporting create/display/insert/delete/search in SLL and DLL.
* **ELI5 Tie-In:** "We stitched and un-stitched our treasure map on demand."
* **Review Game:** Kahoot on linked list pitfalls (null pointer, memory leak).
* **Homework:** Prepare one question about trees.

#### Day 6 – Tree Fundamentals & Binary Tree Traversals
* **Theory:** Node degree, height, leaf/internal nodes; binary tree properties; traversals (pre-, in-, post-order); recursion.
* **ELI5:** "A tree is an upside-down family chart—grandparent at top, children below."
* **Activity:** Human traversal: students stand as tree nodes, teacher walks pre/in/post paths.
* **Quiz:** Identify traversal sequence for given tree.

#### Day 7 – Binary Search Tree (BST)
* **Theory:** Ordered property; insert, search, delete cases (leaf, one child, two children); complexity best O(log n), worst O(n).
* **ELI5:** "BST is like an organised bookshelf—left shelf has smaller books, right has larger; you know where to look."
* **Lab:** Code BST insert/search; visualise via simple ASCII tree.
* **Self-study:** Trace delete of root with two children.

#### Day 8 – Balanced Trees: AVL Rotations
* **Theory:** Need for balance; balance factor; single & double rotations (LL, RR, LR, RL); height O(log n).
* **ELI5:** "AVL tree is a self-balancing mobile—if one side gets heavier, it shifts weights to stay level."
* **Demo:** Physical mobile model; group performs rotations with cards.
* **Assessment:** MCQ on rotation type for given imbalance.

#### Day 9 – Multi-way Trees: B & B+ Trees
* **Theory:** m-way search trees for disks; node structure, splitting; difference between B and B+; search complexity O(logₘ n).
* **ELI5:** "B-tree is like a binder with many tabs—each tab leads to several pages to reach your file quickly."
* **Lab:** Step-through insert sequence into B-tree using animation tool.
* **Quiz:** Identify when node split occurs.

#### Day 10 – Integrated Project & Unit-3 Review
* **Project:** Implement phone-contact manager: insert/search/delete using BST; export ordered list (in-order).
* **ELI5 Wrap-Up:** "Our digital family tree grew and we learned to keep it tidy and balanced."
* **Unit-3 Test:** 20 marks (MCQ, pointer tracing, tree rotations).
* **Feedback:** Clarify doubts; introduce Unit 4 (Sorting, Hashing, Graphs).

---

### Expected Outcomes after 2 Weeks
* Implement singly, doubly, and circular linked lists with insertion, deletion, and traversal operations.  
* Convert array-based stacks/queues to linked-list implementations.  
* Explain binary tree concepts and perform recursive traversals.  
* Build and manipulate BSTs, understanding average vs worst-case complexities.  
* Demonstrate AVL rotations to maintain balance.  
* Describe structure and insertion of B and B+ trees for secondary storage.  
* Communicate complex pointer and tree operations through clear ELI5 analogies. 

## Unit 4 – Two-Week Curriculum (Designed for Below-Average Learners)

### Overview
Unit 4 blends **Sorting, Hashing, and Graph Fundamentals**. Although the official contact time is **≈ 9 lecture hours**, the plan spreads learning across **10 class-days (≈ 2 weeks)** for ample reinforcement.

* **Theory (standard explanation)**  
* **ELI5 version (Explain-Like-I'm-Five)**  
* **Activities / practice**

| Week | Day | Topics |
|------|-----|--------|
| 1 | 1 | Why Sorting? Performance Metrics & O-Notation Refresh |
|   | 2 | Selection Sort Algorithm & Complexity |
|   | 3 | Bubble Sort vs Insertion Sort |
|   | 4 | Merge Sort (Divide-and-Conquer) |
|   | 5 | Quick Sort Idea & Partitioning Demo |
| 2 | 6 | Heap Data Structure & Heap Sort |
|   | 7 | Comparative Sorting Lab & Stability Discussion |
|   | 8 | Hashing Concepts, Collisions & Resolution |
|   | 9 | Graph Basics, Representations, BFS/DFS |
|   | 10 | Integrated Mini-Project & Unit-4 Review |

---

### Detailed Daily Breakdown

#### Day 1 – Why Sorting? Performance Metrics
* **Theory:** Importance of sorting for search efficiency; stability; in-place vs out-of-place; recap Big-O.
* **ELI5:** "Sorting is like arranging books alphabetically so any title is easy to find."
* **Activity:** Students sort index cards manually, time the process; discuss factors affecting speed.
* **Homework:** Note daily life examples where sorting matters.

#### Day 2 – Selection Sort
* **Theory:** Repeatedly select minimum element; in-place, O(n²) comparisons, O(n) swaps.
* **ELI5:** "Like picking the smallest candy from the pile and putting it in a new row, again and again."
* **Lab:** Implement selection sort; count comparisons and swaps.
* **Quiz:** Predict passes for n = 6.

#### Day 3 – Bubble Sort vs Insertion Sort
* **Theory:** Bubble: adjacent swaps, early exit optimisation; Insertion: build sorted prefix; best-case O(n).
* **ELI5:** Bubble: "big bubbles rise to top"; Insertion: "sorting playing cards in your hand."
* **Hands-on:** Race bubble vs insertion on nearly-sorted array; plot time.
* **Assessment:** MCQ on stability and adaptive nature.

#### Day 4 – Merge Sort (Divide-and-Conquer)
* **Theory:** Recursive splitting, merging; complexity O(n log n); stable; extra O(n) space.
* **ELI5:** "Cut deck into halves, sort each, then interleave like shuffling two sorted decks."
* **Demo:** Visual merge process with coloured paper strips.
* **Self-study:** Trace merge sort on 8 numbers.

#### Day 5 – Quick Sort Idea & Partitioning
* **Theory:** Pivot selection, partition algorithm (Lomuto/Hoare), average O(n log n), worst O(n²); in-place.
* **ELI5:** "Pick a leader, send smaller kids to left line and bigger kids to right; repeat in each line."
* **Lab:** Implement quick sort; experiment with pivot choices.
* **Quiz:** Identify worst-case pivot scenario.

#### Day 6 – Heap Data Structure & Heap Sort
* **Theory:** Binary heap as array, heapify, build-heap O(n), heap sort O(n log n); not stable.
* **ELI5:** "Heap is a sand-pile where the biggest grain always sits on top; remove it and pile settles again."
* **Hands-on:** Draw max-heap for 10 numbers; perform one delete-max.
* **Homework:** Implement heap insert/delete.

#### Day 7 – Comparative Sorting Lab & Stability Discussion
* **Activity:** Students benchmark all six sorts on random, sorted, reversed datasets; fill table (time, swaps, stability).
* **ELI5 Tie-In:** "See which sorting 'team' wins different races."
* **Discussion:** Pros/cons; when to pick which algorithm.
* **Assessment:** Short reflective write-up.

#### Day 8 – Hashing Concepts, Collisions & Resolution
* **Theory:** Hash function properties; load factor; collision strategies (chaining, linear/quadratic probing, double hashing); complexity analysis.
* **ELI5:** "Hashing is like giving every student a locker by secret math; if two get same locker, one waits or uses next empty."
* **Lab:** Implement hash table with chaining; test insertion/search time at varying load factors.
* **Quiz:** Choose suitable collision method for scenario.

#### Day 9 – Graph Basics, Representations, BFS/DFS
* **Theory:** Terminologies (vertex, edge, degree); adjacency matrix vs list; BFS & DFS algorithms and applications.
* **ELI5:** "Graph is a map of cities and roads; BFS is exploring layer by layer, DFS is diving deep along one road first."
* **Hands-on:** Paper graph traversal; students shout visit order.
* **Self-study:** Code BFS on adjacency list.

#### Day 10 – Integrated Mini-Project & Unit-4 Review
* **Project:** Build a tiny search engine: read list of words, hash into table, sort by frequency using heap; provide BFS traversal of synonym graph.
* **ELI5 Wrap-Up:** "We organised words fast, stored them in magic lockers, and explored word-friend maps."
* **Unit-4 Test:** 20 marks (MCQ, coding, dry-run).
* **Feedback:** Summarise entire course; suggest further practice resources.

---

### Expected Outcomes after 2 Weeks
* Implement and analyse selection, bubble, insertion, merge, quick, and heap sort algorithms, knowing their stability, space, and time trade-offs.  
* Select appropriate sorting technique for a given dataset scenario.  
* Explain hashing principles, design simple hash functions, and apply collision resolution strategies.  
* Represent graphs using adjacency lists/matrices and perform BFS and DFS traversals.  
* Relate technical processes to everyday analogies via ELI5 explanations.  
* Integrate sorting, hashing, and graph traversal in a small application. 