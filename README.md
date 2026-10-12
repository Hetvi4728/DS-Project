# Quiz Management System in C++

## About the Project

The Quiz Management System is a console-based application developed using C++. It uses a **Singly Linked List** to store and manage multiple-choice questions related to Data Structures (DS).

Users can add questions, view all available questions, attempt the quiz, and receive their final score based on their answers.

## Features

- **Add Questions:** Add questions with four options (A, B, C, D).
- **Display Questions:** View all questions and their options.
- **Start Quiz:** Attempt multiple-choice Data Structures questions.
- **Automatic Score Calculation:** Display correct answers, wrong answers, and final score.
- **Dynamic Memory Allocation:** Store questions using dynamically allocated linked-list nodes.
- **Menu-Driven Interface:** Use a simple menu to access different functions.

## Technologies Used

- **Programming Language:** C++
- **Data Structure:** Singly Linked List
- **Header File:** `iostream`
- **Concepts:** Structures, pointers, functions, loops, conditional statements, arrays, and dynamic memory allocation.

## Data Structure Used

This project uses a **Singly Linked List** to store quiz questions.

Each node contains:

- `question` – Stores the question text.
- `options` – Stores four multiple-choice options.
- `answer` – Stores the correct answer.
- `next` – Points to the next node.

The `head` pointer points to the first node of the linked list. Each new question is added as a new node at the end of the list.

## Menu Options

| Option | Function |
|---|---|
| 1 | Add Question |
| 2 | Display Questions |
| 3 | Start Quiz |
| 4 | Exit |

## Sample Data Structures Quiz Questions

The following questions can be entered into the program using the **Add Question** option.

### Question 1
Which data structure follows the LIFO principle?

- A. Queue
- B. Stack
- C. Linked List
- D. Tree

**Correct Answer:** B. Stack

### Question 2
Which data structure follows the FIFO principle?

- A. Stack
- B. Tree
- C. Queue
- D. Graph

**Correct Answer:** C. Queue

### Question 3
Which data structure consists of nodes connected by pointers?

- A. Array
- B. Linked List
- C. Integer
- D. Character

**Correct Answer:** B. Linked List

### Question 4
What is the time complexity of binary search on a sorted array?

- A. O(n)
- B. O(log n)
- C. O(n²)
- D. O(1)

**Correct Answer:** B. O(log n)

### Question 5
Which data structure is commonly used in recursion?

- A. Queue
- B. Stack
- C. Graph
- D. Array only

**Correct Answer:** B. Stack

### Question 6
Which traversal of a Binary Search Tree visits nodes in sorted order?

- A. Preorder
- B. Postorder
- C. Inorder
- D. Level order

**Correct Answer:** C. Inorder

### Question 7
Which data structure is used in Breadth-First Search (BFS)?

- A. Stack
- B. Queue
- C. Heap
- D. Tree

**Correct Answer:** B. Queue

### Question 8
Which of the following is a non-linear data structure?

- A. Array
- B. Stack
- C. Queue
- D. Tree

**Correct Answer:** D. Tree

### Question 9
What is the time complexity of accessing an array element by index?

- A. O(n)
- B. O(log n)
- C. O(1)
- D. O(n²)

**Correct Answer:** C. O(1)

### Question 10
Which data structure is commonly used to implement a priority queue efficiently?

- A. Heap
- B. Stack
- C. Simple queue only
- D. Linked list only

**Correct Answer:** A. Heap

### Question 11
In a singly linked list, what does the last node point to?

- A. First node
- B. Previous node
- C. NULL
- D. Itself

**Correct Answer:** C. NULL

### Question 12
Which algorithm is used to find a minimum spanning tree?

- A. Binary Search
- B. Kruskal's Algorithm
- C. Linear Search
- D. Insertion Sort

**Correct Answer:** B. Kruskal's Algorithm

### Question 13
Which sorting algorithm repeatedly selects the minimum element?

- A. Bubble Sort
- B. Selection Sort
- C. Merge Sort
- D. Quick Sort

**Correct Answer:** B. Selection Sort

### Question 14
What is the maximum number of children a node can have in a binary tree?

- A. 1
- B. 2
- C. 3
- D. Unlimited

**Correct Answer:** B. 2

### Question 15
Which data structure is suitable for implementing undo operations?

- A. Queue
- B. Stack
- C. Graph
- D. Tree

**Correct Answer:** B. Stack

## How to Run the Program

### Step 1: Save the Code

Save the C++ source code in a file named `quiz.cpp`.

### Step 2: Compile the Program

Use a C++ compiler such as GCC.

```bash
g++ quiz.cpp -o quiz
```

### Step 3: Run the Program

**Windows:**

```bash
quiz.exe
```

**Linux / macOS:**

```bash
./quiz
```

## Sample Output

```text
--- QUIZ MANAGEMENT SYSTEM ---
1. Add Question
2. Display Questions
3. Start Quiz
4. Exit
Enter choice: 1

Enter question: Which data structure follows LIFO?
Enter option A: Queue
Enter option B: Stack
Enter option C: Tree
Enter option D: Graph
Enter correct answer (A/B/C/D): B

Question added successfully!
```

## Advantages

- Questions can be added dynamically.
- The linked list can grow as new questions are added.
- The program is divided into functions for easier understanding.
- The project demonstrates the practical use of linked lists.
- The quiz helps students revise Data Structures concepts.

## Limitations

- Questions are stored in memory and are lost when the program terminates.
- Questions cannot be edited or deleted.
- Each question supports exactly four options.
- There is no user login or administrator authentication.
- Quiz questions must be entered manually each time the program starts.

## Future Improvements

- Save questions permanently using file handling or a database.
- Add options to edit and delete questions.
- Introduce a timer for the quiz.
- Add user accounts and a leaderboard.
- Add input validation for answer choices.
- Organize questions by topic and difficulty level.

## Learning Outcomes

This project demonstrates:

- Singly linked list implementation.
- Structures and pointers in C++.
- Dynamic memory allocation using `new`.
- Traversing a linked list.
- Functions and menu-driven programming.
- Multiple-choice quiz logic and score calculation.

## Author

Developed as a C++ Data Structures project to demonstrate a Quiz Management System using a Singly Linked List.
