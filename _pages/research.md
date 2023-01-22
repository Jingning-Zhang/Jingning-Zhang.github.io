---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
--- 

My research interests lie primarily in developing statistical and computational methods to address public health problems by data integration from large datasets. Below I will introduce my current accomplishments in more detail.

  
Plasma proteome analyses in individuals of European and African ancestry identify cis-pQTLs and models for proteome-wide association studies
------
**Jingning Zhang**, Diptavo Dutta, Anna Kottgen, Adrienne Tin, Pascal Schlosser, Morgan E. Grams, Benjamin Harvey, CKDGen Consortium, Bing Yu, Eric Boerwinkle, Josef Coresh, Nilanjan Chatterjee. Plasma proteome analyses in individuals of European and African ancestry identify cis-pQTLs and models for proteome-wide association studies. Nature Genetics 54.5 (2022): 593-602. [\[Puslished manuscript\]](https://www.nature.com/articles/s41588-022-01051-w)

- Manuscript published on *Nature Genetics 54.5 (2022): 593-602*.
- Proposed pipeline for cleaning and preprocessing high-throughput protein data measured by SomaScan assays, performed cis- protein quantitative trait loci (cis-pQTL) analysis in large bi-ancestry population from ARIC cohort, and studied the shared and distinct genetic architecture between the two ancestries. Performed fine-mapping for cis-pQTLs, and colocalization analysis with cis-eQTLs from GTEx project.
- Built imputation models for plasma protein levels using machine learning method based on the cis-variants of corresponding protein-encoding gene, which can be used to conduct proteome-wide association studies (PWAS) in external dataset for identifying potential causal proteins for complex traits.
- Demonstrated an application of PWAS for gout, resulting in the exemplary identification of the IL1RN protein that reveals the promise of the drug repurposing of anakinra to treat gout, which suggests utilizing our results to investigate the causal role of plasma proteins on complex traits and their drug repurposing potential.
- Created a web resource for downloading summary statistics data and PWAS models with searchable options for exploring/viewing various results from our analyses ([http://nilanjanchatterjeelab.org/pwas](http://nilanjanchatterjeelab.org/pwas)).


An ensemble penalized regression method for multi-ancestry polygenic risk prediction
------
**Jingning Zhang**, Jianan Zhan, Jin Jin, Cheng Ma, Ruzhang Zhao, Jared O' Connell, Yunxuan Jiang, 23andMe Research Team, Bertram L Koelsch, Haoyu Zhang, Nilanjan Chatterjee. An ensemble penalized regression method for multi-ancestry polygenic risk prediction. Prepared for submission to Nature Methods 2021+ [\[Slides\]](https://github.com/Jingning-Zhang/PROSPER/blob/main/PROSPER.pdf)

- Manuscript prepared for submission to *Nature Methods*.
- Proposed a novel method for generating multi-ancestry Polygenic Risk scOres based on enSemble of PEnalized Regression models (PROSPER) for predicting complex traits / disease risk by integrating summary statistics from genome-wide association studies (GWAS) and individual-level reference data.
- In simulation and real data analyses, PROSPER has substantial improvement compared to alternative methods across a wide variety of genetic architectures, and is an order of magnitude faster than an existing multi-ancestry method (PRS-CSx).
  
Proteomic mediation of genetic risks of cancers
------
**Jingning Zhang**\*, Diptavo Dutta\*, Josef Coresh, Montserrat Garcia-Closas, Bing Yu, Eric Boerwinkle, Elizabeth Platz, Corinne Joshu, Aaron Folsom, Nilanjan Chatterjee. Proteomic Mediation of Genetic Risks of Cancers. 2022+ (\*Co-first author)

- Proposed to use polygenic risk score (PRS) to identify major cancer proteins through which the genetic risk of cancers may be mediated.
- Obtained PRS for 21 common cancers from PGS Catalog, and associated PRS to plasma proteins from ARIC cohort by partitioning them for characterizing cis and trans proteomic mediation.
- Identified multiple potential trans-regulated cancer proteins encoded by genes without genome-wide significant cis GWAS hit, and some of those proteins are biological meaningful for cancers.
  

Statistical Modeling for skewed data using mixed-effects model
------
Advised by Dr. Yuanyuan Tang and Dr. Yongming Qu at Eli Lilly and Company, June 2022 -- Aug. 2022

- In the framework of mixed-effects model (MM), I proposed a statistics to summarize the population-level treatment effect, e.g., change from baseline, and proposed an estimator for it. The estimator is constructed by integrating out the random effects, and therefore is comparable for MM with different distribution assumptions.
- Derived the non-normal asymptotic distribution of the proposed estimator, proved its unbiasedness and consistency, and proposed an approach to building confidence interval for the proposed statistics.
- In simulation and real data analyses, using the proposed estimator, we have shown that for modeling skewed data, MM with beta assumption has higher power than MM with normal assumption applied to log-transformed data.

