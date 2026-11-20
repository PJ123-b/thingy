# Elementary flattening lemma (foundational, not original)

**Date:** 2026-11-20  
**Purpose:** explain why the Dirichlet-patch boundary unique-continuation problem does not become an easy interior unique-continuation theorem on flattening a merely Lipschitz boundary.

## Setting

Locally, let \(\Omega=\{(x',x_d):x_d>\varphi(x')\}\) for a Lipschitz function \(\varphi:\mathbb R^{d-1}\to\mathbb R\) with Lipschitz constant \(L\). Set

\[
F(y',t)=(y',t+\varphi(y')),\qquad v(y',t)=u(F(y',t)).
\]

Here \(F\) maps the upper half-space onto the graph domain, is bi-Lipschitz, and \(\det DF=1\) a.e.

## Lemma: change of variables

If \(u\in H^1_{\mathrm{loc}}(\Omega)\) is weakly harmonic, then \(v\in H^1_{\mathrm{loc}}(\mathbb R^d_+)\) satisfies

\[
\operatorname{div}_y(A(y')\nabla_y v)=0,\quad
A=(DF)^{-1}(DF)^{-T}
=
\begin{pmatrix}
I_{d-1}&-\nabla\varphi\\
-(\nabla\varphi)^T&1+|\nabla\varphi|^2
\end{pmatrix}\qquad\text{a.e.}
\]

**Proof.** Rademacher's theorem implies \(F\) is differentiable a.e. with

\[
DF=\begin{pmatrix}I&0\\(\nabla\varphi)^T&1\end{pmatrix},\qquad
(DF)^{-1}=\begin{pmatrix}I&0\\-(\nabla\varphi)^T&1\end{pmatrix}.
\]

The a.e. Sobolev chain rule gives \(\nabla_y v=(DF)^T\nabla_xu\circ F\).
For a compactly supported test \(\eta\) in the upper half-space, take \(\psi=\eta\circ F^{-1}\) in the weak harmonic equation. Then, using the area formula and \(\det DF=1\),

\[
0=\int_\Omega\nabla_xu\cdot\nabla_x\psi\,dx
=\int_{\mathbb R^d_+}A\nabla_yv\cdot\nabla_y\eta\,dy.
\]
QED.

**Uniform ellipticity.** For any \(\xi\in\mathbb R^d\),

\[
\xi^TA\xi=|\xi'-\xi_d\nabla\varphi|^2+\xi_d^2.
\]

Because \(\|DF\|\) and \(\|(DF)^{-1}\|\) are both bounded by \(1+L\) (a safe, though nonsharp, operator-norm bound), the quadratic form obeys

\[
(1+L)^{-2}|\xi|^2\leq\xi^TA\xi\leq(1+L)^2|\xi|^2.
\]

## Boundary flux identity

At a boundary point with \(\varphi\) differentiable and where suitable gradient traces exist, the physical outward unit normal is

\[
\nu_x=\frac{(\nabla\varphi,-1)}{\sqrt{1+|\nabla\varphi|^2}}.
\]

Writing \(\nu_y=-e_d\), one computes

\[
\nu_y\cdot A\nabla_yv
=\nabla\varphi\cdot\nabla'v-(1+|\nabla\varphi|^2)\partial_tv
=\sqrt{1+|\nabla\varphi|^2}\,\partial_{\nu_x}u\circ F.
\]

Thus the physical normal derivative condition corresponds to a conormal flux condition, not generally to \(\partial_tv=0\). The boundary surface measure changes by \(d\sigma_x=\sqrt{1+|\nabla\varphi|^2}\,dy'\), so positive surface measure is preserved.

**Trace caveat.** For generic weak solutions, \(\nabla u\) need not have a pointwise boundary trace. The displayed flux identity is a pointwise identity only under extra trace hypotheses; otherwise it should be understood in the appropriate weak conormal-trace/measure-theoretic framework. This distinction is part of the technical work, not something to assume away.

## Obstruction

A Lipschitz graph has \(\nabla\varphi\in L^\infty\) a.e., but this derivative need not be continuous, Lipschitz, or differentiable. Consequently \(A\in L^\infty\) is uniformly elliptic, yet generally not Lipschitz. Classical strong unique-continuation estimates requiring differentiable coefficients therefore cannot simply be invoked on the flattened equation. Odd reflection of a zero-Dirichlet solution also creates a coefficient interface that requires justification.

This explains a **failure of a naïve proof strategy**, not an impossibility theorem. Finding additional structure in graph-induced \(A\) beyond generic bounded measurable elliptic coefficients is a potential direction.

## Next checks

1. Verify the precise boundary trace interpretation in the main Lin-conjecture papers.
2. Analyze whether the special form \(A=DF^{-1}DF^{-T}\), \(\det DF=1\), improves unique continuation near the boundary.
3. Check how and why known methods work in small-slope and quasiconvex cases.
4. Do not claim novelty for this flattening calculation; it is a standard PDE transformation.
