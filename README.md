# AI-LAB5

What is the Block World Problem?
The Block World Problem is a classical problem in Artificial Intelligence used to study planning and reasoning.

-The world consists of a table and a set of blocks that can be stacked or placed on the table.

-The problem is defined by an initial state and a goal state.

-The task is to find a sequence of valid moves to reach the goal state.

Example:
-Initial State: A on B, B on Table, C on Table

-Goal State: B on C, A on B

The AI program must reason step by step:
1.Move A from B to Table

2.Move B onto C

3.Move A onto B

This problem helps demonstrate:
-State space representation

-Goal-directed reasoning

-Search-based planning

Prolog and Lisp
Prolog (Programming in Logic)
Prolog is a logic programming language. It has important role in artificial intelligence. Unlike many other programming languages, Prolog is intended primarily as a declarative programming language. In prolog, logic is expressed as relations (called as Facts and Rules). Core heart of prolog lies at the logic being applied. Formulation or Computation is carried out by running a query over these relations.

1.Prolog is a logic programming language based on formal logic.

2.Programs are written as a set of facts and rules.

3.Queries are executed using backtracking and unification.

4.Best suited for problems involving knowledge representation, reasoning, and AI planning.

Lisp (List Processing Language)
Lisp is a programming language that has an overall style that is organized around expressions and functions. Every Lisp procedure is a function, and when called, it returns a data object as its value. It is also commonly referred to as "functions" even though they may have side effects.

Lisp is the second-oldest high-level programming language in the world which is invented by John McCarthy in the year 1958 at the Massachusetts Institute of Technology.

Features of LISP Programming Language:
1.It is a machine-independent language

2.It uses iterative design methodology and is easily extensible

3.It allows us to create and update the programs and applications dynamically.

4.It provides high-level debugging.

5.It supports object-oriented programming.

6.It supports all kinds of data types like objects, structures, lists, vectors, adjustable arrays, set, trees,hash-tables, and symbols.

7.It is an expression-based language

8.It can support different decision-making statements like if, when,case, and cond

9.It will also support different iterating statements like do, loop,loopfor, dotimes and dolist.

10.It will support input and output functions

11.By using lisp we can also create our own functions

Conclusion on Prolog’s Usefulness
Strengths:
Excellent for symbolic AI problems (planning, reasoning, knowledge representation).
Concise programs using facts and rules.
Still valuable in academia and specialized expert systems.
Limitations:
Not widely used in modern large-scale software development.
Performance issues compared to modern languages like Python or C++.
Limited ecosystem for machine learning and deep learning.
Conclusion: Prolog is still useful for learning AI fundamentals and in certain niche applications (expert systems, reasoning engines), but for modern AI and large-scale systems, languages like Python dominate because of their rich libraries and community support.
