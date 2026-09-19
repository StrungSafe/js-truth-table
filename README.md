# Truth Table Generator

An easy web based tool that builds a truth table from a boolean expression. Variables are
detected automatically, and you can optionally compare two expressions to check whether
they're logically equivalent.

## Syntax

Expressions accept either plain words or logical symbols:

| Meaning       | Accepted forms                    |
|---------------|------------------------------------|
| Negation      | `NOT p`, `¬p`, `!p`                |
| Conjunction   | `p AND q`, `p ∧ q`, `p && q`       |
| Disjunction   | `p OR q`, `p ∨ q`, `p \|\| q`        |
| Exclusive or  | `p XOR q`, `p ⊕ q`                 |
| Implication   | `p IMPLIES q`, `p → q`, `p -> q`   |
| Biconditional | `p IFF q`, `p ↔ q`, `p <-> q`      |
| Constants     | `TRUE`, `FALSE`                    |

Use parentheses to group. Variable names can be any letters/digits (e.g. `p`, `q`, `isValid`).

## How To Use

There are two ways to view the page

### Hosted (Easy)

1. Open [preview](https://htmlpreview.github.io/?https://github.com/StrungSafe/js-truth-table/blob/main/index.html)

### Locally

1. Download or clone the repo
2. Open index.html in browser

### Contributing

Feel free to open a PR to fix any bugs or enhance the page