# Discrete Mathematics - Detailed Notes

# Table of Contents

1. Introduction to Discrete Mathematics
2. Need for Studying Discrete Mathematics
3. Discrete vs Continuous Objects
4. Syllabus of Discrete Mathematics
5. Real-World Applications
6. Conclusion

---

# 1. Introduction to Discrete Mathematics

## What is Discrete Mathematics?

Discrete Mathematics is a branch of mathematics that studies **discrete objects**.

Discrete objects are:
- Separate
- Distinct
- Countable

Unlike continuous mathematics, discrete mathematics does not deal with smoothly changing values.

It focuses on:
- Integers
- Graphs
- Logical statements
- Sets
- Trees
- Finite structures

---

## Meaning of the Word "Discrete"

The word **discrete** means:
> Individually separate and distinct.

Example:

```text
1, 2, 3, 4, 5
```

Each number is clearly separated.

---

# Example of Discrete Objects

| Object | Discrete or Continuous |
|---|---|
| Number of students | Discrete |
| Number of books | Discrete |
| Number of cars | Discrete |
| Temperature | Continuous |
| Height | Continuous |

---

# Simple Example

You can have:
- 1 book
- 2 books
- 3 books

But you cannot have:
- 2.5 books

Therefore, books are discrete objects.

---

# Main Topics in Discrete Mathematics

Discrete Mathematics includes:

- Logic
- Set Theory
- Relations
- Functions
- Graph Theory
- Number Theory
- Combinatorics
- Probability
- Boolean Algebra

---

# Small Diagram

## Discrete Structure

```text
●   ●   ●   ●   ●
```

Separate points.

## Continuous Structure

```text
────────────────────
```

Smooth line.

---

# 2. Need for Studying Discrete Mathematics

## Why is Discrete Mathematics Important?

Discrete Mathematics is extremely important in:
- Computer Science
- Software Engineering
- Competitive Programming
- Artificial Intelligence
- Cybersecurity
- Data Science

It helps improve:
- Logical thinking
- Problem solving
- Algorithmic reasoning

---

# 2.1 Importance in Computer Science

Computers work using:
- Binary values
- Logic
- Finite structures

All these concepts come from discrete mathematics.

---

# 2.2 Importance in Programming

Programming uses logical conditions.

Example:

```js
if (age > 18 && hasID) {
  console.log("Allowed");
}
```

This uses:
- Logical AND
- Boolean values
- Conditional logic

These are topics from discrete mathematics.

---

# 2.3 Importance in Data Structures

Many data structures are based on discrete mathematics.

Examples:

| Data Structure | Related Topic |
|---|---|
| Tree | Graph Theory |
| Graph | Graph Theory |
| Heap | Trees |
| Hash Table | Number Theory |

---

# 2.4 Importance in Algorithms

Algorithms often use:
- Counting
- Recursion
- Graphs
- Probability

Example:
- Shortest path algorithm
- BFS
- DFS

---

# 2.5 Importance in Competitive Programming

Competitive Programming heavily depends on:
- Number Theory
- Graph Theory
- Combinatorics
- Logic

Example problems:
- Prime numbers
- Dynamic Programming
- Permutations

---

# 2.6 Importance in Artificial Intelligence

AI uses:
- Probability
- Graphs
- Logic
- Set Theory

Applications:
- Recommendation systems
- Search engines
- Machine learning

---

# 2.7 Importance in Cybersecurity

Encryption systems use:
- Prime numbers
- Modular arithmetic
- Number theory

Example:
- RSA Encryption

---

# 2.8 Importance in Databases

Databases use:
- Relations
- Sets
- Functions

SQL joins are based on relation theory.

---

# 3. Discrete vs Continuous Objects

# What are Discrete Objects?

Discrete objects are:
- Countable
- Separate
- Distinct

Example:
- Students
- Cars
- Computers

---

# Example

```text
1, 2, 3, 4, 5
```

Each number is separated.

---

# What are Continuous Objects?

Continuous objects can change smoothly.

There are infinitely many values between two numbers.

Examples:
- Height
- Weight
- Time
- Temperature

---

# Example

Between 1 and 2:

```text
1.1
1.01
1.001
1.0001
...
```

Infinite values exist.

---

# Comparison Table

| Feature | Discrete | Continuous |
|---|---|---|
| Nature | Separate | Smooth |
| Countable | Yes | Usually Infinite |
| Example | Students | Temperature |
| Used In | Computer Science | Physics |

---

# Visual Representation

## Discrete

