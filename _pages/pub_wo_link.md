---
layout: archive
permalink: /publications_list/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reference List</title>
    <style>
        ol.references {
            counter-reset: list-counter; /* Initialize a custom counter */
            padding-left: 0;
        }
        ol.references li {
            counter-increment: list-counter; /* Increment the counter for each item */
            list-style: none; /* Remove default list styling */
            margin-bottom: 10px;
            padding-left: -10px;
            text-indent: -10px;
        }
        ol.references li::before {
            content: "[" counter(list-counter) "] "; /* Automatically add brackets around the counter */
            /*font-weight: bold;*/
            padding-right: 10px;
            padding-left: 10px;
        }
    </style>
</head>

Publications
======

<ol class="references">

### JOURNAL PAPERS (SUBMITTED) 
1. <ins>M. Zhu</ins> and A. Bemporad, “Global and preference-based optimization with mixed variables using piecewise aﬃne surrogates,” 2023, Submitted for publication. [arXiv](https://arxiv.org/abs/2302.04686), [code](https://github.com/mjzhu-p/PWAS)



### JOURNAL PAPERS (IN PRESS)

1. <ins>M. Zhu</ins>, A.  Mroz, L. Gui, K. Jelfs, A. Bemporad, EA. del Río Chanona, and Y. Lee, "Discrete and mixed-variable experimental design with surrogate-based approach," Digital Discovery, 2024, in press. [paper-link](https://doi.org/10.1039/D4DD00113C), [code](https://github.com/MolChemML/ExpDesign), [ChemRxiv](https://chemrxiv.org/engage/chemrxiv/article-details/6626a713418a5379b0674df2)


### JOURNAL PAPERS
1. L. Cannelli, <ins>M. Zhu</ins>, F. Farina, A. Bemporad, and D. Piga, “Multi-agent active learning for distributed black-box optimization,” IEEE Control Systems Letters, vol. 7, pp. 1488–1493, 2023.. [paper-link](https://ieeexplore.ieee.org/document/10107979), [pdf](http://mjzhu-p.github.io/files/2023-dglis-lcss.pdf), [code](https://leon.idsia.ch/lib_download)
1. <ins>M. Zhu</ins>, D. Piga, and A. Bemporad, “C-GLISp: Preference-based global optimization under unknown constraints with applications to controller calibration,” IEEE Trans. Contr. Systems Technology, vol. 30, no. 3, pp. 2176–2187, Sept. 2022. [paper-link](https://doi.org/10.1109/TCST.2021.3136711), [pdf](http://mjzhu-p.github.io/files/2022-tcst-cglisp.pdf), [code](https://github.com/bemporad/GLIS)


### CONFERENCE PAPERS (SUBMITTED)
1. S. Kay, <ins>M. Zhu</ins>, O. Pennington, and Dongda Zhang, "Machine Learning-Driven Optimisation of Operational Spaces for Uncertainty Management in Process Industries," 2024, submitted for publication.

### CONFERENCE PAPERS
1. <ins>M. Zhu</ins>, A. Bemporad, M. Kneissl, and H. Esen, “Learning critical scenarios in feedback control systems for automated driving,” in IEEE 26th Int. Conf. on Intelligent Transportation Systems (ITSC), Bilbao, Bizkaia, Spain, Sept. 2023. [paper-link](https://ieeexplore.ieee.org/document/10421978), [pdf](https://arxiv.org/pdf/2209.12586)
1. <ins>M. Zhu</ins>, A. Bemporad, and D. Piga, “Preference-based MPC calibration,” in European Control Conference, 2021. [paper-link](https://doi.org/10.23919/ECC54610.2021.9654900), [pdf](http://mjzhu-p.github.io/files/2021-ecc.pdf)

### BOOK CHAPTERS
1. A. Molin, E. Aguilar, D. Nickovic, <ins>M. Zhu</ins>, A. Bemporad, and H. Esen, “Speciﬁcation-guided critical scenario identiﬁcation for automated driving,” 25th International Symposium on Formal Methods, 2023. [paper-link](https://doi.org/10.1007/978-3-031-27481-7_35), [pdf](https://arxiv.org/pdf/2303.05139.pdf)
1. <ins>M. Zhu</ins>, FL. Santamaria, S. Macchietto, "A general dynamic model of a complete milk pasteuriser unit subject to fouling," in Computer Aided Chemical Engineering, vol. 48, pp. 247-252, 2020. [paper-link](https://doi.org/10.1016/B978-0-12-823377-1.50042-2), [pdf](http://mjzhu-p.github.io/files/2020-escape30.pdf)

### TECHNICAL REPORTS
1. <ins>M. Zhu</ins>, D. Piga, and A. Bemporad, “C-GLIS:  Global Optimization under Unknown Constraints,” 2021. [pdf](https://mjzhu-p.github.io/files/2021-cglis_post.pdf)


### THESES
1. <ins>M. Zhu</ins>, "Global and preference-based optimization using surrogate-based methods", Ph.D. dissertation, Systems Science, Track in Computer Science and Systems Engineering, 
IMT School for Advanced Studies Lucca (Scuola IMT Alti Studi Lucca), Lucca, Italy, May 2024. [pdf](https://e-theses.imtlucca.it/415/1/ZhuMengjia_Thesis_final%20version.pdf)
2. <ins>M. Zhu</ins>, "A general dynamic model of a complete milk pasteuriser unit subject to fouling," MSc. thesis, Imperial College London, London, UK, September 2018.








</ol>
