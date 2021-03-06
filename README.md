# Albatross Programming Language

**Version:** 0.4.x

**Author:** Helmut Brandl (helmut dot brandl at gmx dot net)

**Download:** http://sourceforge.net/projects/albatross-lang

**Website:** http://albatross-lang.sourceforge.net

# What is Albatross?

Albatross is a programming language which can be verified statically. You
write programs in Albatross and prove them to be correct in the same language.

What is a correct program? A program is correct if it is consistent with its
specification. Specifications in Albatross are assertions which express
correctness conditions. Assertions are boolean expressions in predicate logic.


A verified Albatross program has as proof for each assertion. The proof is
generated by the compiler.

But since assertions are expressed in predicate logic and predicate logic is
not decidable for arbitrary expressions the theorem prover in the Albatross
compiler cannot prove all valid assertions.

Therefore the programmer has to provide the proof steps which cannot be done
by the compiler automatically. The automation features have been designed with
the following philosophy:

- The compiler does all low level work that can be done efficiently
  without entering a huge search space.

- The programmer has to provide the more intelligent steps which require
  some creativity.


Because of this philosophy the Albatross compiler is something between a proof
assistant and a theorem prover.


> During 2018 a major update of the compiler is planned in order to be able to
  produce executable code from Albatross sources. Therefore no major update
  will appear within 2018.


<!---
Local Variables:
mode: outline
coding: iso-latin-1
outline-regexp: "#+"
End:
-->
