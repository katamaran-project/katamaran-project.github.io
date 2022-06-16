---
layout: icfp
title: Verified Symbolic Execution with Kripke Specification Monads (and no Meta-Programming)
---

[Original submission](./icfp2022-paper17.pdf)

# 2022-06-16 [[pdf]](./202206151246.pdf) [[diff]](./202206151246.diff.pdf)
- Rework notations. Do not use meta-variables to refer to values and types.
- Fix the coloring of object, shallow and symbolic code.

# 2022-06-15 [[pdf]](./202206151546.pdf) [[diff]](./202206151546.diff.pdf)
- Short discussion about partial and total correctness models in Section 6.
- Short discussion on (relative) completeness in Section 5.
- Polish the general methodology at the end of the intro.
- Address the remaining comments from the reviwers
- Minor edits to shorten the text.

# 2022-06-14 [[pdf]](./202206141048.pdf) [[diff]](./202206141048.diff.pdf)
- Split Section 2.3 into two parts. The new Section 2.3 now only discusses the execution of a function call and Section 2.4 discusses the generation of a verification condition for the body of a function.
- Move the summaxlen example from Section 2.0 to Section 2.3 where its contract is discussed.
- Add and explain the push and pop combinators for dealing with the store.
- Clarify that a constraint solving is not in scope of the paper and a solver is assumed to be given.
- In Section 6, clarify that Katamaran implements the techniques as discussed in the preceeding sections, including the logical relation, and that everything is mechanized.
- Fix (most) detailed comments from the reviewers.


# 2022-06-11 [[pdf]](./202206111112.pdf) [[diff]](./202206111112.diff.pdf)
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
