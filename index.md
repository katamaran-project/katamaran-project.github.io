---
layout: default
title: Katamaran
---

## Research goals
An instruction set architecture (ISA) is an abstract specification of the syntax
and semantics of machine code. It defines an envelope of allowed behaviour for
CPU designers and a set of assumptions that software designers can rely on.

We are interested in critical safety guarantees of ISAs and more specifically
the security guarantees of features such as *trusted execution environments* ,
*virtual memory*, or *capability machines*. Our long-term goal is to verify with
machine checked proofs that security guarantees are upheld by the semantics of
all instructions. Moreover, we want to verify these properties in a form that
can be used to reason about programs, as a way to ultimately verify security
properties of full systems, i.e. hardware combined with software.

## Verification
Scaling up ISA property proofs raises important proof engineering challenges.
For the verification effort to scale reasonably in terms of the size and
complexity of the specification and for making it robust to changes, proof
automation is a necessity. To this end, we are developing
[Katamaran](https://github.com/katamaran-project/katamaran), a semi-automated
separation logic verifier for the Sail specification language.

## Case studies
- [Minimal Capability Machine](https://github.com/katamaran-project/katamaran/tree/main/case_study/MinimalCaps)
- [Physical Memory Protection](https://github.com/katamaran-project/katamaran/tree/main/case_study/RiscvPmp)

## People
### Current
- [Dominique Devriese](https://distrinet.cs.kuleuven.be/people/DominiqueDevriese)
- [Sander Huyghebaert](https://github.com/capt-hb)
- [Steven Keuchel](https://soft.vub.ac.be/~skeuchel)

### Past
- [Georgy Lukyanov](https://github.com/geo2a)