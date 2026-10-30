# Supplementary Material

**Manuscript:** *On the Minimum Distance of High-rate Moore-Type Quasi-Cyclic LDPC Codes*

This directory contains two analytical supplementary documents accompanying the manuscript.

## Files

1. **`Supplementary_Materia_Proposition_29.pdf`**  
   Complete enumeration proof of Proposition 29. It classifies the weight-8 matching configurations into the seven representatives stated in the main manuscript.

2. **`Supplementary_Material_Theorem_36.pdf`**  
   Detailed fundamental-cycle calculations, reduced row-echelon forms, and distinctness checks for Cases II–VII in Theorem 36. Case I is proved in the main manuscript.

## Scope and notation

Throughout, `m` is an odd prime and `a,b` are units modulo `m`. Their multiplicative orders are `k = ord_m(a)` and `j = ord_m(b)`.

For Supplement A, the parameter range is `3 <= j < k`. The columns of `Moore(m,a,b,3)` are represented by

`c(x,t) = [x, x+(b-1)a^t, x+(b^2-1)a^t]^T`, with `x` in `Z_m` and `t` in `Z_k`.

The actual matching partition at level `s` is denoted by `M_s`, as in Definition 11 of the main manuscript. In Supplement A, `M_0^f` is used only for the initial pairwise refinement of the level-0 matching; it is not the actual matching partition `M_0`. Subsequent merged matching configurations retain the main manuscript's notation `M=(M_0,M_1,M_2)`.

Supplement B specializes to `j=3` and `k>3`. Since `m` is prime, the calculations identify `Z_m` with `F_m`. The normalization is `c_1=c(0,0)`, and `u_i=a^(t_i)` with `t_i` in `Z_k` and `u_1=1`.

The weighted-cycle notation follows Remark 16 of the main manuscript: a cycle is written as `i_1,i_2,...,i_ell,i_1(s_1,...,s_ell)`, where `s_r` is the level of the edge joining `c_{i_r}` and `c_{i_(r+1)}`, with `i_(ell+1)=i_1`. Supplement B underlines the vertex indices in this display to identify the ordered cycle vertices.

## Relation to the main manuscript

- Supplement A expands the proof omitted for Proposition 29 and uses Lemmas 13, 14, 19, and 20, Corollary 23, and Algorithm 1.
- Supplement B provides the detailed algebraic derivations for the six alternatives corresponding to Cases II–VII of Theorem 36. Its case-to-matching-subcase correspondence is given in the table on the first page of the document.
- For Case VI (matching subcase 2-3-5), the column order is the representative used in Proposition 29; relative to the intermediate enumeration label, this uses the relabeling `c_7 <-> c_8`.

The supplements are intended to be read together with the main manuscript. Proposition, theorem, lemma, corollary, algorithm, and equation references refer to that manuscript.

## Reproducibility note

These two PDFs contain analytical proofs and derivations. They do not, by themselves, constitute a software package or a record of the computational runs used for numerical examples. Any separately distributed computational archive should identify its actual scripts, software environment, inputs, and outputs; no unprovided Magma source code is claimed to be included here.

The supplied materials were PDFs rather than original LaTeX sources. Accordingly, this package provides the supplementary PDFs and this README; it does not claim to provide reconstructed editable source files.
