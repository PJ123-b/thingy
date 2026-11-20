# Lin's conjecture

Research repository for a named open problem in theoretical PDEs: boundary unique continuation for harmonic functions in general Lipschitz domains.

**Research status (2026-11-20):** candidate selected; unresolved in the full formulation *according to the sources checked below*. This is **not** a proof and is not a guarantee that no unindexed or very recent resolution exists. Any claimed lemma or theorem must be independently checked.

## Problem

Let \(\Omega\subset\mathbb R^d\) be a Lipschitz domain and \(V\subset\partial\Omega\) a relatively open boundary patch. Suppose \(u\) is harmonic in \(\Omega\), extends continuously with \(u=0\) on \(V\), and its outward normal derivative vanishes on a positive-surface-measure subset of \(V\) (interpreted using appropriate a.e. boundary traces). **Conjecture:** \(u\equiv 0\).

This open *Dirichlet-patch* condition is essential. Do **not** confuse this with the gradient-only/Bers/Nadirashvili problem, for which counterexamples exist.

## What is known (not ours)

- Established for \(C^{1,1}\), \(C^{1,\alpha}\), \(C^{1,\mathrm{Dini}}\), \(C^1\), convex Lipschitz, small-Lipschitz-constant, and quasiconvex Lipschitz domains in the respective cited settings.
- In April 2026, Stefano Vita explicitly states that the general conjecture remains open, while proving a planar/chord-arc result.
- An August 2026 preprint by Qin–Zhan constructs smooth counterexamples to a **different gradient-only** boundary-unique-continuation statement. It explicitly says its theorem does not contradict results with an open Dirichlet patch.
- A paper appearing in *Advances in Mathematics* in October 2026 likewise describes the general Lipschitz-domain version as open.

## Repository organization

- [literature.md](literature.md) — dated source audit, scope distinctions, and checks.
- [notes/flattening.md](notes/flattening.md) — a rigorously derived, elementary change-of-variables lemma. **Not a new research theorem.**
- GitHub Issues — tasks, objections, handoffs, and coordination with other contributors.

## Research standards

1. Treat apparent proofs as unverified until every hypothesis, trace, and limiting argument has been checked.
2. Cite the original mathematical statements and recent research, retaining the date checked.
3. Distinguish established results, elementary derivations, speculative approaches, and genuine new results.
4. Prefer analytical lemmas to parameter sweeps, numerical experimentation, or arbitrary dimensional extensions.
5. If sustained effort stalls, document why and reassess the target instead of endlessly repeating a failed idea.
6. Use issues to invite independent verification and to coordinate with other agents or collaborators when present.

## Initial references

- Stefano Vita, *Boundary unique continuation in planar domains by conformal mapping*, *Bulletin of the London Mathematical Society* (17 April 2026), https://doi.org/10.1112/blms.70356
- Josep M. Gallegos, *Size of the zero set of solutions of elliptic PDEs near the boundary of Lipschitz domains with small Lipschitz constant*, *Calc. Var. PDE* (2023), https://doi.org/10.1007/s00526-022-02426-x
- Yingying Cai, *Unique continuation at the boundary for divergence form elliptic equations on quasiconvex domains*, https://arxiv.org/abs/2405.05044
- Guolin Qin and Weicheng Zhan, *Smooth Failure of Boundary Unique Continuation for Harmonic Functions*, preprint (3 August 2026), https://arxiv.org/abs/2608.01683
- *Nodal sets of Dirichlet eigenfunctions in quasiconvex Lipschitz domains*, *Advances in Mathematics* (October 2026), https://www.sciencedirect.com/science/article/pii/S0001870826003713

Last checked: 2026-11-20.