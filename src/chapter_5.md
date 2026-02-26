# Chapter 5:  Zarmelo-Russel Set Theory

*Please skip this chapter unless you understand set notation*

## CHAPTER 5.1 - Axioms
The axioms of Zarmelo-Russel Set Theory are as follows:
1. **Extensionality.** If $X$ and $Y$ have the same elements, then $X = Y$.

$$\forall u (u \in X \equiv u \in Y) \implies X = Y$$

2. **Unordered Pairs.** For any $a$ and $b$ there exists a set $\lbrace a, b\rbrace$ that contains exactly $a$ and $b$.

$$\forall a \forall b \exists c \forall x (x \in c \equiv (x = a \vee x = b))$$

3. **Subsets.** If $\phi$ is a property with parameter $p$, then for any $X$ and $p$ there exists a set $Y = \lbrace u \in X : p(u, \phi)\rbrace$ that contains all those $u \in X$ that have the parameter $p$. 

$$\forall X \forall p \exists Y \forall u (u \in y \equiv (u \in X \vee p(u, \phi)))$$

4. **The Sum Set.** For any $X$, a set of sets, there exists a set $ Y = \cup X$, the union of all elements of each element of $X$.

$$\forall X \exists Y \forall u(u \in Y \equiv \exists z (u \in X \wedge z \in u))$$

5. **The Power Set**. For any $X$ there exists a set $Y = P(X)$, the set of all subsets of $X$.

$$\forall X \exists Y \forall u (u \in Y \equiv u \subsetneq X))$$

6. **Infinity.** There exist an infinite sequence infinite sets with decreasing cardinality.

$$\forall X \exists Y \space C(X) > C(Y) \wedge C(Y) \ge \aleph_{0}$$

7. **Replacement.** If $X$ is a set, then for any $Y$ there exists a function $F$ such that $F[X] = Y$

$$\forall X \forall Y \exists F (F(X) = Y)$$


8. **Consistancy.** The set of all sets that don't contain themselves does not contain itself.

$$\forall P \neg \Gamma \vdash P \wedge \neg P$$

*Note: these axioms are here for reference, and should be taken as absolute truth (they are axioms, after all). Do not try to prove them.*
