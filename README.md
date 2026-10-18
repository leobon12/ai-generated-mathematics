# AI Generated Mathematics

Research notes developed with ChatGPT, curated by Leonardo Bonanno. These are unrefereed manuscripts. Inclusion here records the selected manuscripts and their stated results; it is not an independent certification of their proofs.

[Research website](https://leobon12.github.io/research.html#ai-generated-research)

The current collection contains 10 PDFs in 10 entries across 6 topic sections. Expand a result below to read its statement. PDF links open GitHub’s document preview.

## Directed Distances in Random Planar Maps

### Shortest Directed Paths: Scale and Continuum Limits

<details>
<summary>Result</summary>

<p class="research-description">Let M<sub>0,n</sub> be the unconditioned KMSW cell encoded by n independent steps, each uniform on {(1, −1), (−1, 0), (0, 1)}. The cell consists of its n + 1 active edges with their endpoint identifications; missing boundary edges are excluded. Let Δ<sub>n</sub> be the maximum, over ordered vertex pairs joined by a directed path inside the cell, of the minimum number of edges in such a path.</p>
<p class="research-description">There are deterministic constants c, C &gt; 0 such that, for every integer n ≥ 0 and every real A ≥ 1, ℙ[Δ<sub>n</sub> &gt; A(n + 1)<sup>3/8</sup>] ≤ C e<sup>−cA</sup>.</p>
<p class="research-description">For every n ≥ 1 and every median m<sub>n</sub> of Δ<sub>n</sub>—meaning ℙ[Δ<sub>n</sub> ≤ m<sub>n</sub>] ≥ 1/2 and ℙ[Δ<sub>n</sub> ≥ m<sub>n</sub>] ≥ 1/2—one has c n<sup>3/8</sup> ≤ m<sub>n</sub> ≤ C n<sup>3/8</sup>, with constants independent of n and of the choice of median.</p><p class="research-description">Let M be the uniform infinite bipolar-oriented triangulation. Write p(e) = (i(e), j(e)) for the times of an edge e in the north- and west-going primal Peano explorations, rooted at the same edge and oriented so both times increase along directed paths. For edges e ≼ f, meaning that a directed path can start with e and end with f, let d<sup>•</sup><sub>M</sub>(e, f) be the minimum number of edges in such a path, with d<sup>•</sup><sub>M</sub>(e, e) = 1. Comparability is equivalent to p(e) ≤ p(f) coordinatewise.</p>
<p class="research-description">For each n ≥ 1, choose any median m<sub>n</sub> of the maximal finite vertex-to-vertex SDP distance in an unconditioned n-increment KMSW cell with uniform increments from {(1, −1), (−1, 0), (0, 1)}. Put U<sub>n</sub> = {p(e)/n : e ∈ E(M)}, W<sub>n</sub> = {(x, y) ∈ U<sub>n</sub> × U<sub>n</sub> : x ≤ y coordinatewise}, and D<sub>n</sub>(p(e)/n, p(f)/n) = d<sup>•</sup><sub>M</sub>(e, f)/m<sub>n</sub>. Let Γ<sub>n</sub> = {(w, D<sub>n</sub>(w)) : w ∈ W<sub>n</sub>}.</p>
<p class="research-description">The laws of (W<sub>n</sub>, Γ<sub>n</sub>) are tight in 𝔽(ℝ<sup>4</sup>) × 𝔽(ℝ<sup>5</sup>), where 𝔽 denotes closed subsets with the Fell topology. Every sequence n → ∞ therefore has a subsequence converging in law. Every such limit is almost surely (W, {(w, D(w)) : w ∈ W}) for a locally bounded continuous function D : W → [0, ∞): above every point of W there is exactly one finite limiting height. The function is uniquely determined by its limiting graph; uniqueness of the subsequential law is not asserted.</p><p>Every such subsequential limiting function is almost surely not identically zero: with probability one, there are distinct comparable x and y with D(x,y) &gt; 0. Section 8 proves this using the preceding results for every deterministic choice of medians. No extra joint convergence with quantum-surface data is required. Uniqueness of the subsequential law and all-pairs point separation are not asserted.</p>

<p><em>Shortest Directed Paths in Bipolar-Oriented Triangulations: Theorems 1.1–1.2, p. 2; Theorem 8.1 and its proof, pp. 19–21.</em></p>

</details>

- [Shortest Directed Paths: Scale and Continuum Limits](papers/sdp-scale-and-continuum-limits.pdf) (22 pages)

**Lean:** coming soon

## Small-Parameter Liouville Quantum Gravity

### A Small-Parameter Limit for LFPP in All Dimensions

<details>
<summary>Result</summary>

<p>For each fixed integer d ≥ 2, let λ<sub>d</sub>(ζ) be the distance exponent of Liouville first passage percolation on ℝ<sup>d</sup>, with logarithmic covariance normalized to have coefficient one. The manuscript establishes</p>
<p>lim<sub>ζ↓0</sub> λ<sub>d</sub>(ζ)/ζ<sup>4/3</sup> = κ<sub>d</sub>, with 0 &lt; κ<sub>d</sub> &lt; ∞.</p>
<p>The coefficient is the subadditive rate of a Gaussian variational problem. Let V<sub>n,d</sub> consist of continuous functions f: [0,1] → ℝ<sup>d−1</sup> that vanish at the endpoints and are affine on dyadic intervals of length 2<sup>−n</sup>. For the centered Gaussian process G<sub>d</sub> with covariance Cov(G<sub>d</sub>(f), G<sub>d</sub>(g)) = π∫<sub>0</sub><sup>1</sup>(|f| + |g| − |f − g|) dx, define A<sub>n,d</sub> = 𝔼 sup<sub>f∈V<sub>n,d</sub></sub>{G<sub>d</sub>(f) − ½∫<sub>0</sub><sup>1</sup>|f′|² dx}. Then κ<sub>d</sub> = inf<sub>n≥1</sub> A<sub>n,d</sub>/(n log 2) = lim<sub>n→∞</sub> A<sub>n,d</sub>/(n log 2).</p>
<p>The constants satisfy (d − 1)<sup>2/3</sup>κ<sub>2</sub> ≤ κ<sub>d</sub> ≤ (d − 1)κ<sub>2</sub>. The dimension is fixed; no error estimate uniform as d → ∞ is asserted.</p>

<p><em>higher-dimensional-lfpp-limit.pdf: model and normalization (1.1)–(1.3), variational definitions (1.4)–(1.6), and Theorem 1.1, p. 2; comparison between dimensions (1.8), p. 3.</em></p>

</details>

- [A Small-Parameter Limit for LFPP in All Dimensions](papers/higher-dimensional-lfpp-limit.pdf) (26 pages)

**Lean:** [Lean](https://github.com/leobon12/lean-formalizations/tree/main/results/small-gamma-dimension). Existing planar small-gamma formalization: Theorem 1.1 and Proposition 1.2 of the earlier planar manuscript, with explicit LFPP-exponent existence and dimension-relation inputs. See the linked guide for its scope.


### Gaussian Fluctuations of LQG Distance

<details>
<summary>Result</summary>

<p><strong>Proposed theorem.</strong> Let h be a whole-plane Gaussian free field with unit-circle average h<sub>1</sub>(0) = 0. For each 0 &lt; γ &lt; 2, let D<sub>h</sub><sup>γ</sup> be the γ-LQG metric, using the same field for all γ. Fix its deterministic scale by requiring the lower median of C<sub>γ</sub> = inf<sub>s,t∈[0,1]</sub> D<sub>h</sub><sup>γ</sup>(is, 1 + it) to equal one. These are global distances: the connecting paths are not required to stay inside the unit square.</p>
<p>Define H<sub>y</sub> = ∫<sub>0</sub><sup>1</sup> h(x + iy) dx by L² limits of smooth mollifications, and let q be the lower median of min<sub>y∈[0,1]</sub> H<sub>y</sub>. The proposed result states that q &lt; 0 and (D<sub>h</sub><sup>γ</sup>(0, 1) − 1)/γ → (H<sub>0</sub> − q)/2 in probability as γ ↓ 0 on the common field probability space.</p>
<p>Consequently the limiting distribution is Gaussian with mean −q/2 and variance 3/8. The point-distance median m<sub>γ</sub> = med D<sub>h</sub><sup>γ</sup>(0, 1) also satisfies m<sub>γ</sub> = 1 − (q/2)γ + o(γ). Thus the first-order normalization correction comes from minimizing horizontal line integrals across the square.</p>

<p><em>gaussian-lqg-distance.pdf: field and metric normalization, §1, p. 1; global crossing (1.4), line-integral definitions (1.5)–(1.6), and Theorem 1.1, equations (1.7)–(1.9), p. 2.</em></p>

</details>

- [Gaussian Fluctuations of LQG Distance](papers/gaussian-lqg-distance.pdf) (17 pages)

**Lean:** coming soon

### Small-Parameter LQG Geodesics

<details>
<summary>Result</summary>

<p>For the whole-plane γ-LQG geodesic P<sub>γ</sub> from 0 to 1, parametrized at constant metric speed, its maximal Euclidean distance M<sub>γ</sub> from [0,1] satisfies 𝔼M<sub>γ</sub> ≤ Cγ<sup>2/3</sup> and ℙ[M<sub>γ</sub> ≤ aγ<sup>2/3</sup>] ≤ Ca<sup>3/5</sup> for small γ and 0 &lt; a ≤ 1. For each A ≥ 1, limsup<sub>γ↓0</sub> ℙ[M<sub>γ</sub> &gt; Aγ<sup>2/3</sup>] ≤ C(A<sup>−3</sup> + A<sup>−4</sup>).</p><p>The paths γ<sup>−2/3</sup>(P<sub>γ</sub>(t) − t) are tight in C([0,1], ℝ²), and their horizontal component vanishes uniformly in probability. The maximum is tight and bounded away from zero at this scale, with bounded inverse moments of orders below 3/5. No unique limiting law is asserted.</p>

<p><em>Theorem 1.1 (deviation), pp. 1–2; Theorem 1.2 (functional tightness), p. 2; shared band-event Lemma 5.1, p. 11; functional proof, §6, pp. 12–13; lower-tail Proposition 7.1, pp. 14–15; scalar consequences, §8, p. 15.</em></p>

</details>

- [Small-Parameter LQG Geodesics](papers/small-parameter-lqg-geodesics.pdf) (16 pages)

**Lean:** coming soon

## Supercritical Liouville Quantum Gravity

### Conformal Covariance of Supercritical LQG

<details>
<summary>Result</summary>

<p>Fix ξ &gt; ξ<sub>crit</sub> with Q = Q(ξ) ∈ (0, 2), and use one fixed normalization of the canonical supercritical Liouville quantum gravity metric. Let U, V ⊂ ℂ be domains, let φ: U → V be a fixed deterministic conformal bijection, and let h be a Gaussian free field plus a continuous function on V, in the local sense required to define the metric. Here D<sub>h</sub>(x, y; V) is the internal distance, obtained by minimizing metric length over paths contained in V; it may equal +∞.</p>
<p>Almost surely, simultaneously for every u, v ∈ U, D<sub>h</sub>(φ(u), φ(v); V) = D<sub>h∘φ+Q log|φ′|</sub>(u, v; U). The multiplicative constant is exactly one, and the equality includes singular endpoints and infinite distances. The probability-one event may depend on φ; the statement is for each fixed map.</p>

<p><em>supercritical-conformal-covariance.pdf: statement and conventions, Theorem 1.1 and equation (1), p. 1; removal of comparison constant, §6, pp. 9–10.</em></p>

</details>

- [Conformal Covariance of Supercritical LQG](papers/supercritical-conformal-covariance.pdf) (11 pages)

**Lean:** coming soon

## Random Geometry in Dimension at Least Three



### Odd-Dimensional Fields and Quantum Cones

<details>
<summary>Result</summary>

<p>For the whole-space log-correlated Gaussian field in odd dimension d = 2m + 1 ≥ 3, the centered spherical average Sₜ = hₑ⁻ᵗ(0) − h₁(0) is identified as a Brownian moving average with kernel q_d(u) = (d − 2)e⁻²ᵘ(1 − e⁻²ᵘ)^((d−4)/2). It has a modification in C_loc^(m−1,α) for every 0 &lt; α &lt; 1, highest-derivative increment variance comparable to r² log(1/|r|), and no mth mean-square derivative. An explicit continuous function-valued Brownian memory state gives a Markov lift for every integer d &gt; 2. In odd dimension, the non-rational spectrum excludes a finite-dimensional linear time-invariant Gaussian state-space representation of the radial derivative.</p>
<p>For γ ∈ (0, √(2d)), Q = d/γ + γ/2 and β &lt; Q, recenter the radial process at its first global hitting time of level −b after subtracting drift (Q − β)t. As b → ∞, the recentered process converges in total variation on every fixed half-line. Combining the limiting radial process S∞,s + βs with an independent spherical projection constructs the β-quantum cone. At any deterministic center, the corresponding rescaling of the field with a β-logarithmic singularity converges in total variation to the cone on every fixed ball, in the space of distributions.</p>

<p><em>Consolidated manuscript: Theorems A–C, pp. 4–5; Theorem 7.1 (sharp regularity), pp. 25–26; Proposition 7.2 (finite linear-state obstruction), p. 26; Theorem 7.3 (memory-state Markov lift), pp. 26–27; Corollary 7.4 (long-time variance), pp. 27–28. Theorem A and the memory-state formulas also hold for every integer d &gt; 2; the cone construction is for odd d.</em></p>

</details>

- [Odd-Dimensional Fields and Quantum Cones](papers/odd-dimensional-fields-and-quantum-cones.pdf) (30 pages)

**Lean:** coming soon

### GMC Tilings: Quenched Convergence

<details>
<summary>Result</summary>

<p>For every integer d ≥ 3, take 0 &lt; γ &lt; √(2d) − √(2d−1), Q = d/γ + γ/2, and α = Q − √(Q²−4). Let h be the α-quantum cone in its unit-sphere first-passage embedding. Sample a conditional Poisson process with intensity ε<sup>−1</sup>μ<sub>h,γ</sub> and form its Euclidean Voronoi cells.</p><p>The walk starts in the cell containing 0 and chooses a neighboring nucleus with probability proportional to the shared facet area divided by the distance between nuclei. At unit intensity let π(o) be total incident conductance. Then Z = 𝔼[π(o)/μ<sub>h,α</sub>(P<sub>o</sub>)] is strictly positive and finite.</p><p>With deterministic step duration 2ε<sup>α/γ</sup>/Z, the linearly interpolated conditional path laws given the field and tiling converge in probability to α-Liouville Brownian motion from 0, with underlying Brownian generator ½Δ. The topology is local uniform convergence. The field-only conditional laws have the same convergence in probability, and step paths converge in local Skorokhod J₁.</p><p>The argument is shared across all dimensions, including d = 3. The parameter restriction and in-probability quantifier are part of the theorem.</p>

<p><em>Quenched Convergence of GMC-Sampled Tilings in Every Dimension d ≥ 3: Theorem 1.1, p. 2.</em></p>

</details>

- [GMC Tilings: Quenched Convergence](papers/gmc-sampled-tilings-quenched-convergence.pdf) (36 pages)

**Lean:** coming soon

## Sphere Packings and Orthogonal Tilings

### Mesh-Only Convergence for Orthogonal Tilings

<details>
<summary>Result</summary>

<p>For locally finite orthogonal tilings of an open D ⊂ ℝ<sup>d</sup>, d ≥ 2, give an edge (v,w) the conductance vol<sub>d−1</sub>(P<sub>v</sub> ∩ P<sub>w</sub>)/|v−w|. Assume only that the maximum tile diameter ε<sub>n</sub> tends to zero. Fix bounded open U and K with U̅ ⊂ K and K̅ ⊂ D, and let h be harmonic and C² on a neighborhood of K̅. Its discrete harmonic extension h<sub>n</sub>, using h at adjacent boundary vertices, is uniquely defined for sufficiently large n and satisfies max<sub>v∈V<sub>n</sub>∩U</sub>|h<sub>n</sub>(v) − h(v)| ≤ C<sub>d,U,K</sub>‖h‖<sub>C²(K)</sub> ε<sub>n</sub><sup>4/(d+4)</sup>. In dimension two the exponent is 2/3.</p><p>The proof uses the expected exit time of small-volume superlevel sets. Under the remaining Bou-Rabee–Gwynne domain hypotheses, it also gives convergence of harmonic measures and stopped canonical walks to Brownian motion modulo time parametrization. The harmonic-error estimate is not a rate for a parametrized random walk.</p>

<p><em>Theorem 1.1 and improved equation (10), p. 3; Corollary 1.2, p. 4; expected-exit Lemma 6.1, p. 13; uniform estimate (80)–(81), p. 15; random-walk deduction and scope, §7, pp. 15–16.</em></p>

</details>

- [Mesh-Only Convergence for Orthogonal Tilings](papers/mesh-only-tilings-and-rates.pdf) (16 pages)

**Lean:** [Lean](https://github.com/leobon12/lean-formalizations/tree/main/results/mesh-only). Qualitative Dirichlet convergence. The sharper error rate and random-walk corollary are not covered by this Lean result.

### Sphere Packings and Tangency Tilings

<details>
<summary>Result</summary>

<p>Let d ∈ {2, 3, 4}, let Ω ⊂ ℝ<sup>d</sup> be any nonempty open set, and fix ε &gt; 0. There is a countably infinite family of closed balls B(v,r<sub>v</sub>) ⊂ Ω with pairwise disjoint interiors and 0 &lt; r<sub>v</sub> ≤ ε. For each ball, intersect the halfspaces bounded by its common tangent hyperplanes with all tangent balls, choosing the halfspace containing B(v,r<sub>v</sub>). The resulting tangency polytope P<sub>v</sub> is bounded, and the polytopes form a locally finite, face-to-face tiling of exactly Ω.</p>
<p>Two balls are tangent if and only if their polytopes share a facet, and that facet lies in their common tangent hyperplane. Consequently, joining the ball centers across shared facets gives an orthogonal tiling graph. In dimensions 2, 3, and 4 respectively, each tile has at most 6, 12, and 24 facets, and B(v,r<sub>v</sub>) ⊂ P<sub>v</sub> ⊂ B(v,C<sub>d</sub>r<sub>v</sub>), where C<sub>2</sub> = 2, C<sub>3</sub> = √10, and C<sub>4</sub> = 3√2 + 2.</p>
<p>No boundedness, connectedness, or boundary-regularity assumption on Ω is required. Local finiteness is relative to Ω, so accumulation at its boundary is allowed. Exact coverage is by the tangency polytopes; the balls need not cover Ω. The three PDFs give separate constructions in the three dimensions. The four-dimensional construction includes an exact-integer computer-assisted interpolation step and its complete checker.</p>

<p><em>Sphere Packings and Tangency Tilings in Dimensions Two, Three, and Four: Theorem 1, p. 2; shared Lemmas 2–5, pp. 2–4; planar construction, pp. 4–6; three-dimensional construction, pp. 7–9; four-dimensional construction, pp. 9–16; exact checker, Appendix A, pp. 16–20.</em></p>

</details>

- [Sphere Packings and Tangency Tilings](papers/sphere-packings-and-tangency-tilings.pdf) (20 pages)

**Lean:** coming soon

## Random Walks in Random Environments

### Reflected Random Walks with Spatial Singularities

<details>
<summary>Result</summary>

<p>For random planar cell configurations locally finite away from a closed singular-set witness S of zero one-dimensional Hausdorff measure, assume coverage off S, line connectivity off S, the specified geometric Borel topology and measurable witness-existence class, mass transport modulo translations and positive dilations, and the finite diameter–conductance moment. There is a finite-specific-energy harmonic coordinate with uniformly sublinear corrector.</p><p>With ergodicity modulo the same similarities, the area-clock reflected walk is conservative and recurrent. Its interpolated diffusive rescaling converges from every fixed starting cell to Brownian motion with deterministic positive-definite covariance. Exact holding times Area(H)/π(H) give the same limit. Every graph end has a unique spatial image in S ∪ {∞}, and the path never reaches a spatial-infinity end. Moving-start uniformity is not asserted.</p>

<p><em>reflected-random-walks.pdf: Definition 1.1, Assumption 1.2 and Definition 1.3, pp. 3–4; Theorems 1.4–1.5, pp. 4–5; geometric consequences, pp. 10–12.</em></p>

</details>

- [Reflected Random Walks with Spatial Singularities](papers/reflected-random-walks.pdf) (40 pages)

**Lean:** [Lean](https://github.com/leobon12/lean-formalizations/tree/main/results/reflected-gms). Accompanying formalization of the earlier geometric-topology revision. The linked guide records its correspondence with the current PDF.

## Versions and scope

One consolidated SDP paper contains the constant-comparable median scale, continuous graph limits, and nontriviality. It replaces the separate graph-limit and non-collapse PDFs. Its Section 8 integrates the nontriviality argument with the preceding results and uses the same model and arbitrary deterministic median normalization. Superseded files remain recoverable through repository history.

The geodesic, odd-dimensional field, mesh-only tiling, and sphere-packing papers integrate their former companion notes. Each entry links to one manuscript with shared definitions and the distinct results retained. The whole-plane walk variant has been removed from this selection; its different hypotheses are not claimed to be superseded by the retained singular-set paper. Earlier files remain in repository history.

The machine-readable [catalogue](catalogue.json) records the selected file sizes and SHA-256 hashes.
