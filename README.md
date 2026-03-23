# CS50 Week 5 — Data Structures

This repository contains my work from **Week 5 of Harvard's CS50**, where I focused on one of the most fundamental topics in computer science: **data structures**.

At this stage of the course, I moved from understanding memory to organizing and managing data efficiently. This week required me to think not only about how data is stored, but also how quickly and effectively it can be accessed and manipulated.

## What I learned

During Week 5, I worked on core concepts such as:

- Abstract data types
- Linked lists
- Trees and tries
- Hash tables
- Hash functions
- Collision handling
- Dynamic memory allocation
- Efficiency and time complexity

These concepts helped me understand how to design programs that are both **efficient and scalable**.

## Problem Set Focus

### Speller

In the **Speller** problem, I implemented a spell-checker in C using a **hash table with linked lists**.

The goal was to load a dictionary into memory and efficiently check words from a text file against it.

Through this exercise, I practiced:

- Designing and implementing a hash table
- Creating and managing linked lists
- Writing a custom hash function
- Handling hash collisions properly
- Performing fast lookups for large datasets
- Managing memory using `malloc()` and `free()`
- Avoiding memory leaks

Key functions implemented:

- `load` — reads dictionary words into memory
- `check` — verifies if a word exists (case-insensitive)
- `hash` — maps words to indices in the hash table
- `size` — returns total number of words loaded
- `unload` — frees all allocated memory

This problem showed me how powerful data structures are when dealing with real-world scale problems like spell-checking.

## Why this week matters

Week 5 was a major step forward in my understanding of computer science.

Before this, I knew how to work with memory. After this week, I started understanding:

- how to organize large amounts of data efficiently
- how different data structures impact performance
- how hash tables enable near constant-time lookups
- how to combine pointers and structures in practical applications

This week was not just about coding — it was about learning how to think like a software engineer when dealing with performance and scalability.

## Skills demonstrated

Through this week’s work, I practiced and demonstrated:

- Implementing hash tables from scratch
- Using linked lists for collision handling
- Writing efficient lookup algorithms
- Managing memory manually in C
- Debugging pointer-based structures
- Avoiding memory leaks with proper deallocation
- Designing scalable solutions for large datasets
- Applying problem-solving strategies in low-level programming

## My learning approach

I am documenting my CS50 journey publicly to show not only completed exercises, but also my growth in logic, technical understanding, and consistency.

This repository reflects my commitment to:

- learning by doing
- improving step by step
- building strong programming fundamentals
- treating each exercise as part of a long-term professional development path

## About CS50

CS50 is Harvard University’s introduction to computer science. The course covers topics such as algorithms, data structures, memory, abstraction, and software engineering.

## Author

**Guilherme Lima**  
CS50 student | Building programming foundations step by step