```text
●   ●   ●   ●   ●
```

## Continuous

```text
────────────────────────
```

---

# Real-Life Examples

| Situation | Type |
|---|---|
| Number of employees | Discrete |
| Speed of a car | Continuous |
| Number of mobile phones | Discrete |
| Water level | Continuous |

---

# 4. Syllabus of Discrete Mathematics

Different universities may have different syllabuses, but the common topics are:

---

# 4.1 Logic and Propositional Calculus

## Topics

- Statements
- Logical operators
- Truth tables
- Predicate logic
- Quantifiers

---

## Logical Operators

| Symbol | Meaning |
|---|---|
| AND | ∧ |
| OR | ∨ |
| NOT | ¬ |
| IMPLIES | → |

---

## Example Truth Table

| P | Q | P AND Q |
|---|---|---|
| T | T | T |
| T | F | F |
| F | T | F |
| F | F | F |

---

# 4.2 Set Theory

## Topics

- Sets
- Subsets
- Union
- Intersection
- Difference
- Power sets

---

# Example

```text
A = {1,2,3}
B = {3,4,5}

Union:
A ∪ B = {1,2,3,4,5}

Intersection:
A ∩ B = {3}
```

---

# Venn Diagram

```text
      _______
     /   A   \
    /  1 2 3  \
   /____3______\
   \    4 5   /
    \    B   /
     \______/
```

---

# 4.3 Relations and Functions

## Topics

- Cartesian products
- Relations
- Equivalence relations
- Functions
- One-to-one functions
- Onto functions

---

# Example Function

```text
f(x) = x + 2
```

If:
```text
x = 3
```

Then:
```text
f(3) = 5
```

---

# 4.4 Counting and Combinatorics

## Topics

- Permutations
- Combinations
- Factorials
- Pigeonhole principle

---

# Factorial Example

```text
5! = 5 × 4 × 3 × 2 × 1
   = 120
```

---

# Permutation Example

Number of ways to arrange 3 letters:

```text
ABC
ACB
BAC
BCA
CAB
CBA
```

Total:

```text
3! = 6
```

---

# Combination Example

Choosing 2 students from 4 students:

```text
4C2 = 6
```

---

# 4.5 Graph Theory

## Topics

- Graphs
- Trees
- BFS
- DFS
- Shortest path
- Connected graphs

---

# Graph Example

```text
A ----- B
|       |
|       |
C ----- D
```

---

# Applications

- Google Maps
- Social networks
- Routing systems

---

# 4.6 Number Theory

## Topics

- Prime numbers
- GCD
- LCM
- Modular arithmetic

---

# Prime Number Example

Prime numbers:

```text
2, 3, 5, 7, 11
```

---

# Modular Arithmetic Example

```text
17 mod 5 = 2
```

Because:

```text
17 ÷ 5 = remainder 2
```

---

# 4.7 Boolean Algebra

## Topics

- Boolean expressions
- Logic gates
- Simplification

---

# Example

```text
1 AND 1 = 1
1 AND 0 = 0
```

---

# Logic Gate Diagram

```text
A ----\
       AND ---- Output
B ----/
```

---

# 4.8 Recurrence Relations

## Topics

- Recursive sequences
- Recursive formulas
- Fibonacci sequence

---

# Fibonacci Example

```text
F(n) = F(n-1) + F(n-2)
```

Sequence:

```text
0, 1, 1, 2, 3, 5, 8
```

---

# 4.9 Probability

## Topics

- Basic probability
- Conditional probability
- Bayes theorem

---

# Probability Formula

```text
P(A) = Favorable outcomes / Total outcomes
```

---

# Example

If a dice is rolled:

Probability of getting 3:

```text
1 / 6
```

---

# 5. Real-World Applications

# Social Media

Graph theory is used in:
- Facebook
- Instagram
- LinkedIn

Users are represented as nodes.

---

# Google Maps

Shortest path algorithms are used for navigation.

---

# Banking

Encryption uses number theory.

---

# Gaming

Probability is used in:
- Loot systems
- Random events

---

# Search Engines

Graphs and algorithms are used in:
- Google Search
- Recommendations

---

# 6. Conclusion

Discrete Mathematics is one of the most important subjects in Computer Science.

It builds the foundation for:
- Algorithms
- Programming
- Artificial Intelligence
- Cybersecurity
- Competitive Programming

By studying Discrete Mathematics, students improve:
- Logical thinking
- Mathematical reasoning
- Problem-solving ability

It is considered a core subject for every software engineer and computer science student.
