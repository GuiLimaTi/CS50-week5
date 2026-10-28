# CS50x Week 5 – Data Structures

Problem sets from Week 5 of Harvard's CS50x, covering linked lists, trees and hash tables in C, with manual memory management.

**Language:** C · **Course:** [CS50x](https://cs50.harvard.edu/x/) · **Status:** Completed (2026)

## Overview

This week was about organising data efficiently. I built a family tree with recursive structs and a fast spell-checker based on a hash table, managing all memory with `malloc` and `free`.

## Projects

| Project | File | Description | Key concepts |
|---|---|---|---|
| Inheritance | `inheritance.c` | Simulates the inheritance of blood-type alleles across three generations of a family | Recursive structs, pointers, freeing memory recursively |
| Speller | `dictionary.c` | Loads a dictionary into a hash table and spell-checks a text file quickly | Hash function, linked lists for collisions, `malloc`/`free`, no memory leaks |

## How to run

Requires the distribution files from the CS50 problem set.

```bash
make speller
./speller dictionaries/large texts/lalaland.txt
```

## What I learned

- How the choice of data structure changes a program's speed
- Designing a hash function and handling collisions
- Building and freeing linked structures without memory leaks
- Debugging pointer-based code

## Academic honesty

These solutions were written by me as part of CS50x. If you're taking the course, please follow CS50's [academic honesty policy](https://cs50.harvard.edu/x/honesty/) and write your own code.

---

**Guilherme Lima** · Aspiring IT Support Technician · [LinkedIn](https://www.linkedin.com/in/glimaalmeida) · [GitHub](https://github.com/GuiLimaTi)
