# dismathportfolio-cellixsantos
dismathportfolio-cellixsantos created by Classroom for GitHub


## WEEK 1:

- We are introduced to the subject by the professor
- He talked about what is a proof
- A proof of a proposition is a chain of logical deductions leading to the proposition from a base set of axioms
- Proposition is a statement which is either true or false
- And an axiom is a statement that is self true
- We were taught about lots of 'P's and 'Q's
- The subject was very confusing
- I was tought about **Logical Connectives**.

| Logical Symbol  |  Logical Operator     | Shorthand | Formula                                       | Logical Expression            |
| :-------------: |:---------------------:|:---------:|:---------------------------------------------:|:-----------------------------:|
| ¬               | Negation              | not       | val(¬p) = 1 - val(p)                          | ¬p                            |
| ∧               | Conjunction           | and       | val(p ∧ q) = min(val(p), val(q))              | p ∧ q                         |
| v               | Disjunction           | or        | val(p v q) = max(val(p), val(q))              | p v q                         |
| ⊕               | Exclusive disjunction | xor       | if val(p) not equal val(q) = 1, otherwise 0   | p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q)  |
| →               | Conditional           | if, then  | if val(p) ≤ val(q) = 1, otherwise 0           | p → q ≡  ¬p v q               |
| ↔               | Biconditional         | iff       | if val(p) equals val(q) = 1, otherwise 0      | p ↔ q ≡ (p → q) ∧ (q → p)     |


## Week 2:

### LOGICAL EQUIVALENCES

 I learned about a new topic in DISMATH called **Logical Equivalences**.
 
|  **LAW**  |  **EQUIVALENCE**  |
| :------: | :-----------------------------: |
|  _Identity Laws_  |  p ∨ F ≡ p  ;;  p ∧ F ≡ p  |
|  _Domination Laws_  |  p ∨ T ≡ T  ;;  p ∧ F ≡ F  |
|  _Negation Laws_  |  p ∨ ¬p ≡ T  ;;  p ∧ ¬p ≡ F  |
|  _Double Negation Law_  |  ¬(¬p) ≡ p  |
|  _Idempotent Laws_  |  p ∨ p ≡ p  ;;  p ∧ p ≡ p  |
| _Distributive Laws_  |  p ∨ (q ∧ r) ≡ (p ∨ q) ∧ (p ∨ r)  ;;  p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (p ∧ r)  |
|  _Commutative Laws_  |  p ∨ q ≡ q ∨ p  ;;  p ∧ q ≡ q ∧ p  |
|  _Associative Laws_  |  (p ∨ q) ∨ r ≡ p ∨ (q ∨ r)  ;;  (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)  |
|  _De Morgan's Laws_  |  ¬(p ∧ q) ≡ ¬p ∨ ¬q  ;;  ¬(p ∨ q) ≡ ¬p ∧ ¬q  |
|  _Absorption Laws_  |  p ∨ (p ∧ q) ≡ p  ;;  p ∧ (p ∨ q) ≡ p  |

- I also learned about **Propositional Logic** and **Quantifiers**. 
- Propositional Logic deals with proposition as a whole. (Subject + Predicate)
- Quantifiers indicates the generality of an open sentence in which a variable occurs.
- Quantifiers have two classifications, one being Existential Quantifiers (∃x) which means "There exist" and the other being Universal Quantifiers (∀x) which means "For all".
- I was tought how to use the implication equivalence "p → q ≡  ¬p v q" in evaluating

## Week 3:
- During this week, I was introduced to a topic called **Rules of Inference**.
- I was tought about arguments and to see if they are valid or a fallacy

### RULES OF INFERENCE TABLE   

|  **TYPE**  |  **RULE OF INFERENCE**  |  **TAUTOLOGY**  |
| -------: | :--------------: | :--------- |
|  _Modus Ponens_  |  p, p → q ∴ q  |  (p ∧ (p → q)) → q  |
|  _Modus Tollens_  |  ¬q, p → q ∴ ¬p |  (¬q ∧ (p → q)) → ¬p  |
|  _Hypothetical Syllogism_  |  p → q, q → r ∴ p → r  |  ((p → q) ∧ (q → r)) → (p → r)  |
|  _Disjunctive Syllogism_  |  p ∨ q, ¬p ∴ q  |  ((p ∨ q) ∧ ¬p) → q  |
|  _Addition_  |  p ∴ p ∨ q  |  p → p ∨ q  |
|  _Simplification_  |  p ∧ q ∴ p  |  (p ∧ q) → p  |
|  _Conjunction_  |  p, q ∴ p ∧ q  |  ((p) ∧ (q)) → (p ∧ q)  |
|  _Resolution_  |  p ∨ q, ¬p ∨ r ∴ q ∨ r  |  ((p ∨ q) ∧ (¬p ∨ r)) → q ∨ r  |


