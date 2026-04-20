# CSS Specificity Decoded: Mastering the Rules

One of the most misunderstood concepts in CSS — demystified with a clear scoring system, real examples, and practical best practices.

## What It Covers

- How browsers resolve style conflicts using a four-tier specificity scoring system
- The weight of inline styles, IDs, classes, and element selectors — with scores explained
- Three progressively complex examples showing specificity in action
- A quick-reference specificity table for everyday use
- Best practices for writing maintainable, predictable CSS

## Why It Matters

Unexplained style overrides are a silent productivity killer. Developers who understand specificity don't just fix bugs faster — they write CSS that doesn't create bugs in the first place. This tutorial reflects a foundational understanding of how the browser's rendering engine actually works, not just how to make things look right by trial and error.

## Specificity Scores at a Glance

| Selector Type | Example | Score |
|---|---|---|
| Inline Style | `style="color: red;"` | 1,0,0,0 |
| ID | `#header` | 0,1,0,0 |
| Class / Pseudo-class | `.button` / `:hover` | 0,0,1,0 |
| Element / Pseudo-element | `p` / `::before` | 0,0,0,1 |

## Tech Stack

- HTML5 & CSS3
- No frameworks — pure, portable browser fundamentals

---

📖 [Read the full tutorial](https://www.onyekaanene.com/css-specificity-decoded-mastering-the-rules/)

[![GitHub](https://img.shields.io/badge/GitHub-onyekaanene-181717?style=flat&logo=github)](https://github.com/onyekaanene)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/onyekachukwu-anene)