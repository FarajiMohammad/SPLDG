## [Sparse multi-label feature selection via pseudo-label learning and dynamic graph constraints (2025)](https://www.sciencedirect.com/science/article/abs/pii/S156625352500048X)

Authors = Yao Zhang, Jun Tang, Ziqiang Cao, and Han Chen

Journal = Information Fusion.

Abstract :
In multi-label feature selection (MLFS), pseudo-label learning techniques are often employed to mitigate the issue that the binary nature of ground-truth labels is incompatible with linear mappings. Existing studies have demonstrated
that manifold learning and distance discrepancy are powerful facilities to well constrain pseudo-labels. However, there are still two weaknesses for the existing manifold learning-based and distance discrepancy-based approaches.
Firstly, the line of manifold learning uses similarity to constrain the pseudo-labels and instances or ground-truth labels to have the same manifold structure between them, but overlooks the detailed constraints on
each pseudo-label vector. Secondly, the line of distance discrepancy does not consider the importance of specific labels. To address these issues, we design a sparse regularization norm and integrate it with the ground-truth
label manifold to jointly constrain pseudo-labels. Furthermore, to overcome the limitations of traditional fixed graph regularization, We introduce feature manifold and dynamic manifold based on dynamic similarity graphs of
low-dimensional pseudo-labels to thoroughly constrain the feature weights. Consequently, a sparse multi-label feature selection via pseudo-label learning and dynamic graph constraints (SPLDG) is proposed. An effective convergence
scheme with alternating iterations is designed to optimize SPLDG. Finally, the experimental results on all 13 multi-label datasets verify that SPLDG can effectively solve the MLFS problem.

If you find this implementation helpful in your work, please consider citing both the original paper and our related research on multi-label feature selection:

## Original Paper:

```
@article{zhang2025sparse,
  title={Sparse multi-label feature selection via pseudo-label learning and dynamic graph constraints},
  author={Zhang, Yao and Tang, Jun and Cao, Ziqiang and Chen, Han},
  journal={Information Fusion},
  volume={118},
  pages={102975},
  year={2025},
  publisher={Elsevier}
}
```
## Our Paper:
```
@article{faraji2024multi,
  title={Multi-label feature selection with global and local label correlation},
  author={Faraji, Mohammad and Seyedi, Seyed Amjad and Tab, Fardin Akhlaghian and Mahmoodi, Reza},
  journal={Expert Systems with Applications},
  volume={246},
  pages={123198},
  year={2024},
  publisher={Elsevier}
}
```