## WEEK 4:

- Our professor discussed about the different **Methods of Proof**.

### Methods of Proof

|  **TYPE**  |  **Way to solve**  |
| -------: | :--------------: |
|  _Direct Proof_  |  1. Assume that p is true  |
|   |  2. Show that q is true (based on 1.)  |
|  _Proof by Contraposition_  |  1. Assume ¬q is true |
|    |  2. Show that ¬p is also true |
|  _Vacuous Proof_  |  Show that the p is false to make p → q true|
|  _Trivial proof_  |  Show that q is true, it follows that p → q is also true  |
|  _Proof by Contradiction_  |  1. Assume that the premise is not true |
|   |  2. Show that 1. will end up in a contradiction |
|  _Proof by Equivalence_  |  Prove that p → q and q → p is true using any of the previous methods of proof|
|

## WEEK 5:

**Mathematical Induction**
-P(1), P(2), P(3), ... ,P(k), P(k+1)
**Induction step**
- 1.Basis
   - Show to P(1) or P(0) to betrue
- 2.Direct proof
   - a. Assume P(k) to be true
   - b. Show that P(k+1) is also true

## WEEK 6:
* **SUMMATION**
    - The notation for sum of _a<sub>m</sub>, a<sub>m+1</sub>, ..., a<sub>n</sub>_ is _∑<sup>a</sup><sub>i=m </sub>a<sub>i</sub>_ where _i_ is the index of summation.

* **RECURSIVE/INDUCTIVE DEFINITION**
    - Basis step: Specify the value of the function at zero
    - Recursive step: Give a rule for finding its value at an integer from its values at smaller integers

* **RECURSIVE ALGORITHMS**
    - It solves a problem by reducing it to an instance of the same problem with smaller input.
        - Recall: <u>Algorithm</u> - finite set of precise instructions for performing a computation/solving a problem.

* **PROGRAM CORRECTNESS**
    - We need a proof to show that the program always gives the correct output.
        - PROGRAM VERIFICATION
            - Proof of correctness of programs
            - Uses the rules of inference and various proof techniques including mathematical induction
            - It is said to be correct if it produces the correct output for every possible input:
                1. Show that the correct answer is obtained if the program terminates (Partial Correctness)
                2. Show that the program always terminates
        - PARTIAL CORRECTNESS
            - Two propositions are used to specify what it means for a program to produce the correct output:
                1. Initial Assertion - _p_ - gives the properties that the input values must have
                2. Final Assertion - _q_ - gives the properties that the output of the program should have, if the program did what it was told

* **HOARE TRIPLE**
    - p{s}q
    - A program, _S_, is said to be partially correct with respect to the initial assertion _p_ and the final assertion _q_ if whenever _p_ is true for the input values of _S_ and _S_ terminates, then _q_ is true for the output values of _S_.

* **RULES OF INFERENCE**
    - CONDITIONAL STATEMENTS </br>
        (p ∧ _condition_) {S} q </br>
        (p ∧ _¬condition_) → q </br>
        ∴ p {**if** _condition_ **then** _S_} q

    - IF-ELSE STATEMENT </br>
        (p ∧ _condition_) {S<sub>1</sub>} q </br>
        (p ∧ _¬condition_) {S<sub>2</sub>} q </br>
        ∴ p {*if* _condition_ *then* _S<sub>1</sub>_ *else* _S<sub>2</sub>_} q

* **POWER SERIES**
    - ∑<sup>∞</sup><sub>n = 0</sub> a<sub>n</sub>x<sup>n</sup> </br>
        where _a<sub>0</sub>, a<sub>1</sub>, a<sub>2</sub>, ..._ is a given sequence of constants, and _x_ is a real variable.

-Then we did our quiz on friday which is really hard

## WEEK 7:
-I received the score of my quiz and found out I had a really low score so I should work hard for the next one
-The lessons that were discussed this week
* **Set theories**
    -{  ,  ,  ,  }
     ex. {0,2,4,6...}
    -Where Ø is an empty set {}
    -{Ø} is a set with an empty set and is not the same as Ø
    -Union is all the elements in 2 sets
    -Intersection is the common elements in the 2 sets
    -Complement is the elements not in a set
    -Symmetric difference is elements which are not common within the 2 sets

* **SET IDENTITIES TABLE**

