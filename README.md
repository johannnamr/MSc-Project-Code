# MSc-Project-Code
This repository contains the source code for my MSc Project on "Scalable Inference for Generative Models using Quasi-Monte Carlo". It is 
optimised for the use with [Google Colab](https://colab.research.google.com/) and mounts the Google drive to load required other notebooks located in the default folder for Colab notebooks. For local use, file paths have to be adjusted where indicated.

## Content of sub-folders:

### Illustrative examples
This folder contains a Python notebook generating all other illustrations for MC, QMC, and RQMC.

### Helper functions
This folder comprises two Python notebooks with the necessary functions to obtain results for optimisation/convergence ("utils.ipynb") and plots ("Plot_fcts.ipynb") 
for all analysed models. Therefore, both notebooks are loaded in all other notebooks listed below so that their file paths might need to be adjusted where indicated.

### Gaussian location model
In this folder, all results for the Gaussian location model can be found:<br>
- *Gaussian_check.ipynb*: test of kernel, generator and all partial derivatives<br>
- *Gaussian_optim.ipynb*: optimisation procedure using MC, QMC and RQMC<br>
- *Gaussian_conv.ipynb*: convergence of the squared MMD using MC, QMC and RQMC<br>
- *Gaussian_conv_W.ipynb*: convergence of Wasserstein distance using MC, QMC and RQMC<br>
- *Gaussian_conv_sink.ipynb*: convergence of Sinkhorn loss using MC, QMC and RQMC<br>

### Beta distribution
This folder provides the results for the beta distribution:<br>
- *beta_check.ipynb*: test of kernel, generator and all partial derivatives<br>
- *beta_conv.ipynb*: convergence of the squared MMD using MC, QMC and RQMC with options Halton, Sobol or lattice point sets <br>

### G-and-k distribution
This folder contains all results for the g-and-k distribution:<br>
- *gandk_check.ipynb*: test of kernel, generator and all partial derivatives<br>
- *gandk_optim.ipynb*: optimisation procedure using MC, QMC and RQMC<br>
- *gandk_conv.ipynb*: convergence of the squared MMD using MC, QMC and RQMC<br>

### Stochastic volatility model
This folder comprises the results for the stochastic volatility model. The results for this generative model were not used in the final report:<br>
- *sv_check.ipynb*: test of kernel, generator and all partial derivatives<br>
- *sv_optim.ipynb*: optimisation procedure using MC, QMC and RQMC<br>
