# Core Path Algebra for Graph Queries

This repository contains my seminar paper on path-based algebraic foundations for graph query languages, written as part of the *Graph Database Management* seminar at the University of Stuttgart.

## Abstract

Graph databases are an important technology for representing highly connected data. Modern graph query languages such as **GQL** and **SQL/PGQ** rely heavily on path queries for navigation and pattern matching.

This paper reviews the **path algebra proposed by Angles et al.** and discusses its role as a formal foundation for graph query languages. The algebra introduces operators for path selection, concatenation, union, and recursion, allowing paths to be treated as first-class query objects.

The paper further examines how these operators support the path-querying capabilities of GQL and SQL/PGQ and compares the proposed algebra with alternative formal foundations, including **relational algebra, automata-based approaches, and semiring-based models**.

## Contents

The paper covers:

* foundations of graph databases and graph query languages
* the core path algebra proposed by Angles et al.
* recursive path algebra
* the relationship between path algebra and GQL / SQL/PGQ
* related theoretical foundations
* comparison with relational algebra, automata-based approaches, and semiring-based models
* discussion of the role of path algebra as a formal foundation for graph query languages

## Repository Structure

```text
.
├── main.tex
├── references.bib
├── seminar-paper.pdf
└── sections/
    ├── 01_introduction.tex
    ├── 02_background.tex
    ├── 03_core_path_algebra.tex
    ├── 04_recursive_path_algebra.tex
    ├── 05_mapping_to_gql.tex
    ├── 06_related_work_foundations.tex
    ├── 07_discussion.tex
    └── 08_conclusion.tex
```

## Paper

The final version of the seminar paper is available as [`seminar-paper.pdf`](seminar-paper.pdf).

The LaTeX source is included alongside the paper.