|  **LAW**  |  **IDENTITY**  |
| :------: | :-----------------------------: |
|  Identity Laws  |  A ⋂ U ≡ A  <br>  A ⋃ ∅ ≡ A  |
|  Domination Laws  |  A ⋃ U ≡ U  <br>  A ⋂ ∅ ≡ ∅  |
|  Idempotent Laws  |  A ⋃ A ≡ A  <br>  A ⋂ A ≡ A  |
|  Complementation Law  |  (A¯)‾ ≡ A  |
|  Commutative Laws  |  A ⋃ B ≡ B ⋃ A  <br>  A ⋂ B ≡ B ⋂ A  |
|  Associative Laws  |  A ⋃ (B ⋃ C) ≡ (A ⋃ B) ⋃ C  <br>  A ⋂ (B ⋂ C) ≡ (A ⋂ B) ⋂ C  |
|  Distributive Laws  |  A ⋃ (B ⋂ C) ≡ (A ⋃ B) ⋂ (A ⋃ C) <br>  A ⋂ (B ⋃ C) ≡ (A ⋂ B) ⋃ (A ⋂ C)  |
|  De Morgan's Laws  |  (A ⋂ B)‾ ≡ A‾ ⋃ B‾  <br>  (A ⋃ B)‾ ≡ A‾ ⋂ B‾  |
|  Absorption Laws  |  A ⋃ (A ⋂ B) ≡ A  <br>  A ⋂ (A ⋃ B) ≡ A  |
|  Complement Laws  |  A ⋃ A‾ ≡ U  <br>  A ⋂ A‾ ≡ ∅  |

* **SUBSETS ⊆**
   -is a set that can be made from another set where they have the same elements
* **POWER SET P( )**
   -is a set of all possible subsets
* **CARDINALITY | |**
   -is the number of elements a set contains
   -duplicates of a element in a set is not counted
   -If the cardinaly is too high or infinite ex. cardinality of all natural numbes |ℕ| we use aleph-naught ![Image](https://upload.wikimedia.org/math/b/e/4/be4c703ed73456618ed283b892c6715a.png)

* **FUNCTIONS**
  - Let A and B be sets. A function f from A to B is an assignment of exactly one element of B to each element of A.
  -  Functions are also called MAPPINGS or TRANSFORMATIONS.
    - f: A to B </br>
       A: domain </br>
       B: co-domain
    - Range - actually occuring values
    - IMAGE
      - If _f(a) = b_, _b- is the image of _A_.
      - The range of _f_ is the set of all images of elements of _a_.

* **TYPES OF FUNCTIONS**
    - One - to - one Function (Injection)
      - like the name implies only one element of x can be assigned to y and vise versa
    - Onto Function (Surjective)
      - functions have equal range & co-domain.
    - One - to - one Correspondence (Bijection)
     - function is both one - to - one and onto.
## WEEK 8:
-We learned about algorithms one of the most confusing lessons in Dismath
* **Properties**
      - INPUT - has input values from a specified set 
      - OUTPUT - solution to the problem 
      - DEFINITENESS - defined precisely 
      - CORRECTNESS - produce the correct output values 
      - FINITENESS - produce the desired output 
      - EFFECTIVENESS - perform exactly and in a finite amount of time 
      - GENERALITY - applicable for all problems of the desired form
* **PSEUDOCODE**
   -its like coding what we did in LBYEC71 on paper that can be understood by humans
   -it has preconditions and postconditions
## WEEK 9:
-We were thought about different algorithms which are Searching, Sorting, and Greedy Algorithms
*Searching Algorithm*
  -Used for finding an elemenent in a ordered list
  -There are 2 types that we learned
    -Linear Search- Finding the element one by one throughout the list
    -Binary Search- Comparing middle values of the list until the element is found
*Sorting Algorithm*
  - used for assorting elements in increasing order
    - Bubble Sort - compares the first two elements then interchanging them if they are in the incorrect order.
    - Insertion Sort - compares the second element with the first and inserts it before the first element if it is less. Otherwise, it is inserted after the first element.
*Greedy Algorithm*
  - -an algorithm that starts with the "best" choice at each step to lead to an optimal solution.
 
## WEEK 10:
-We learned about growth of functions
- Big-O Notation
    - Let f and g be functions from R-R; _f(x)_ is _O(g(x))_ if there are constants C and k such that:
        |f(x)| ≤ C|g(x)| 
    whenever x > k.

- Big-Omega and Big-Theta Notation
    - Big-O Notation does not provide a lowerbound for the size of f(x). 
        - Big-Omega (Big-Ω) - lower bound
        - Big-Theta (Big-Θ) - both upper and lower bound

- Algorithm Time Complexity - can be expressed in terms of the number of operations used by the algorithm when the input has a particular size.

- Division and Modulo Operator
  - let a be an integer and d positive integer. Then there is a unique Q and r with 0 ≤ r < d such that a = dQ + r
  - Q = a div d
  - r = a mod d

-We did our second quiz on friday
