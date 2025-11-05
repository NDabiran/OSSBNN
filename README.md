# 🔒 The code and data will be made publicly available after the journal review process is complete.

# OPTIMAL SPARSITY STRUCTURED BAYESIAN NEURAL NETWORK 

## Overview
This repository contains the implementation of OPTIMAL SPARSITY STRUCTURED BAYESIAN NEURAL NETWORK, which uses Gaussian mixture model (GMM) approximations to provide a descriptive representation of the complex non-Gaussian parameter posteriors. The framework is designed to improve uncertainty quantification and alleviate overfitting within the Bayesian neural network.


<table width="100%">
  <tr>
    <td width="33%" align="center"><img src="https://github.com/user-attachments/assets/2d85523b-6ab2-4fef-9fcf-a472dd902f89" width="100%"></td>
    <td width="33%" align="center"><img src="https://github.com/user-attachments/assets/270c6741-838b-4a1e-98f3-4c90fd12bc63" width="100%"></td>
    <td width="33%" align="center"><img src="https://github.com/user-attachments/assets/ca35c096-622e-4550-bb5d-b468322e3ecf" width="100%"></td>
  </tr>
</table>


![Image](https://github.com/user-attachments/assets/8a933d77-d066-4026-be67-06be5205d811)

The code used to generate the results presented in the paper [OPTIMAL SPARSITY STRUCTURE FOR BAYESIAN NEURAL NETWORK] can be found in the `/oss-bnn` directory.

### Requirements Libraries:  
- **matplotlib** version: `3.9.2`  
- **numpy** version: `1.26.4`  
- **pandas** version: `2.2.2`  
- **scipy** version: `1.13.1`  
- **tensorflow** version: `2.16.2`  
- **tensorflow-probability** version: `0.24.0`  
- **keras** version: `3.6.0`

## Installation
Clone this repository:  
`git clone git@github.com:NDabiran/OSS-BNN.git`  

This creates a virtual environment and installs requirement libraries:
`chmod +x setup_env.sh`
`./setup_env.sh`

The codes are tested on Ubuntu 22.04, and various machines in the Digital Research Alliance of Canada consortium.  

## Repository Structure
```
OSS-BNN/
├── oss_bnn/                  # Contains Bayesian inference (BNN) and OSS-BNN framework
├── hbi/                      # Contains Hierarchical Bayesian inference (HBNN)
├── multistart_sensitivity/   # Contains sensitivity analysis on multi-start optimization and hyperparameter tuning
```

The codes can be run in VS Code, Jupyter Notebooks, Google Colab, etc. 
Plots will be displayed inline, and figures and data will be saved in the appropriate subdirectory.

## Citation
If you use this code for research, please cite:
```
@article{dabiran2023sparse,
  title={Sparse Bayesian neural networks for regression: Tackling overfitting and computational challenges in uncertainty quantification},
  author={Dabiran, Nastaran and Robinson, Brandon and Sandhu, Rimple and Khalil, Mohammad and Poirel, Dominique and Sarkar, Abhijit},
  journal={arXiv preprint arXiv:2310.15614},
  year={2023}
}
```

## License
GNU GENERAL PUBLIC LICENSE


