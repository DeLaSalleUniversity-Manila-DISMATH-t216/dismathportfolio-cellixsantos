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
    - Example: ∑<sup>a</sup><sub>i=m </sub> = 1 + 2 + 3 + ... + n
    - We also proved the theorem: The sum of the first n powers of two is _2<sup>n</sup>-1_.

* **RECURSIVE/INDUCTIVE DEFINITION**
    - Basis step: Specify the value of the function at zero
    - Recursive step: Give a rule for finding its value at an integer from its values at smaller integers
    - Example: Find _f(1), f(2), f(3), f(4)_ of the following recursive function.

* **RECURSIVE ALGORITHMS**
    - It solves a problem by reducing it to an instance of the same problem with smaller input.
        - Recall: <u>Algorithm</u> - finite set of precise instructions for performing a computation/solving a problem.
    - Examples:
        - What is the recursive algorithm _n!_?
        - Give a recursive algorithm for computing _a<sup>n</sup>_, where _a_ is a nonzero real number and _n_ is a nonnegative integer.

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
    - Example: Given the initial assertion _p: x=1_ and the final assertion _q: z=3_, show the partial correctness of the program segment: </br> y = 2 </br> z = x + y

* **RULES OF INFERENCE**
    - CONDITIONAL STATEMENTS </br>
        (p ∧ _condition_) {S} q </br>
        (p ∧ _¬condition_) → q </br>
        ∴ p {**if** _condition_ **then** _S_} q
        - Example: Verify that the following program segment is correct with respect to the initial assertion _T_ and the final assertion _y ≥ x_. </br>
            **if** _x>y_ **then** </br>
            _y=x_
    - IF-ELSE STATEMENT </br>
        (p ∧ _condition_) {S<sub>1</sub>} q </br>
        (p ∧ _¬condition_) {S<sub>2</sub>} q </br>
        ∴ p {*if* _condition_ *then* _S<sub>1</sub>_ *else* _S<sub>2</sub>_} q
        - Example: **if** _x<0_ **then** </br> _abs= -x_ </br> **else** </br> _abs = x_

* **POWER SERIES**
    - ∑<sup>∞</sup><sub>n = 0</sub> a<sub>n</sub>x<sup>n</sup> </br>
        where _a<sub>0</sub>, a<sub>1</sub>, a<sub>2</sub>, ..._ is a given sequence of constants, and _x_ is a real variable.
    - Examples:
        - 1 + r + r<sup>2</sup> + r<sup>3</sup> + ... = 1/(1-r)
        - Represent as power series: 1/(1+x)
        - Find the corresponding function: 1 - x<sup>2</sup> + x<sup>4</sup> - x<sup>6</sup> + ...
## WEEK 7:

## WEEK 8:

## WEEK 9:
