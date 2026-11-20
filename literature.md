# Literature audit — Lin's conjecture

**Audit date:** 2026-11-20. **Status:** unresolved in the full general-Lipschitz-domain formulation in the sources reviewed, but the search is not an exhaustive mathematical proof of openness.

## Target, precisely

A standard formulation asks whether a harmonic function \(u\), vanishing continuously on a relatively open portion \(V\) of the boundary of a Lipschitz domain \(\Omega\subset\mathbb R^d\), must vanish identically if its outward normal derivative vanishes on a subset of \(V\) of positive surface measure. The exact meaning of normal derivative and the regularity assumptions must be imported from a chosen reference before attempting a theorem.

**Non-negotiable hypothesis:** the Dirichlet condition is on an **open boundary patch**, while the Neumann condition is only on a **positive-measure subset** of that patch.

## Checked references, with relevance and limits

1. **Stefano Vita**, *Boundary unique continuation in planar domains by conformal mapping*, *Bulletin of the London Mathematical Society* 58 (2026), article e70356, https://doi.org/10.1112/blms.70356 ; preprint https://arxiv.org/abs/2405.04388 . Published 17 April 2026. Its abstract says the boundary uniqueness assertion in planar chord-arc domains is conjectured by Lin in higher-dimensional Lipschitz domains. **Positive result in dimension two, not a resolution in all dimensions.**
2. **Guolin Qin and Weicheng Zhan**, *Smooth Failure of Boundary Unique Continuation for Harmonic Functions*, https://arxiv.org/abs/2608.01683 (3 August 2026). Constructs a nonconstant harmonic function in a half-space with all boundary derivatives zero on a compact nowhere-dense positive-measure set. **Not a disproof of Lin's open-patch Dirichlet formulation**: the zero set is nowhere dense, not a relatively open patch.
3. **Yingying Cai**, *Unique continuation at the boundary for divergence form elliptic equations on quasiconvex domains*, https://arxiv.org/abs/2405.05044 . Establishes boundary unique continuation on quasiconvex Lipschitz domains under stated coefficient assumptions, covering a substantial subclass.
4. **Josep M. Gallegos**, *Size of the zero set of solutions of elliptic PDEs near the boundary of Lipschitz domains with small Lipschitz constant*, *Calculus of Variations and Partial Differential Equations* (2023), https://doi.org/10.1007/s00526-022-02426-x . Related geometric restrictions and quantitative nodal-set results.
5. **Boundary unique continuation for harmonic functions in C¹ domains and Lipschitz domains with small constant**, literature on small Lipschitz-constant and \(C^1\) boundary cases. Check exact author, publication version and hypotheses before citing a specific theorem.
6. **Nodal sets of Dirichlet eigenfunctions in quasiconvex Lipschitz domains**, *Advances in Mathematics* (2026), https://www.sciencedirect.com/science/article/pii/S0001870826003713 . Related 2026 work: verify theorem and version before extrapolating any claim.

## Important negative result vs the conjecture

Qin–Zhan's smooth half-space example disproves a related statement where **both** Dirichlet and Neumann data vanish only on a positive-measure, nowhere-dense boundary set. It does not supply a counterexample with \(u=0\) on a relatively open boundary patch. Do not drop the open-patch requirement inadvertently when making a reduction.

## Honest scope of audit

Checked searches for: 'Lin conjecture boundary unique continuation 2026'; 'Lin Lipschitz proved solved 2026'; 'Smooth Failure Boundary Unique Continuation 2026'; Vita 2026; Cai and Gallegos. This is a preliminary targeted search, **not** an exhaustive survey of all literature or a proof that the conjecture remains open as of today. Future search: MathSciNet / zbMATH, references citing Vita and Cai, revised arXiv versions, scholar citations to 2026 papers, and author home pages.

## Problem suitability

Lin's full conjecture may be substantially too ambitious for a beginning postdoc; the problem has resisted extensive prior work. Aim initially for an independently useful **structural lemma or reduction** rather than promising to resolve it. If no credible tractable advance emerges, re-evaluate against the user's preference for modest, named unresolved conjectures.

## Working bibliography policy

Distinguish direct verification from secondary reporting, track versions and dates, and copy no substantial copyrighted prose into this repository.
