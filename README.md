# Optimal Transport Barycenters

<hr>

**_Dépôt labelisé dans le cadre du [Label Reproductible du GRESTI'25](https://gretsi.fr/colloque2025/recherche-reproductible/)_**

| Label décerné | Auteur | Rapporteur | Éléments reproduits | Liens |
|:-------------:|:------:|:----------:|:-------------------:|:------|
| ![](label_argent.png) | Eloi TANGUY<br>[@eloitanguy](https://github.com/eloitanguy) | Mathieu LEONARDON<br>[@bonben](https://github.com/bonben) |  Figures 1, 2, 3, 4, 5 et 6 | 📌&nbsp;[Dépôt&nbsp;original](https://github.com/eloitanguy/ot_bar)<br>⚙️&nbsp;[Issue](https://github.com/GRETSI-2025/Label-Reproductible/issues/14)<br>📝&nbsp;[Rapport](https://github.com/akrah/test/tree/main/rapports/Rapport_issue_14) |

<hr>

This repository provides code for the fixed-point approach to OT barycenters
with arbitrary cost functions, and our implementation for [our preprint](https://arxiv.org/abs/2407.13445).

The main function to use in practice is
`ot_bar.solvers.solve_OT_barycenter_fixed_point` which solves the OT barycentre
problem using the (barycentric) fixed-point method.

To install required packages:

    pip install -r requirements.txt

To install this repository as an editable package:

    pip install -e .

### To cite this work:

    @misc{tanguy2025constrainedapproximateoptimaltransport,
        title={Constrained Approximate Optimal Transport Maps}, 
        author={Eloi Tanguy and Agnès Desolneux and Julie Delon},
        year={2025},
        eprint={2407.13445},
        archivePrefix={arXiv},
        primaryClass={math.OC},
        url={https://arxiv.org/abs/2407.13445}, 
    }
