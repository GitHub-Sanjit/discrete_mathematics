# Part 3: Propositional Logic, Propositional Variables, and Compound Propositions

## 📌 Overview

In this section, we study how simple statements (called propositions) can be combined or modified to create more complex logical expressions. This is the foundation of **Discrete Mathematics** and is widely used in programming, algorithms, and reasoning systems.

---

# 1. What is Propositional Logic?

**Definition:**

Propositional Logic is the branch of logic that deals with propositions and how they can be combined or modified to form more complex statements. It also studies the relationships between these statements.

👉 In simple words:

> Propositional Logic is about **building complex logical statements from simple ones and analyzing their truth**.

---

## 🔍 Understanding the Definition

Let’s break it down using examples.

### Example 1: Combining Statements

- Statement 1:  
  "Adam is good at playing football."

- Statement 2:  
  "Adam is good at playing football, and this time he is representing his college at the national level."

👉 What happened here?

- We **combined two ideas** using the word **"and"**
- This creates a **compound statement**

---

### Example 2: Modifying Statements

- Statement 3:  
  "I enjoy watching television."

- Statement 4:  
  "It is not the case that I enjoy watching television."

👉 What happened here?

- We **modified** the original statement
- We used **negation (NOT)**

---

## 📌 Important Fact

Propositional Logic is also known as:

- **Sentential Logic**
- **Statement Logic**

---

# 2. Compound Propositions

## 📌 Definition

A **compound proposition** is formed by combining one or more simple propositions using logical operators.

---

## 🔧 Common Logical Operators

| Operator | Symbol | Meaning        | Example              |
|----------|--------|----------------|----------------------|
| AND      | ∧      | Both must be true | p ∧ q |
| OR       | ∨      | At least one true | p ∨ q |
| NOT      | ¬      | Negation        | ¬p |
| IMPLIES  | →      | If...then       | p → q |
| IFF      | ↔      | If and only if  | p ↔ q |

---

## ✅ Example

Let:

- p: Adam is good at football  
- q: Adam represents his college  

Then:

- **p ∧ q** → "Adam is good at football AND represents his college"

---

## 🤔 Why Do We Need Compound Propositions?

Because most real-world and mathematical statements are not simple.

👉 Example:

- "If it rains, then I will not go outside."

This cannot be expressed using a single simple proposition.

---

# 3. Modifying Propositions

## 📌 Negation (NOT)

Negation changes the truth value of a statement.

| Original (p) | Negation (¬p) |
|-------------|--------------|
| True        | False        |
| False       | True         |

---

## ✅ Example

- p: "I enjoy watching television."
- ¬p: "I do NOT enjoy watching television."

---

## ⚠️ Key Idea

Negation simply **reverses the meaning** of a proposition.

---

# 4. Propositional Variables

## 📌 Definition

Propositional variables are symbols used to represent propositions.

👉 Instead of writing long sentences, we use variables like:

- p
- q
- r

---

## 🔍 Why Use Variables?

Because it makes expressions:

- Shorter
- Easier to analyze
- More mathematical

---

## ✅ Example

Instead of writing:

> "Adam is good at playing football, and this time he is representing his college at the national level."

We write:

- p = Adam is good at playing football  
- q = He represents his college  

Then:

- **p ∧ q**

---

## 📌 Key Insight

> Propositional variables allow us to focus on the **structure of logic**, not the length of sentences.

---

# 5. Summary

- A **proposition** is a statement that is either true or false.
- **Propositional Logic** studies how to combine and modify these statements.
- **Compound propositions** are formed using logical operators like AND, OR, NOT.
- **Negation** modifies a statement by reversing its truth.
- **Propositional variables** (p, q, r) simplify complex expressions.

---

# 🧠 Final Intuition

Think of propositional logic like **programming with truth values**:

- Variables → store statements  
- Operators → combine logic  
- Result → new logical meaning  

---

# 🚀 What's Next?

After this topic, you should learn:

- Truth Tables
- Logical Equivalences
- Laws of Logic (De Morgan’s Laws, etc.)

---
# Propositional Logic: Practice Problems & Truth Table Cheat Sheet

---

# 🧠 Part 1: Practice Problems

## 🔹 Section A: Identify Propositions

Determine whether each sentence is a **proposition** or **not a proposition**.

1. "The sky is blue."
2. "Close the door."
3. "x + 5 = 10"
4. "Dhaka is the capital of Bangladesh."
5. "What time is it?"

👉 *Hint:* A proposition must be either **true or false**, not a question or command.

---

## 🔹 Section B: Assign Propositional Variables

Rewrite the following statements using variables:

1. "It is raining and I am happy."
2. "I will study or I will fail."
3. "It is not hot today."

👉 Example:

- p = It is raining  
- q = I am happy  
- Expression: **p ∧ q**

---

## 🔹 Section C: Translate into Logical Form

Convert the statements into symbolic logic:

1. "Adam plays football and represents his college."
2. "It is not the case that I enjoy watching TV."
3. "Either I will go to class or I will stay home."

---

## 🔹 Section D: Negation Practice

Write the negation of each statement:

1. "It is raining."
2. "I am happy."
3. "He is a student."

👉 Example:

- p: "It is raining"  
- ¬p: "It is NOT raining"

---

## 🔹 Section E: Build Compound Statements

Let:

- p = I study  
- q = I pass  

Write the meaning of:

1. p ∧ q  
2. p ∨ q  
3. ¬p  
4. p → q  
5. p ↔ q  

---

## 🔹 Section F: Challenge Questions

1. If:
   - p = "It is raining"
   - q = "I carry an umbrella"

   Write:
   - "If it is raining, then I carry an umbrella."

2. Express:
   - "I will not go outside if it is raining."

---

# 📊 Part 2: Truth Table Cheat Sheet

---

## 🔹 1. Negation (NOT)

| p | ¬p |
|---|----|
| T | F  |
| F | T  |

👉 Meaning: Reverses the truth value

---

## 🔹 2. AND (∧)

| p | q | p ∧ q |
|---|---|-------|
| T | T | T     |
| T | F | F     |
| F | T | F     |
| F | F | F     |

👉 True only when **both are true**

---

## 🔹 3. OR (∨)

| p | q | p ∨ q |
|---|---|-------|
| T | T | T     |
| T | F | T     |
| F | T | T     |
| F | F | F     |

👉 True when **at least one is true**

---

## 🔹 4. Implication (→)

| p | q | p → q |
|---|---|-------|
| T | T | T     |
| T | F | F     |
| F | T | T     |
| F | F | T     |

👉 Only false when:
- p is TRUE and q is FALSE

---

## 🔹 5. Biconditional (↔)

| p | q | p ↔ q |
|---|---|-------|
| T | T | T     |
| T | F | F     |
| F | T | F     |
| F | F | T     |

👉 True when both have the **same truth value**

---

# ⚡ Quick Memory Tricks

- **AND (∧)** → "Both must be true"
- **OR (∨)** → "At least one is true"
- **NOT (¬)** → "Opposite"
- **→ (Implies)** → "Only false when T → F"
- **↔ (IFF)** → "Same truth values"

---

# 🧪 Mini Self-Test

1. If p = T and q = F, what is:
   - p ∧ q = ?
   - p ∨ q = ?
   - p → q = ?

2. If p = F, what is:
   - ¬p = ?

---

# 🎯 Final Tip

Practice translating **English → Logic → Truth Table**

That’s the core skill in Discrete Mathematics.

---
