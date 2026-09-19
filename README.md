# Supplementary Material for Moore-Type QC LDPC Codes

This repository contains the supplementary material for the manuscript

**On the Minimum Distance of High-rate Moore-Type Quasi-Cyclic LDPC Codes**

by Hongwei Zhu, Shanghong Xie, Chunming Tang, He Zhang, and Minjia Shi.

The supplementary files provide the detailed combinatorial and algebraic
calculations supporting the classification of low-weight codewords of
Moore-type quasi-cyclic LDPC codes.

## Supplementary Material A

### Complete Proof of Proposition 29

Files:

- `Supplementary_Material_A_Proposition_29.tex`
- `Supplementary_Material_A_Proposition_29.pdf`

Supplementary Material A contains the complete proof of Proposition 29,
which classifies the possible matching configurations of Hamming-weight-8
codewords of `Moore(m,a,b,3)`.

The material includes:

- the normalization of a weight-8 support;
- the pairwise refinement of matching partitions;
- the complete enumeration of admissible matching configurations;
- the exclusion of branches forcing repeated support columns;
- the forced appearance of 4-matchings;
- the reduction by weight-preserving graph isomorphisms; and
- the resulting seven representative matching configurations,
  Cases I--VII.

This document replaces the detailed proof previously included as
Appendix A of the manuscript.

## Supplementary Material B

### Detailed Algebraic Derivations for Theorem 36, Cases II--VII

Files:

- `Supplementary_Material_B_Theorem_36.tex`
- `Supplementary_Material_B_Theorem_36.pdf`

Supplementary Material B contains the detailed algebraic derivations for
Cases II--VII in the Hamming-weight-8 existence criterion of Theorem 36.

For each matching configuration, the document gives the complete chain

```text
matching configuration
    -> weighted matching graph
    -> fundamental-cycle system
    -> linear congruence system
    -> reduced row echelon form
    -> subgroup-membership conditions
    -> distinctness conditions.
