### PAC Learning
- For input space X, a problem space F is PAC learnable if, for all sampling distributions D over X and all f∈F, a algorithm can, with polynomial probability, produce a g with polynomial expected loss E_D(l(g(x),f(x))) in polynomial time/number of samples.

### PAC Bayes
- Now the algorithm produces a distribution Q(g), and the loss is an expectation over Q.
- The bound is constructed with respect to an arbitrary fixed 'prior' distribution P (it contains KL(Q||P))
- But has nothing to do with bayes?? I guess it has a prior-like term (it's smaller when Q is close to P) and a likelihood-like term (it's smaller when the empirical loss is small)?
