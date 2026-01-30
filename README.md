# Evaluating Demographic Misrepresentation in Image-to-Image Portrait Editing

**[Project Page](https://seochan99.github.io/i2i-demographic-bias/)**

> We expose demographic-conditioned failures in I2I portrait editing—**Soft Erasure** and **Stereotype Replacement**—showing pervasive skin lightening and identity drift, and propose a prompt-level mitigation that reduces bias without model updates.

## Authors

**Huichan Seo**<sup>1*</sup>, **Minki Hong**<sup>2*</sup>, **Sieun Choi**<sup>2*</sup>, **Jihie Kim**<sup>2</sup>, **Jean Oh**<sup>1</sup>

<sup>1</sup>Carnegie Mellon University · <sup>2</sup>Dongguk University · <sup>*</sup>Equal contribution

## Key Findings

- **Pervasive skin lightening**: 62–71% of all edited outputs exhibit lighter skin tones. Indian and Black subjects experience 72–75% vs. 44% for White subjects.
- **Asymmetric mitigation**: Feature prompts reduce race change by 1.48 points for Black subjects but only 0.06 for White subjects, revealing a "default to White" prior.
- **Gender-occupation bias**: Models follow occupational stereotypes in 84–86% of cases, overriding source gender with occupation-driven priors.

## Links

| Resource | Status |
|----------|--------|
| [Project Page](https://seochan99.github.io/i2i-demographic-bias/) | Available |
| arXiv | Coming Soon |
| Code & Data | Coming Soon |
| Hugging Face | Coming Soon |

## Citation

```bibtex
@article{seo2026demographic,
  title={Evaluating Demographic Misrepresentation in Image-to-Image Portrait Editing},
  author={Seo, Huichan and Hong, Minki and Choi, Sieun and Kim, Jihie and Oh, Jean},
  journal={arXiv preprint},
  year={2026}
}
```
