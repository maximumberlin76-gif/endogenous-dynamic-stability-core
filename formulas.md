Formulas

---

1. Fundamental Dynamics

Let X(t) ∈ ℝⁿ be the system state.

dX/dt = F(X, t) = S(X,t) − P(X,t) − D(X,t)

Define:

Δ(t) = S − P − D

---

2. Stability Conditions

Local (instantaneous)

Δ(t) ≥ ε > 0

Integral (finite horizon)

Δ_T = ∫_0^T (S − P − D) dt > 0

---

3. Dynamic Equilibrium

S(t) ≈ P(t) + D(t)

---

4. Quasi-Stationary Regime

d⟨O⟩/dt ≈ 0  with ongoing internal dynamics

---

5. Coherence Coupling

C(t) ∈ (0,1]

S_eff = C · S
D_eff = D / C

---

6. Scaling Law (phenomenological)

S ∼ X^α
P ∼ X^β
D ∼ X^γ

Stability at scale requires:

α ≥ max(β, γ)

---

7. Linear Stability (Lyapunov)

Linearize near X*:

dξ/dt = J(X*) ξ,  where J = ∂F/∂X

Stable if:

Re(λ_i(J)) < 0  for all i

---

8. Lyapunov Function (energy-like)

Choose V(X) ≥ 0

dV/dt = ∇V · F(X)

Stable if:

dV/dt ≤ 0

Asymptotically stable if:

dV/dt < 0

---

9. Bifurcation (Hopf)

At parameter μ:

Re(λ(μ)) crosses zero:

Re(λ(μ_c)) = 0

If Im(λ(μ_c)) ≠ 0:

⇒ Hopf bifurcation
⇒ emergence of limit cycle

---

10. Noise and Stochasticity

dX = F(X,t) dt + σ dW_t

Stability becomes probabilistic:

E[Δ] > 0

---

11. Human System

R — recovery resource

Stability:

R ≥ R_crit
Δ ≥ 0

---

12. Final Condition

System remains viable if:

∫_0^T (S − P − D) dt > 0

under bounded dissipation and sufficient coherence.
