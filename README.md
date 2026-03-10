# Uniqueness and Maximality of the Planar 6-Point Isosceles Set: A Proof via Gallai Colorings

## The Result

A finite set of points in the plane is called an **isosceles set** if every triple of points forms an isosceles triangle (including equilateral). In 1946, Erdős asked: what is the largest such set in ℝ²?

The answer is **6 points**: the five vertices of a regular pentagon plus its center.

This paper gives a new proof of both:
1. **Uniqueness** — the pentagon + center is the *only* 6-point isosceles set (up to similarity)
2. **Maximality** — no 7-point isosceles set exists, so 6 is the absolute maximum

## The Method

We translate the isosceles condition into a **Gallai coloring** (rainbow-triangle-free edge-coloring) of the complete graph K_n, then use Gallai's structural theorem to reduce the problem to finitely many partition types. Each partition is eliminated using elementary Euclidean geometry — primarily the fact that **two distinct circles intersect in at most two points**.

For maximality, we introduce a **monotonicity principle**: if a Gallai partition type is geometrically impossible, then adding points or groups preserves the impossibility. This reduces the n = 7 case to a single new partition (6+1), which is eliminated by the main theorem.

## How This Differs from Previous Proofs

| Proof | Method |
|---|---|
| Kelly (1947) | Direct case analysis on edge lengths |
| Kovács (2024) | Gröbner basis and elimination ideals |
| **This paper** | **Gallai colorings + circle intersection arguments** |

## Files

- `proof.tex` — LaTeX source
- `proof.pdf` — Compiled paper (5 pages)

## Key References

- P. Erdős and L. M. Kelly, *Elementary Problems and Solutions: E735*, Amer. Math. Monthly **54** (1947), 227–229.
- Z. Kovács, *A note on Erdős's mysterious remark*, arXiv:2412.05190, December 2024.
- T. Gallai, *Transitiv orientierbare Graphen*, Acta Math. Acad. Sci. Hungar. **18** (1967), 25–66.
- S. J. Einhorn and I. J. Schoenberg, *On Euclidean sets having only two distances between points*, Indag. Math. **28** (1966), 479–488.

## Authorship and Collaboration

This proof was constructed through a **human–AI collaboration** directed by **Saeb Swaity** (Hebron, Palestine), who coordinated the investigation, proposed the monotonicity principle and partition pruning framework used in the maximality argument.

**AI contributions:**
- **Gemini (Google)** — Introduced the key idea of applying Gallai's coloring theorem to the isosceles set problem
- **Claude (Anthropic)** — Verification, computation, proof assembly, and corrections
- **ChatGPT (OpenAI)** — Independent verification and computation

The result itself is classical. The contribution lies in the proof method.

## License

This work is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You are free to share and adapt it with appropriate credit.

## Citation

If you reference this work, you can cite:

```
Swaity, S. (2026). Uniqueness and Maximality of the Planar 6-Point Isosceles Set:
A Proof via Gallai Colorings. Available at: https://github.com/[your-username]/isosceles-set-gallai-proof
```

## Contact

Saeb Swaity — Hebron, Palestine

For questions, endorsement offers (arXiv), or collaboration: feel free to open an issue or reach out on LinkedIn.
