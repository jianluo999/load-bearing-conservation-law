# A Load-Bearing Conservation Law and Its Self-Recording Fixed Point

**The Degeneration Spectrum as a Corollary Chapter**

Preprint manuscript (amsart_submission_v16.pdf).

## Summary

We isolate a bottom-level structure and prove exactly what it does and does not determine. Its conserved kernel is the Piola cofactor identity `div ℓ adj(∇²ψ) = 0` (an identity for every Hessian) together with the mother chain `E_H(t) = det(I + tH) = Σ_k e_k(H) t^k`. The softmax instance adds the rank-one image `adj(G) = (∏_j p_j) 11^T`; this rank-one structure, not the Piola identity alone, is what makes the tensor load-bearing.

All conserved coefficients are readings of the one mother chain under three operations (coefficient extraction, index reversal, terminal power). Power sums `tr H^j` are polynomial recombinations of the same coefficients by Newton's identities and therefore add no fourth independent generator.

Two normalization conventions are fixed explicitly and are not claimed to be consequences of the conservation law. In the `J = 11^T` frame one has the identity `det(G + cJ) = c 1^T adj(G) 1 = c N² ∏_j p_j = c N f` for every real `c`; choosing the gauge-line stiffness so that the datum equals `f = [t¹] det(I + t adj G)` gives `λ* = 1/N`. In the normalized frame `E = J/N = e e^T` the same identity reads `det(G + cE) = c f` and the same choice is `c = 1`. Thus `λ* = 1/N` is a canonical normalization of the gauge direction, not a value forced by the conservation law.

The second result is a self-recording fixed point: substituting the Reynolds projection `P_G` into the mother chain gives `det(I + t P_G) = (1 + t)^{D²}`, with `D = (m k)` determined by the compound space alone. Its solution set is the trivial group, whose layer algebra is the full-matrix space `A_G = End(V^k)`: the undegraded case.

The organizing principle of the paper is also its main structural claim: the corollary set of the load-bearing structure is the entire mainstream architecture family — CNN, Transformer, RNN / SSM–Mamba / RWKV, Mixer, MoE, GNN and the remaining architectures.

## 2020 Mathematics Subject Classification

Primary: 15A75, 35J96
Secondary: 20C30, 22C05, 53B12

## Keywords

Piola identity; determinant generating function; compound matrix; Reynolds projection; Monge–Ampère equation; self-recording fixed point; degeneration spectrum; equivariant layer algebra

## License

This preprint is released for review and discussion. See the manuscript for the full provenance and license statement.
