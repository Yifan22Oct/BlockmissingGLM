# BlockmissingGLM
Variable selection for high dimensional generalized linear model with block-missing data

Authors: Yifan He, The Chinese University of Hong Kong
	 Xinyuan SONG, The Chinese University of Hong Kong

The code is written in R 

Prerequisites:
- R version 4.1.0

Simulation Study

File: Simulation/simulation.R

Requirement: 
libraries: 1. MASS; 2. glmnet; 3. Matrix; 4. softImpute; 5. robustbase

1. 'Overlapped' in the code is the method Stacked; 'Gaussian' is the proposed method and 'imputed' is the method softimpute in the paper.

2. The parameters in the code are set for setting I-IV in the paper. We also put an additional setting for testing the effects from dissymmetric distribution of covariates. For various block-missing types, we need change n1-n4 or blo4.in.y. 

3. n.raw is B in the paper. 