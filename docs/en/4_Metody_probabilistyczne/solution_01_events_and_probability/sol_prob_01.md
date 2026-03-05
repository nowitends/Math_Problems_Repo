# Problem 1

## Short theory (sets as events)

In probability, an event is a **subset of the sample space** $\Omega$ (the set of all elementary outcomes).  
Therefore, events are manipulated using **set operations**.

### Most useful definitions / formulas

**Union ("A or B")**

$$
A \cup B = \{\omega \in \Omega : \omega \in A \text{ or } \omega \in B\}
$$

**Intersection ("A and B")**

$$
A \cap B = \{\omega \in \Omega : \omega \in A \text{ and } \omega \in B\}
$$

**Difference ("in B but not in A")**

$$
B \setminus A = \{\omega \in B : \omega \notin A\}
$$

Similarly

$$
A \setminus B = \{\omega \in A : \omega \notin B\}
$$

---

# Step-by-step solution

Given the sample space

$$
\Omega = \{\omega_1, \omega_2, \omega_3, \omega_4, \omega_5\}
$$

Events:

$$
A = \{\omega_1, \omega_3, \omega_5\}
$$

$$
B = \{\omega_2, \omega_3, \omega_4\}
$$

---

## 1. Union of events $A \cup B$

The union contains all elements that belong to **at least one** of the events.

Take all elements from $A$:

$$
\{\omega_1, \omega_3, \omega_5\}
$$

Add elements from $B$ that are not yet included:

$$
\omega_2, \omega_4
$$

Therefore

$$
A \cup B = \{\omega_1, \omega_2, \omega_3, \omega_4, \omega_5\}
$$

This equals the whole sample space:

$$
A \cup B = \Omega
$$

---

## 2. Intersection of events $A \cap B$

The intersection contains elements belonging to **both sets**.

Compare the sets:

$$
A = \{\omega_1, \omega_3, \omega_5\}
$$

$$
B = \{\omega_2, \omega_3, \omega_4\}
$$

The only common element is

$$
\omega_3
$$

Thus

$$
A \cap B = \{\omega_3\}
$$

---

## 3. Difference of events $B \setminus A$

Take elements from $B$ but remove those that appear in $A$.

Start with

$$
B = \{\omega_2, \omega_3, \omega_4\}
$$

Since

$$
\omega_3 \in A
$$

remove it.

Therefore

$$
B \setminus A = \{\omega_2, \omega_4\}
$$

---

## 4. Difference of events $A \setminus B$

Take elements from $A$ but remove those that appear in $B$.

Start with

$$
A = \{\omega_1, \omega_3, \omega_5\}
$$

Since

$$
\omega_3 \in B
$$

remove it.

Thus

$$
A \setminus B = \{\omega_1, \omega_5\}
$$

---

# Final results

$$
A \cup B = \{\omega_1,\omega_2,\omega_3,\omega_4,\omega_5\}
$$

$$
A \cap B = \{\omega_3\}
$$

$$
B \setminus A = \{\omega_2,\omega_4\}
$$

$$
A \setminus B = \{\omega_1,\omega_5\}
$$