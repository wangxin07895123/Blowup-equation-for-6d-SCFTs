# Blowup-equation-for-6d-SCFTs
The data for the elliptic genera and the BPS invariants are based on arXiv:[2006.03030](https://arxiv.org/abs/2006.03030), please cite us.

Contents:
---

1. ../BPS/ : An extensive data of Appendix G.

2. ../EllipticGenera/ : Elliptic genera for various models which are solved from Weyl orbit expansion for n=1,2 and recursion formula for n>=3.
  - In the sub-directory Elliptic_Genera_Massive_n3456/, one finds data files which contain one string elliptic genera with all gauge and flavor fugacities turned on, expanded up to subleading order of Qtau. These data files can be simply loaded using the ``Get[..]'' command, and then the one-string genus is found in the variable *E1RedMassive*. We use the convention that
    + Gauge fugacities: \xi[i] = \exp 2\pi i (\omega_i, m_G), where \omega_i are fundamental weights.
    + Flavor fugacities: \zeta[i] = \exp 2\pi i (\omega_{(i)}, m_F), where omega_{(i)} are half of the weights in the flavor representation, so that no pair of them add up to zero.

3. [EllipticGeneraAppendix.nb](EllipticGeneraAppendix.nb) : Modular ansatz results for various unfixed models in arXiv:1804.09694
