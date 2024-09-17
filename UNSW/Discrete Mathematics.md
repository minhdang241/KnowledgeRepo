# Set

> Definition: is an unordered collection of distinct objects.

**Set comprehension**:
$$\{x\ |\ some\ conditions\ on\ x\}$$
**Note:** '|' == ':' == 'such that'.

**Set comparison**:
- Set A and B have exactly the same members: $$ A = B $$
- All members of A are also member of B: $$ A \subseteq B$$
- When members of A are also member of B, and A != B, A is a proper subset of B: $$ A \subset B$$
**Proof**
> Definition: is a sequence of statements of the form "if (some hypotheses) the (a conclusion)"

Common Operation:
**Intersection:** 
$$\bigcap_{i=1}^{n} A_i = \{x \mid x \in A_i \text{ for every } i \}$$
**Union**:
$$\bigcup_{i=1}^{n} A_i = \{x \mid x \in A_i \text{ for some } i \}$$
> A and B are disjoint 

**Algebraic laws:** equations involving union and intersection that hold for all sets
- idempotence laws: $$A \cup A = A,\qquad 
  A\cap A = A$$
- commutative laws: $$A \cup B = B \cup A,\qquad A \cap B = B\cap A$$
- associative laws: $$(A \cup B) \cup C = B \cup (A\cup C), \qquad (A \cap B)\cap C = A \cap (B \cap C)$$
- distributed laws: $$A\cup (B\cap C) = (A\cup B) \cap (A\cup C), \qquad A\cap (B\cup C) = (A\cap B) \cup (A\cap C)$$
- one and zero laws: $$A\cup \emptyset = A, \qquad A\cap \emptyset = \emptyset$$
**Complements**
> Definition: The relative complement of B in A, is the set whose elements are in A but not in B

$$A\setminus B = \{x \mid x \in A \ and\ x \notin B\}$$

**Symmetric difference**
> Definition: The symmetric difference of A and B, is the set whose elements are in one, but not both, of A and B

$$A \oplus B = \{x \mid ( x \in A\ and\ x \notin B)\ or\ (x \in B\ and\ x \notin A)\}$$

**Cartesian product**:
$$A \times B = \{(x,y) \mid x \in A\ and\ y \in B\}$$
**Power set**
> Definition: If A is a set then the power set of A is the set of all subsets of A
$$\mathscr{P}(A) = \{B \mid B \subseteq A\}$$

**Cardinality**
> Definition: the size of a set $$|A|$$

When A is a finite set, this is the number of elements.

**Bags**:
> Definition: this is an unordered collections of objects where duplicates **are allowed**. $$\{1,1,2,3\}$$

