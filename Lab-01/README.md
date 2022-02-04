# Propositional Logic and Equivalences

# Hovedopgave 1

Section 1.1 in the book

## Underopgave 5

- Question
    - What is the negation of each of these propositions?
        - a) Mei has an MP3 player.
        - b) There is no pollution in New Jersey.
        - c) 2 + 1 = 3.
        - d) The summer in Maine is hot and sunny.
- Answer
    - a = It is not the case that Mei has an MP3 player
    - b = There is polution in new jersey
    - c = It is not the case that 2+1 is 3
    - It is not the case that the summer in Maine is hot and sunny

## Underopgave 13

- Question
    - Let p and q be the propositions
    p: It is below freezing.
    q: It is snowing.
    - Write these propositions using p and q and logical connectives (including negations).
    a) It is below freezing and snowing.
    b) It is below freezing but not snowing.
    c) It is not below freezing and it is not snowing.
    d) It is either snowing or below freezing (or both).
    e) If it is below freezing, it is also snowing.
    f ) Either it is below freezing or it is snowing, but it is not snowing if it is below freezing.
    g) That it is below freezing is necessary and sufficient for it to be snowing.
- Answer
    - A = p ∧ q
    - b =  p ∧ -q
    - c = -p ∧ -q
    - d = p ∨ q
    - e = p → q
    - f = (p ∨ q) ∧ (p → -q)
    - e = p ↔q

## Underopgave 31

- Question
    - How many rows appear in a truth table for each of these compound propositions?
    a) p → p
    b) (p ∨ r) ∧ (q ∨ s)
    c) q ∨ p ∨ s ∨ r ∨ t ∨ u
    d) (p ∧ r ∧ t) ↔ (q ∧ t)
- Answer
    - The number of rows can be obtained by N = 2^n where n = the number of propositional variables
    - a = 2^1 = 2
    - b = 2^4 = 16
    - c = 2^6 = 64
    - d = 2^5 = 32

## Underopgave 33 a–d

- Question
    - Construct a truth table for each of these compound propositions
        - a) p ∧ -p
        - b) p ∨ -p
        - c) (p ∨ -q) → q
        - d) (p ∨ q) → (p ∧ q)
- Answer
    - a:
        
        
        | p | -p | p ∧ -p  |
        | --- | --- | --- |
        | T | F | F |
        | F | T | F |
    - b:
        
        
        | p | -p | p ∨ -p |
        | --- | --- | --- |
        | T | F | T |
        | F | T | T |
    - c:
        
        
        | p | q | -q | p ∨ -q | (p ∨ -q) → q  |
        | --- | --- | --- | --- | --- |
        | T | T | F | T | T |
        | T | F | T | T | F |
        | F | T | F | F | T |
        | F | F | T | T | F |
    - d:
        
        
        | p | q | (p ∨ q) | (p ∧ q) | (p ∨ q) → (p ∧ q) |
        | --- | --- | --- | --- | --- |
        | T | T | T | T | T |
        | T | F | T | F | F |
        | F | T | T | F | F |
        | F | F | F | F | T |

# Hovedopgave 2

Section 1.3 in the book

## Underopgave 6

- Question
    - Use a truth table to verify the first De Morgan law -(p ∧ q) ≡ -p ∨ -q
- Answer
    
    
    | p | q | -p | -q | (p ∧ q) | -(p ∧ q) | -p ∨ -q |
    | --- | --- | --- | --- | --- | --- | --- |
    | T | T | F | F | T | F | F |
    | T | F | F | T | F | T | T |
    | F | T | T | F | F | T | T |
    | F | F | T | T | F | T | T |

## Underopgave 7

- Question
    - Use De Morgan’s laws to find the negation of each of the following statements.
    a) Jan is rich and happy.
    b) Carlos will bicycle or run tomorrow.
    c) Mei walks or takes the bus to class.
    d) Ibrahim is smart and hard working.
- Answer
    - a = (p∧q) = ¬p∨¬q. Or, by words, Jan is not rich, or not happy, or both
    - b = (p∨q) = ¬p∧¬q. Or, by words, Carlos will neither bicykle or run tomorrow
    - c = (p∨q) = ¬p∨¬q.  Or, by words, Mei will neither walk or take the bus to class.
    - d = (p∧q) = ¬p∨¬q. Or, by words, Ibrahim is neither smart nor hardworking

## Underopgave 19

- Question
    - Determine whether (-q ∧ (p → q)) → -p is a tautology.
- Answer
    - It is a taulogy since no matter of truth value of p or q, the stetement ¬𝑞∧(𝑝→𝑞)→¬𝑝¬q∧(p→q)→¬p is always true, hence it is a tautology.
    
    | p | q | p → q | -q | -q ∧ (p → q) | -p | -q ∧ (p → q)) → -p |
    | --- | --- | --- | --- | --- | --- | --- |
    | T | T | T | F | F | F | T |
    | T | F | F | T | F | F | T |
    | F | T | T | F | F | T | T |
    | F | F | T | T | T | T | T |

# Hovedopgave 3

**(TRUE) / (FALSE)**

- (a) Hvis p er sand, og q er falsk, er p ∧ q sand.  **(FALSE)**
- (b) Hvis p er falsk, er p ∨ q sand. **(TRUE)**
- (c) Hvis p er sand, og q er falsk, er p ⊕ q sand. **(TRUE)**
- (d) Hvis p ∨ q er sand, er p ogs nødvendigvis sand. **(FALSE)**
- (e) p ∨ q er sand, hvis og kun hvis p er sand. **(FALSE)**
- (f) Hvis p ∧ q er sand, er p ∨ q ogs sand. **(TRUE)**
- (g) Hvis p ⇒ q er sand, og p er sand, er q ogs sand. **(FALSE)**
- (h) Hvis p ⇒ q er sand, og q er falsk, er p ogs falsk.  **(TRUE)**

| p | q | p→q |
| --- | --- | --- |
| T | T | T |
| T | F | F |
| F | T | T |
| F | F | T |