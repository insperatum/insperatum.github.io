---
title: Probability
---

- [What Are the "True" Statistics of the Environment? (Feldman, 2016)](https://onlinelibrary.wiley.com/doi/epdf/10.1111/cogs.12444)
  
## Computational learning theory
### PAC Learning
- For input space X, a problem space F is PAC learnable if, for all sampling distributions D over X and all f∈F, a algorithm can, with polynomial probability, produce a g with polynomial expected loss E_D(l(g(x),f(x))) in polynomial time/number of samples.
### PAC Bayes
- Now the algorithm produces a distribution Q(g), and the loss is an expectation over Q.
- The bound is constructed with respect to an arbitrary fixed 'prior' distribution P (it contains KL(Q||P))
- But has nothing to do with bayes??
