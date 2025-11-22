# BTL-CGLMM
BTL-CGLMM (Bayesian Transfer Learning under Compositional Generalized Linear Mixed Model) is developed to address microbiome data, which are typically characterized by high dimensionality, small sample sizes, and compositional constraints. This package provides model function code and simulation experiment analysis code for both the BTL-CGLMM and Adaptive BTL-CGLMM, supporting both continuous and binary outcomes. The code files are organized into two separate folders, namely "Continuous" and "Binary", corresponding to the two outcome types respectively.

## Installation
Please download the packge to your computer and put it in a workpath that your Rstudio can access to it. This package includes two folders: Continuous and Binary. We introduce each of these as follows.

### Continuous
In this directory, you will find four main files:

The "regression-func.R" file contains the function code for compositional data generation, model definition, and model evaluation.

The "regression-sim.R" file contains the analysis code for our proposed method BTL-CGLMM and Adaptive BTL-CGLMM specifically designed for continuous response data.

The "Regression_BTL_CGLMM.stan" file and the "Regression_Adaptive_BTL_CGLMM.stan" file provide the Stan implementations for our proposed method BTL-CGLMM and Adaptive BTL-CGLMM.

### Binary
In this directory, you will find four main files:

The "classification-func.R" file contains the function code for compositional data generation, model definition, and model evaluation.

The "classification-sim.R" file contains the analysis code for our proposed method BTL-CGLMM and Adaptive BTL-CGLMM specifically designed for binary response data.

The "Classification_BTL_CGLMM.stan" file and the "Classification_Adaptive_BTL_CGLMM.stan" file provide the Stan implementations for our proposed method BTL-CGLMM and Adaptive BTL-CGLMM.

