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

## Articles

- **Semi-automatic verification of ISA security guarantees in the form of universal contracts**<br>
  *Sander Huyghebaert, Steven Keuchel and Dominique Devriese*<br>
  <span style="color:silver">Short paper presented at the workshop on the Security of Software / Hardware Interfaces, SILM'21</span><br>
  [[pdf]](articles/2021-09-silm-universalcontracts.pdf) [[slides]](articles/2021-09-silm-universalcontracts-slides.pdf)

- **Katamaran: semi-automated verification of ISA specifications**<br>
  *Steven Keuchel, Georgy Lukyanov and Dominique Devriese*<br>
  <span style="color:silver">Extended abstract REMS-DeepSpec 2020 workshop.</span><br>
  [[pdf]](articles/2020-06-remsdeepspec-katamaran.pdf) [[slides]](articles/2020-06-remsdeepspec-katamaran-slides.pdf)

- **Verified Symbolic Execution with Kripke Specification Monads (and no Meta-Programming)**<br>
  *Steven Keuchel, Sander Huyghebaert, Georgy Lukyanov and Dominique Devriese*<br>
  <span style="color:silver">Manuscript, under submission</span><br>
  [[pdf]](articles/2022-06-symbolic-execution-vcgen.pdf)

## Software Releases

- [Katamaran v0.1](https://github.com/katamaran-project/katamaran/releases/tag/v0.1.0)

## Case studies
- [Minimal Capability Machine](https://github.com/katamaran-project/minimalcaps)
- [Physical Memory Protection](https://github.com/katamaran-project/katamaran/tree/main/case_study/RiscvPmp)

## People
### Current
- [Dominique Devriese](https://distrinet.cs.kuleuven.be/people/DominiqueDevriese)
- [Sander Huyghebaert](https://github.com/capt-hb)
- [Steven Keuchel](https://soft.vub.ac.be/~skeuchel)

### Past
- [Georgy Lukyanov](https://github.com/geo2a)


## Partners and Funding
- [CyberSecurity in Flanders](https://cybersecurity-research.be/)
- [Software Languages Lab](http://soft.vub.ac.be/soft/)
- [imec - DistriNet](https://distrinet.cs.kuleuven.be/)
