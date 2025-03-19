# Challenge: Polynomial Evaluation Challenge

[Link to Repository](https://github.com/ingonyama-zk/poly-eval-challenge)

In many zero-knowledge (ZK) protocols, we need to evaluate polynomials defined over a scalar finite field. Your task is to implement an efficient solution in CUDA that can evaluate multiple polynomials over the same domain.
‍
For example, evaluate the polynomials P₁(x), P₂(x), ..., Pₙ(x) over the domain {4, 7, 9}. Here, n is the batch_size, domain_size is 3, and coeffs_size represents the shared degree of the polynomials.

You need to implement the function poly_eval() in the file poly_eval.cu. To test and bench - run make test_poly_eval. The function should run for any valid input parameters but the typical parameters are those given in the test file.

Good luck!

---

To apply, please send your answer to hr@ingonyama.com
