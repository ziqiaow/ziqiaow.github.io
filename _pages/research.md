---
layout: page
permalink: /research/
title: Research
nav: true
sort: 3
---
  
  <div class="publications" markdown="1">
  <p>A full list of my publications are available here: <a href="https://scholar.google.com/citations?user=n6MtCyUAAAAJ&hl=en&oi=ao" target="_blank">Google Scholar</a> </p>
  
&nbsp;

---
#####  __Efficient Modeling of Polygenic Risk Scores and Environment Interplay__

We developed a series of novel methods for modeling of polygenic scores (PGS) in different epidemiological study designs. These include joint modeling of polygenic gene-environment correlations and interactions in case-control studies, and unified modeling of direct, indirect, and gxe interactions in family-based studies. We have shown improved efficiency in case-control studies that are comparable to cohort studies. Family-based methods can further eliminate potential population stratification bias in PGS estimations.


<p align="center">
<img src="/assets/img/research_gxe.png" width=90% >
</p>

- __Wang, Z.__, Shi, W., Carroll, R., Chatterjee, N. (2024). Joint Modeling of Gene-Environment Correlations and Interactions Using Polygenic Risk Scores in Case-Control Studies. *__American Journal of Epidemiology__*, 2024. DOI: 10.1093/aje/kwae081
[[Paper]](https://doi.org/10.1093/aje/kwae081) 
[[Software]](https://github.com/ziqiaow/RetroGE)  
- __Wang, Z.__, Ray, D., Grosvenor, L., Beaty, T., Volk, H., Ladd-Acosta, C., Chatterjee, N. Novel Methods for Estimating Risk Parameters Associated with Polygenic Scores using Case-Parent Trio Designs. 2024+.
[[Paper]]() 
[[Software]](https://github.com/ziqiaow/PRS-TRI)  

&nbsp;



---

##### __Multi-Omics Data Integration__
We developed novel methods for data integrations to examine the associations between genes and disease phenotype through multiple layers of omic information. Our methods are based on multivariate Gaussian mixture models to characterize the precise correlations between different data types using summary statistics, leading to superior statistical power in association studies. We have also extended this work to spatially resolved high-dimensional genomics data, including DNA methylation and RNA sequencing data using specific datasets in bladder tumor samples, to increase the power of finding molecular signals contributing to cancer initiation, promotion, and progression. 

Our work has several key advantages over conventional designs, including the novel feature of controlling the false discovery rate in significant genes across multiple omics data types, the ability to incorporate independent or overlapping sets of cohorts with respect to omics data, the generality of applications to meta-analysis and gene enrichment pathways, and fast computational efficiency by adopting the expectation-maximization (EM) algorithm.


<p align="center">
<img src="/assets/img/research_spatialimix.png" width=90% >
</p>


-	__Wang, Z.__, Wei, P. IMIX: A Multivariate Mixture Model Approach to Association Analysis Through Multi-Omics Data Integration. *__Bioinformatics__*, 2020. DOI:10.1093/bioinformatics/btaa1001
[[Paper]](https://doi.org/10.1093/bioinformatics/btaa1001)
[[Software]](https://github.com/ziqiaow/IMIX)
__(Platform presentation, ASHG 2020)__
-	__Wang, Z.__, Czerniak, B., Wei, P. Spatial IMIX: A Mixture Model Approach to Spatially Correlated Multi-Omics Data Integration. *Preprint*, 2023. DOI:10.1101/2023.07.15.549148
[[Paper]](https://www.biorxiv.org/content/10.1101/2023.07.15.549148v1)
[[Software]](https://github.com/ziqiaow/spatialimix)



&nbsp;


---

##### __Epigenome-Wide Association Studies in Cancer__
We also investigated the role of DNA methylation in whole blood affecting susceptibility to pancreatic cancer. We performed a two-phase epigenome-wide association study by examining two independent case-control studies measured within MDA and leveraged the Framingham Heart Study data to increase the sample size in controls. We discovered important differentially methylated CpG sites and regions associated with pancreatic cancer, and validated the results using a third independent dataset from the Women's Health Initiative. We further confirmed the causal relationship of the discovered CpG sites using Mendelian randomization analysis, and investigated the functional consequences in gene expression. We performed another large-scale EWAS in studying the role of differentially methylated CpG sites between HPV-positive and HPV-negative oropharyngeal cancer patients and discovered a long non-coding RNA nc886 that leads to further important clinical implications.


<p align="center">
<img src="/assets/img/research_methylation.jpg" width=90% >
</p>


-	__Wang, Z.__, Lu, Y., Fornage, M., Jiao, L., Li, D., Wei, P. Identification of novel susceptibility methylation loci for pancreatic cancer in a two-phase epigenome-wide association study. *__Epigenetics__*, 2022. DOI: 10.1080/15592294.2022.2026591
[[Paper]](https://doi.org/10.1080/15592294.2022.2026591)
__(Platform presentation, IGES 2019)__
-	Xu, Y.(co-first author), __Wang, Z.__(co-first author), Wei, P., Gairola, R., Kelsey, K., Sikora, A., Li, G., Gu, J. Hypermethylation of nc886 in HPV-positive oropharyngeal cancer and its clinical implications: an epigenome DNA methylation profiling study. *__Molecular Therapy-Nucleic Acids__*, 2022. DOI:10.1016/j.omtn.2022.11.012
[[Paper]](https://doi.org/10.1016/j.omtn.2022.11.012)


&nbsp;


---

##### __Method for Benefit-Risk Analysis in Clinical Trials__
I collaborated with Dr. Jie Chen at Merck during my summer internship and developed a novel method to test for significant trend effects of multiple dosage levels of medication use by using composite endpoints in clinical trial studies. This method prioritizes the user's intended endpoints including the adverse events and efficacy endpoints and assesses whether the examined dose levels in clinical trials show an increasing or decreasing trend effect. This method is computationally fast and robust to type I errors.



-	__Wang, Z.__, Chen J. Testing for Trend in Benefit-Risk Analysis with Prioritized Multiple Outcomes. *__Statistics in Biopharmaceutical Research__*, 2020. DOI: 10.1080/19466315.2019.1690037
[[Paper]](https://www.tandfonline.com/doi/full/10.1080/19466315.2019.1690037)
[[Software]](https://github.com/ziqiaow/MvTrend)

&nbsp;



---