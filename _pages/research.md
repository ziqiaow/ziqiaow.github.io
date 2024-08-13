---
layout: page
permalink: /research/
title: Research
nav: true
sort: 3
---
  
  <div class="publications" markdown="1">
  <p>A full list of publications are available here: <a href="https://scholar.google.com/citations?user=n6MtCyUAAAAJ&hl=en&oi=ao" target="_blank">Google Scholar</a> </p>
  
&nbsp;

---
#####  __Efficient Modeling of Polygenic Risk Scores and Environment Interplay__
<div class="row justify-content-sm-center">
  <div class="col-sm-4 mt-3 mt-md-0">
  {% include figure.liquid path="assets/img/research_gxe.png" title="A Unified Model of Estimating Polygenic Risks in Case-Parent Trio Design" class="img-fluid rounded z-depth-1" %}
</div>
  <div class="col-sm-8 mt-3 mt-md-0">We developed a novel method for joint modeling of gene-environment correlations and interactions using polygenic scores in case-control studies. This method can improve the efficiency of the parameter estimation of PRS and environment interactions by exploiting the natural model constraint that the inherited genetic susceptibilities and environmental exposures are independent in the underlying population. This method is robust in the case when the assumption of gene-environment independence is violated, by introducing an additional parameter to leverage the gene-environment correlations jointly in the model. We applied the UK Biobank data to assess the model performance using reduced numbers of case-control data and showed the model's ability to recover the power in a full cohort study and discovered important interactions between long-term oral contraceptive use and breast cancer polygenic risk scores in premenopausal and postmenopausal women cohorts respectively. This method is computationally simple and fast, robust to the possible violation of the independence assumption, and can lead to great efficiency gain compared to standard logistic regression method.</div>
  </div>  


