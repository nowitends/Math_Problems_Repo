# Problem 1

## Short theory (sets as events)

In probability, an **event** is a **subset** of the sample space $\Omega$ (the set of all elementary outcomes). So we use normal **set operations**:

### Most useful definitions / formulas

**Union** (“$A$ or $B$”):
$$
A\cup B={\omega\in\Omega:\ \omega\in A\ \text{or}\ \omega\in B}
$$

**Intersection** (“$A$ and $B$”):
$$
A\cap B={\omega\in\Omega:\ \omega\in A\ \text{and}\ \omega\in B}
$$

**Difference** (“in $B$ but not in $A$”):
$$
B\setminus A={\omega\in B:\ \omega\notin A}
$$
and similarly
$$
A\setminus B={\omega\in A:\ \omega\notin B}.
$$

---

## Step-by-step solution

Given:
$$
\Omega={\omega_1,\omega_2,\omega_3,\omega_4,\omega_5},
$$
$$
A={\omega_1,\omega_3,\omega_5},\quad
B={\omega_2,\omega_3,\omega_4}.
$$

---

### 1) Find $A\cup B$

**Step 1:** Take all elements from $A$:
$$
{\omega_1,\omega_3,\omega_5}
$$

**Step 2:** Add all elements from $B$ that are not yet included:

* $B$ has $\omega_2,\omega_3,\omega_4$
* $\omega_3$ is already there, so add $\omega_2,\omega_4$

So:
$$
A\cup B={\omega_1,\omega_2,\omega_3,\omega_4,\omega_5}=\Omega.
$$

---

### 2) Find $A\cap B$

**Step 1:** Look for outcomes that appear in **both** sets.

* In $A$: $\omega_1,\omega_3,\omega_5$
* In $B$: $\omega_2,\omega_3,\omega_4$

The only common element is $\omega_3$, so:
$$
A\cap B={\omega_3}.
$$

---

### 3) Find $B\setminus A$

This means: **keep what’s in $B$, remove what is also in $A$.**

**Step 1:** Start with $B$:
$$
B={\omega_2,\omega_3,\omega_4}
$$

**Step 2:** Remove elements that are in $A={\omega_1,\omega_3,\omega_5}$.

* $\omega_3$ is in $A$, so remove it.

Result:
$$
B\setminus A={\omega_2,\omega_4}.
$$

---

### 4) Find $A\setminus B$

This means: **keep what’s in $A$, remove what is also in $B$.**

**Step 1:** Start with $A$:
$$
A={\omega_1,\omega_3,\omega_5}
$$

**Step 2:** Remove elements that are in $B={\omega_2,\omega_3,\omega_4}$.

* $\omega_3$ is in $B$, so remove it.

Result:
$$
A\setminus B={\omega_1,\omega_5}.
$$

---

## Final answers

$$
A\cup B={\omega_1,\omega_2,\omega_3,\omega_4,\omega_5}
$$

$$
A\cap B={\omega_3}
$$

$$
B\setminus A={\omega_2,\omega_4}
$$

$$
A\setminus B={\omega_1,\omega_5}
$$
