# Quantifiers

# Hovedopgave 1

Angiv for hvert af de følgende par af udsagn, om: 

(a) ⇒ (b), (b) ⇒ (a), (a) ⇔ (b) eller ingen af delene.

| a | b | udsagn |
| --- | --- | --- |
| (a) p∨q | (b) p∧q |  |
| (a) ¬p∨q | (b) p⇒q |  |
| (a) ¬(p∧q) | (b) p∨q |  |
| (a) (p∨q)∧(p∨r) | (b) p∨(q∧r) |  |
| (a) ¬p⇒q | (b) ¬q⇒p |  |

# Hovedopgave 2

Afsnit 1.4: 

## Underopgave 5

- Let P(x) be the statement *“x spends more than five hours every weekday in class,”* where the domain for x consists of all students. Express each of these quantifications in English.
    - a) ∃xP(x)
        - Some students spend more than 5 hours every weekday in class
    - b) ∀xP(x)
        - All stydents spends more than 5 hours every weekday in class
    - c) ∃x ¬P(x)
        - Some students does not spend more that 5 hours every weekday in class
    - d) ∀x ¬P(x)
        - None of the students spends more than 5 hours every weekday in class

## Underopgave 11

- Let P(x) be the statement “$x = x^2$.” If the domain consists of the integers, what are these truth values?
    - a) P(0)
        - True
    - b) P(1)
        - True
    - c) P(2)
        - False
    - d) P(−1)
        - False*
    - e) ∃xP(x)
        - True
    - f ) ∀xP(x)
        - False

## Underopgave 16

- Determine the truth value of each of these statements if the domain of each variable consists of all real numbers.
    - a) ∃x(x^2 = 2)
        - False
    - b) ∃x(x^2 = −1)
        - True
    - c) ∀x(x^2 + 2 ≥ 1)
        - False
    - d) ∀x(x^2 ≠ x)
        - False

## Underopgave 17

- Suppose that the domain of the propositional functionP(x) consists of the integers 0, 1, 2, 3, and 4. Write out each of these propositions using disjunctions, conjunctions,and negations.
    - a) ∃xP(x)
        - P(0) ∨ P(1) ∨ P(2) ∨ P(3) ∨ P(4)
    - b) ∀xP(x)
        - P(0) ∧ P(1) ∧ P(2) ∧ P(3) ∧ P(4)
    - c) ∃x¬P(x)
        - ¬P(0) ∨ ¬P(1) ∨ ¬P(2) ∨ ¬P(3) ∨ ¬P(4)
    - d) ∀x¬P(x)
        - ¬P(0) ∧ ¬P(1) ∧ ¬P(2) ∧¬P(3) ∧ ¬P(4)
    - e) ¬∃xP(x)
        - ¬(P(0)∨P(1)∨P(2)∨P(3)∨ P(4))
    - f ) ¬∀xP(x)
        - ¬(P(0)∧P(1) ∧P(2) ∧ P(3) ∧ P(4))

## Underopgave 54

- As mentioned in the text, the notation ∃!xP(x) denotes“There exists a unique x such that P(x) is true.”If the domain consists of all integers, what are the truth values of these statements?
    - a) ∃!x(x > 1)
        - False
    - b) ∃!x(x^2 = 1)
        - False
    - c) ∃!x(x + 3 = 2x)
        - True
    - d) ∃!x(x = x + 1)
        - False

`Hvis der er tid:`

# Hovedpunkt 3

Afsnit 1.4: 

## Underopgave 62

- Let P(x), Q(x), and R(x) be the statements “x is a clear explanation,” “x is satisfactory,” and “x is an excuse,”respectively. Suppose that the domain for x consists of all English text. Express each of these statements using quantifiers, logical connectives, and P(x), Q(x), andR(x).
    - a) All clear explanations are satisfactory.
        - ∀x [P(x) → Q(x)]
    - b) Some excuses are unsatisfactory.
        - ∃x [R(x) ∧ ¬Q(x)]
    - c) Some excuses are not clear explanations.
        - ∃x [R(x) ∧ ¬Q(x)]
    - ∗d) Does (c) follow from (a) and (b)?
        - ?