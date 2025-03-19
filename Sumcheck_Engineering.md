# Challenge: Sumcheck Prover Performance

With the rising popularity of sumchecks in SNARKs, you are called to improve your naive sumcheck prover implementation. Your code supports a multilinear polynomial of dimension n=28 over a 128-bit field, is based on [VSBW13](https://www.pepper-project.org/allspice-oakland13.pdf), and runs on Nvidia L4 GPU.

As you look into recent research, you discover Blendy which seems to offer a better time-space tradeoff. You implement [Blendy](https://eprint.iacr.org/2024/524.pdf) for k=4 on the same GPU, and to your surprise, your old naive algorithm has better latency.

Explain why!

---

To apply, please send your answer to **hr@ingonyama.com**.
