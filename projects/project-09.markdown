---
layout: post
title: Project 9
due: "Nov 6, 11:59pm"
categories: [projects]
---

# Project 9

- Read pp. 121-172

- Create a repository on Bitbucket named exactly `csci201-project-09`. Invite me (`joshuaeckroth`) as a reader.

## Task 1

Write these functions in the VM language:

```
// returns a if a>b, otherwise returns b
int max(a, b)
```

```
// returns a/b
int quotient(a, b)
```

```
// returns a^b; computes iteratively
int iterativePow(a, b)
```

```
// returns a^b; computes recursively
int recursivePow(a, b)
```

```
// returns -1 if n is prime, 0 otherwise;
// uses mod function from notes
int prime(n)
```

Download test files: [project-09.zip](/code/project-09.zip) (incomplete). The test files include working implementations of examples from class.

## Task 2

Write these "words" in [Forth](/notes/forth.html). The code must run on Gforth.

```
max2 ( a b -- maxval )
```