- __Wang, Z.__, Shi, W., Carroll, R., Chatterjee, N. (2024). Joint Modeling of Gene-Environment Correlations and Interactions Using Polygenic Risk Scores in Case-Control Studies. *American Journal of Epidemiology*, 2024. DOI: 10.1093/aje/kwae081
[[Paper]](https://doi.org/10.1093/aje/kwae081) 
[[Software]](https://github.com/ziqiaow/RetroGE)  
- __Wang, Z.__, Ray, D., Grosvenor, L., Beaty, T., Volk, H., Ladd-Acosta, C., Chatterjee, N. Novel Methods for Estimating Risk Parameters Associated with Polygenic Scores using Case-Parent Trio Designs. 2024+.
[[Paper]]() 
[[Software]](https://github.com/ziqiaow/PRS-TRI)  

&nbsp;


---

##### __Multi-Omics Data Integration__
<div class="row justify-content-sm-center">
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/research_spatialimix.png" title="Spatial IMIX" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-7 mt-3 mt-md-0">During my doctoral training period, I developed novel methods for data integrations to examine the associations between genes and disease phenotype through multiple layers of omic information. My methods are based on multivariate Gaussian mixture models to characterize the precise correlations between different data types using summary statistics, leading to superior statistical power in association studies. I have also extended this work to spatially resolved high-dimensional genomics data, including DNA methylation and RNA sequencing data using specific datasets in bladder tumor samples, to increase the power of finding molecular signals contributing to cancer initiation, promotion, and progression. My work has several key advantages over conventional designs, including the novel feature of controlling the false discovery rate in significant genes across multiple omics data types, the ability to incorporate independent or overlapping sets of cohorts with respect to omics data, the generality of applications to meta-analysis and gene enrichment pathways, and fast computational efficiency by adopting the expectation-maximization (EM) algorithm.</div>

-	__Wang, Z.__, Wei, P. IMIX: A Multivariate Mixture Model Approach to Association Analysis Through Multi-Omics Data Integration. *Bioinformatics*, 2020. DOI:10.1093/bioinformatics/btaa1001
[[Paper]](https://doi.org/10.1093/bioinformatics/btaa1001)
[[Software]](https://github.com/ziqiaow/IMIX)
-	__Wang, Z.__, Czerniak, B., Wei, P. Spatial IMIX: A Mixture Model Approach to Spatially Correlated Multi-Omics Data Integration. *Preprint*, 2023. DOI:10.1101/2023.07.15.549148
[[Paper]](https://www.biorxiv.org/content/10.1101/2023.07.15.549148v1)
[[Software]](https://github.com/ziqiaow/spatialimix)



&nbsp;


---

##### __Epigenome-Wide Association Studies in Cancer__
<div class="row justify-content-sm-center">
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/research_methylation.png" title="Example Figure 1: DNA Methylation" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-7 mt-3 mt-md-0">The other contribution I made during my doctoral training period was investigating the role of DNA methylation in whole blood affecting susceptibility to pancreatic cancer. I carried out a two-phase epigenome-wide association study by examining two independent case-control studies measured within MDA and leveraged the Framingham Heart Study data to increase the sample size in controls. I discovered important differentially methylated CpG sites and regions associated with pancreatic cancer. I validated the results using a third independent dataset from the Women's Health Initiative, further confirmed the causal relationship of the discovered CpG sites using Mendelian randomization analysis, and investigated the functional consequences in gene expression. In short, this pioneering study yielded valuable information on how DNA methylation and gene expression relate to disease susceptibility, with clear implications for diagnosing and treating pancreatic cancer, where treatments tend to be complicated due to diagnosis at later stages. I performed another large-scale EWAS in studying the role of differentially methylated CpG sites between HPV-positive and HPV-negative oropharyngeal cancer patients and discovered a long non-coding RNA nc886 that leads to further important clinical implications.</div>
&nbsp;

-	__Wang, Z.__, Lu, Y., Fornage, M., Jiao, L., Li, D., Wei, P. Identification of novel susceptibility methylation loci for pancreatic cancer in a two-phase epigenome-wide association study. *Epigenetics*, 2022. DOI: 10.1080/15592294.2022.2026591
\emph{\underline{Platform presentation, IGES 2019}}
[[Paper]](https://doi.org/10.1080/15592294.2022.2026591)
-	Xu, Y.(co-first author), __Wang, Z.__(co-first author), Wei, P., Gairola, R., Kelsey, K., Sikora, A., Li, G., Gu, J. Hypermethylation of nc886 in HPV-positive oropharyngeal cancer and its clinical implications: an epigenome DNA methylation profiling study. *Molecular Therapy-Nucleic Acids*, 2022. DOI:10.1016/j.omtn.2022.11.012
[[Paper]](https://doi.org/10.1016/j.omtn.2022.11.012)


&nbsp;


---

##### __Method for Benefit-Risk Analysis in Clinical Trials__
<div class="row justify-content-sm-center">
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/research_dose.png" title="Example Figure 2: Benefit Risk Analysis in Difference Doses" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-7 mt-3 mt-md-0">I collaborated with Dr. Jie Chen at Merck during my summer internship and developed a novel method to test for significant trend effects of multiple dosage levels of medication use by using composite endpoints in clinical trial studies. This method prioritizes the user's intended endpoints including the adverse events and efficacy endpoints and assesses whether the examined dose levels in clinical trials show an increasing or decreasing trend effect. This method is computationally fast and robust to type I errors.</div>

-	__Wang, Z.__, Chen J. Testing for Trend in Benefit-Risk Analysis with Prioritized Multiple Outcomes. *Statistics in Biopharmaceutical Research*, 2020. DOI: 10.1080/19466315.2019.1690037
[[Paper]](https://www.tandfonline.com/doi/full/10.1080/19466315.2019.1690037)
[[Software]](https://github.com/ziqiaow/MvTrend)

&nbsp;

Example Figures Sources:[1](https://www.labclinics.com/2018/11/08/role-dna-methylation-disease/?lang=en) [2](https://i-base.info/ttfa/learning-resources/drug-levels-drug-activity-and-side-effects/)
