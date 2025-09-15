# Homework 2

## Problem 3.40
### (a) Kilam is a student
$S(\text{Kilam})$

### (b) All students are smart
$\forall s (S(s) \rightarrow I(s))$

### (c) No student is a friend of Kilam
$\forall s (S(s) \rightarrow \neg F(s, \text{Kilam}))$

### (d) Every student is a friend of some other student
$\forall a (S(a) \rightarrow \exists b (S(b)) \land a \neq b \land F(a,b)$

### (e) There is a student who is a friend of every other student
$\exists a (S(a)) \land \forall b ((S(b)) \land a \neq b) \rarr F(a,b)$

### (f) All smart students have a friend
$\forall s((S(s) \land I(s)) \rarr \exists b (S(b) \land F(s,b)))$

## Problem 3.44
### (a) 
$\exists x : (\forall y : x + 2y \neq 3)$\
The negation is true, therefore the original is false.

### (b)
$\forall x > 0 : (\exists y > 0 : xy \geq x)$

### (c)
$\forall (x,y) : (x + y \neq 13) \lor (xy \neq 36)$

## Problem 4.10
### (k) 3 divides $n - 2 \rarr n$ is not a perfect square
The contrapositive would be: If n is a perfect square, then $3$ does not divide $n - 2$.

**Proof**

$n = k^2$ where $k$ is some integer

Case 1: k is a multiple of 3.
$n = k^2 = (3m)^2 = 9m^2$
$n-2 = 9m^2 - 2 = 3(3m^2) - 2$
This will always have a remainder of -2 when divided by 3

Case 2: k has a remainder of 1 when divided by 3
$k = 3m + 1
n = (3m + 1)^2 = 9m^2 + 6m + 1
n - 2 = 9m^2 + 6m - 1 = 3(3m^2 + 2m) - 1$
This will always have a remainder of -1 when divided by 3

Case 3: k has a remainder of 2 when divided by 3
$k = 3m + 2
n = k^2 = (3m + 2)^2 = 9m^2 +12m + 4
n - 2 = 9m^2 + 12m + 2 = 3(3m^2 + 4m) + 2$
This will always have a remainder of 2 when divided by 3.

## Problem 4.13
### (i)
So we need to start by making the assumtion that the 8x8 chessboard with 32 dominos can not have a 2x2 square of dominos. This means there are no layouts where two horizontal dominos are adjacent and no vertical dominos are adjacent. There will be 32 white squares and 32 black squares on the board. Each domino must cover one of each color square. If $N_v$ is the total bumber of vertical dominos and the number of horizontal dominos on black rows is N H,black. the following must be true: $N_V + 2N_H,black = 32$


## Problem 4.44
### (a) Set Differences
The set difference A−B contains everything in set A that is not in set B.

i. For A={1,2,3,4} and B={2,4,6,8,10}:
A−B={1,3}
B−A={6,8,10}

ii. For A={multiples of 3} and B={prime numbers}:
A−B={6,9,12,15,...}
B−A={2,5,7,11,13,...} 

### (b) Expression for Set Difference
A−B=A∩B c
 


Here are the solutions to your set theory problems.


<!-- ## Markdown Math Cheat Sheet

**Instructions:** To type equations, wrap the LaTeX commands in dollar signs.
- Use single dollar signs for inline math: `$ ... $`
- Use double dollar signs for a centered equation block: `$$ ... $$`

### Logic and Predicates
| Symbol | Command | Description |
|:---:|:---|:---|
| $\forall$ | `\forall` | "For all" (Universal Quantifier) |
| $\exists$ | `\exists` | "There exists" (Existential Quantifier) |
| $\neg$ | `\neg` | "Not" (Negation) |
| $\land$ | `\land` | "And" (Conjunction) |
| $\lor$ | `\lor` | "Or" (Disjunction) |
| $\rightarrow$ | `\rightarrow` | "Implies" (Conditional) |
| $\leftrightarrow$ | `\leftrightarrow` | "If and only if" (Biconditional) |

### Set Theory
| Symbol | Command | Description |
|:---:|:---|:---|
| $\in$ | `\in` | "Is an element of" |
| $\notin$ | `\notin` | "Is not an element of" |
| $\subset$ | `\subset` | "Is a proper subset of" |
| $\subseteq$ | `\subseteq` | "Is a subset of" |
| $\cup$ | `\cup` | Union |
| $\cap$ | `\cap` | Intersection |
| $\emptyset$ | `\emptyset` | The empty set |
| $\mathbb{Z}$ | `\mathbb{Z}` | The set of all integers |
| $\mathbb{N}$ | `\mathbb{N}` | The set of natural numbers |

### Common Symbols & Formatting
| Example | Markdown Code | Description |
|:---:|:---|:---|
| $x^2$ | `$x^2$` | Superscript (Power) |
| $x_{i}$ | `$x_i$` | Subscript (Index) |
| $\frac{a}{b}$ | `$\frac{a}{b}$` | Fraction |
| $\sqrt{x}$ | `$\sqrt{x}$` | Square Root |
| $a \neq b$ | `$a \neq b$` | Not Equal |
| $a \leq b$ | `$a \leq b$` | Less Than or Equal To |
| $a \geq b$ | `$a \geq b$` | Greater Than or Equal To | -->