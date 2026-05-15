# 🧠 Logical Operators: Negation, Conjunction, and Disjunction

## 📌 Introduction

Logical operators are fundamental concepts in propositional logic. They allow us to combine or modify simple statements (propositions) to form more complex ones.

In this section, we focus on three important logical operators:

1. Negation (NOT)
2. Conjunction (AND)
3. Disjunction (OR)

---

# 🔁 1. Negation (NOT)

## ✅ Definition

Let **p** be a proposition.

The **negation** of p is written as:

```

¬p (or NOT p)

```

It simply means:

> "It is not the case that p"

---

## 💡 Explanation

Negation reverses the truth value of a proposition:

- If **p is true**, then **¬p is false**
- If **p is false**, then **¬p is true**

---

## 📊 Truth Table

| p     | ¬p    |
|-------|-------|
| True  | False |
| False | True  |

---

## 🧾 Example

Let:

> p: "Adam and Eve lived together for many years."

Then:

> ¬p: "It is not the case that Adam and Eve lived together for many years."  
> OR  
> "Adam and Eve have not lived together for many years."

---

# 🔗 2. Conjunction (AND)

## ✅ Definition

Let **p** and **q** be two propositions.

The **conjunction** of p and q is written as:

```

p ∧ q (p AND q)

```

---

## 💡 Explanation

Conjunction is true **only when both statements are true**.

- If **both p and q are true → result is true**
- Otherwise → result is false

---

## 📊 Truth Table

| p     | q     | p ∧ q |
|-------|-------|-------|
| True  | True  | True  |
| True  | False | False |
| False | True  | False |
| False | False | False |

---

## 🧾 Example

> "12 is divisible by 3 AND 3 is a prime number"

- First part: True  
- Second part: True  
- Result: **True**

---

## ⚠️ Note

In logical meaning:

> "AND" and "BUT" are treated the same.

Example:

- "He is poor but honest"
- "He is poor and honest"

Both represent **conjunction (p ∧ q)**

---

# 🔀 3. Disjunction (OR)

## ✅ Definition

Let **p** and **q** be two propositions.

The **disjunction** is written as:

```

p ∨ q (p OR q)

```

---

## 💡 Explanation

Disjunction is false **only when both statements are false**.

- If **at least one is true → result is true**
- If **both are false → result is false**

---

## 📊 Truth Table

| p     | q     | p ∨ q |
|-------|-------|-------|
| True  | True  | True  |
| True  | False | True  |
| False | True  | True  |
| False | False | False |

---

## 🧾 Example

> "16 - 4 = 10 OR 4 is an even number"

- First part: False (16 - 4 = 12)
- Second part: True
- Result: **True**

---

# ⚠️ Important Concept

This "OR" is **inclusive OR**, meaning:

> It is true if **either or both** statements are true.

(It is different from **Exclusive OR (XOR)**, which requires exactly one to be true — you’ll study that later.)

---

# 🎯 Summary

| Operator     | Symbol | Meaning                     | When True                          |
|--------------|--------|----------------------------|------------------------------------|
| Negation     | ¬p     | NOT p                      | When p is false                    |
| Conjunction  | p ∧ q  | p AND q                    | When both p and q are true         |
| Disjunction  | p ∨ q  | p OR q                     | When at least one is true          |

---

# 🚀 Final Thought

These three operators form the **foundation of logical reasoning** in computer science and mathematics. Mastering them will help you understand:

- Conditional logic
- Algorithms
- Programming decisions
- Mathematical proofs

---
