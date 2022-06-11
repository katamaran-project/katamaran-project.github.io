---
layout: icfp
title: Verified Symbolic Execution with Kripke Specification Monads (and no Meta-Programming)
---

[Original submission](./icfp2022-paper17.pdf)

# 2022-06-11 11:12 [[pdf]](./202206111112.pdf) [[diff]](./202206111112.diff.pdf)
- Polished the discussion of a hypothetical direct proof between the symbolic
  executor and the program logic at the end of Section 5.

## Soudness related
- Added corollary 2.2 to express soundness of shallow VCG w.r.t. Hoare triples.
- Added Lemma 5.1 to express soundness of symbolic execution without the logical
  relation.
- Included the definition of the symbolic VCG at the end of Section 3.4 as
  another example of definitions with the *same structure*.
- Added Section 6.1 with a brief discussion about the Iris model instantiation,
  and a new Lemma 6.1 that states end-to-end result between pure contracts and
  the operational semantics.

## Debug information
- Added forward references in 3.5 to the examples discussed.
- Added an example discussing the omission of a ghost lemma statement to Section
  4.1.


