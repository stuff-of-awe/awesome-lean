<!-- SPDX-License-Identifier: CC-BY-SA-4.0 -->
# Awesome Lean

Start with Lean 4 to write a theorem, then find the lemmas that mathlib already supplies.

- [Theorem Proving in Lean 4](https://lean-lang.org/theorem_proving_in_lean4/) — Work through propositions and tactics in the same project so you can compare the proof terms.
- [Mathematics in Lean](https://leanprover-community.github.io/mathematics_in_lean/) — Practise with mathlib on mathematical examples.
- [mathlib documentation](https://leanprover-community.github.io/mathlib4_docs/) — Look up declarations and their import paths before adding a dependency.
- [Lean community](https://leanprover-community.github.io/) — Find Zulip and ask about a small reproducible goal.
- [Earlier community catalogue](https://github.com/paolobrasolin/awesome-lean) — Compare historical resources and check the Lean version before following them.
- [Lean programming catalogue](https://github.com/saviorand/awesome-lean-programming) — Explore libraries for programming in Lean 4.

## A first exercise

Open Mathematics in Lean and try a proof twice, once with an explicit lemma and once with a tactic. Inspect the goal after each step. Lean 3 scripts generally need porting to Lean 4.

## Curation

Stuff of Awe starter collection, assembled 3 November 2026. Original annotations link to the authors' resources. The two independent Lean catalogues above offer complementary coverage. The exercise is a reading or practice prompt and has not been execution-tested here. Open an issue or PR here for corrections, version caveats or additions. [Editorial guidance](https://github.com/stuff-of-awe/.github/blob/main/docs/collections/MAINTENANCE.adoc).

## Rechecking proofs and studying the kernel

- [Lean4Lean](https://github.com/digama0/lean4lean) — Reimplementation of the Lean 4 kernel in Lean with formal metatheory work. It follows the C++ kernel closely; do not mistake it for an entirely independent implementation or a completed proof of all kernel properties.
- [nanoda](https://github.com/ammkrn/nanoda_lib) — Alternative Lean 4 checker written in Rust. It can recheck exported declarations with a distinct implementation, but its availability does not establish that its implementation has been formally proved correct.
- [Lean Kernel Arena](https://arena.lean-lang.org/) — Compare checker behaviour on accepted, rejected, and corner-case declarations. Treat comparative testing separately from a proof of soundness.

For assurance, record the exact Lean version, exported declarations, checker version, allowed axioms and any rejected/unsupported cases. No independent checking was executed for this curation update. Related [proof-checking and verified-machine guide](https://github.com/stuff-of-awe/awesome-provable/pull/18) is in draft review.
