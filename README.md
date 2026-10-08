# LDIFE-HySU-Datasets
Synthetic hyperspectral datasets used in the LDIFE-HySU study.

Supplementary Datasets for LDIFE-HySU

This package contains the synthetic and real hyperspectral datasets used in the experiments of the manuscript:

“LDIFE-HySU: Leveraging dataset intrinsic features in evaluating HySU algorithms”

File descriptions
-----------------

1. S0.mat
   Baseline synthetic hyperspectral dataset.

2. S1.mat
   Synthetic hyperspectral dataset generated for evaluating the influence of spectral variability.

3. S2.mat
   Synthetic hyperspectral dataset generated for evaluating the influence of abundance smoothness.

4. S3.mat
   Synthetic hyperspectral dataset generated for evaluating the influence of endmember similarity.

5. GT_abundance_MMG-0.282.mat
   Ground-truth abundance maps corresponding to the synthetic dataset with an MMG value of 0.282.

6. GT_abundance_MMG-0.374.mat
   Ground-truth abundance maps corresponding to the synthetic dataset with an MMG value of 0.374.

7. GT_end4_SSP_50.06%.mat
   Ground-truth endmember spectra for the synthetic dataset with an SSP value of 50.06%.

8. GT_end4_SSP_76.52%.mat
   Ground-truth endmember spectra for the synthetic dataset with an SSP value of 76.52%.

9. jasperRidge_R198.mat
   Jasper Ridge hyperspectral dataset used for real-data evaluation.

10. Urban_R162_end6.mat
     Urban hyperspectral dataset with 162 spectral bands and six endmembers, used for real-data evaluation.

Notes
-----
- Urban and Jasper Ridge are publicly available benchmark datasets. The files provided here are the preprocessed versions used in this study. Please refer to the corresponding citations in the manuscript for the original data sources.
- All dataset files are provided in MATLAB .mat format.
- The synthetic datasets were generated for controlled evaluation of intrinsic dataset characteristics, including spectral variability, endmember similarity, and abundance smoothness.
- The real datasets were used to examine whether the observed trends are consistent with those obtained from the synthetic experiments.
- Please refer to the manuscript for the detailed dataset-generation procedure, metric definitions, preprocessing steps, and experimental settings.
- File names indicate the corresponding experimental condition or metric value where applicable.

Data availability
-----------------

These supplementary datasets are provided to support research reproducibility and academic use related to this study.

For questions regarding the datasets, please contact the corresponding author.
