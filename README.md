# Mutual Information Lab

An interactive study guide for §6.3 of Kevin P. Murphy, *Probabilistic Machine Learning: An Introduction*
(mutual information; §6.3.6 normalized MI, §6.3.7 MIC, and §6.3.10 Fano's inequality omitted).

**Live:** https://isaackrallison.github.io/mutual-information/

- **6.3.1 Definition:** drag cells of a 3×3 joint and compare it to p(x)p(y) cell by cell, with each cell's signed contribution to the KL sum and a slider that blends the joint toward independence.
- **6.3.2 Interpretation:** an information diagram whose circle areas are H(X) and H(Y) and whose overlap is I(X;Y), with Eqs. 6.49–6.51 highlighted region by region (driven by a noisy channel or by your §6.3.1 table).
- **6.3.3 Example:** the even/prime example, extended to n ∈ 1…N, with "observe X" to see each row's conditional entropy.
- **6.3.4 Conditional MI:** three binary variables (common cause, redundancy, XOR, irrelevant Z) shown as Z-slices, plus the chain rule revealed in both orders.
- **6.3.5 Gaussian MI:** −½log(1−ρ²) against a live scatter, plus a binned MI estimator showing its bias, and non-linear shapes where ρ ≈ 0 but MI is large.
- **6.3.8 Data processing inequality:** a telephone game where information decays hop by hop, and "can clever processing beat it?" with majority vote, count, parity, and more.
- **6.3.9 Sufficient statistics:** coin flips where you compare posteriors and I(θ; s(D)) for six candidate statistics.
- Step-by-step math breakdowns and a quiz for every section.

Single self-contained `index.html`, no build step. Loads Google Fonts and MathJax from cdnjs.
