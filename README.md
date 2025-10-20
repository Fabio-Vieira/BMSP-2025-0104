# BMSP-2025-0104

This repositoy contains the supplementary material to reproduce the applications presented in the paper **To Vary or Not To Vary: A Flexible Empirical Bayes Factor for Testing Variance Components**.

## Abstract

Random effects are the gold standard for capturing structural heterogeneity in data, such as spatial
 dependencies, individual differences, or temporal dependencies. However, testing for their presence is
 challenging, as it involves a variance component constrained to be non-negative– a boundary problem.
 This paper proposes a flexible empirical Bayes factor (EBF) for testing random effects. Rather than
 testing whether a variance component is zero, the EBF tests the equivalent hypothesis that all random
 effects are zero. Crucially, it avoids manual prior specification based on external knowledge, as the
 distribution of random effects is part of the model’s lower level and estimated from the data—yielding
 an “empirical” Bayes factor. The EBF uses a Savage-Dickey density ratio, allowing all random effects
 to be tested using only the full model fit. This eliminates the need to fit multiple models with different
 combinations of random effects. Simulations on synthetic data evaluate the criterion’s general behavior.
 To demonstrate its flexibility, the EBF is applied to generalized linear crossed mixed models, spatial
 random effects models, dynamic structural equation models, random intercept cross-lagged panel models,
 and nonlinear mixed effects models.

 A pre-print can be found on this link: <https://arxiv.org/abs/2508.01403>
