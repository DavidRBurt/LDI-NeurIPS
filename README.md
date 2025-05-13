## Smooth Sailing: Lipschitz-Driven Uncertainty Quantification for Spatial Associations
This repository contains the reference implementation of the method described in "Smooth Sailing: Lipschitz-Driven Uncertainty Quantification for Spatial Associations".

### Installation
To install, run `pip install .` from the root directory; dependencies are included in the `setup.py` file and should be installed automatically. 

### Re-creating Simulation Experiments from the Paper
Navigate to the directory `Lipschitz-Driven-Inference/experiments/simulations`. To recreate experiments with the same settings as the paper, run `bash run.sh`. Results will be saved in `Lipschitz-Driven-Inference/experiments/simulations/results`.

### Re-creating Real Data Experiments from the Paper
Navigate to the directory `Lipschitz-Driven-Inference/experiments/real_data`. To recreate experiments with the same settings as the paper, run `bash run.sh`. Results will be saved in `Lipschitz-Driven-Inference/experiments/real_data/results`. 

### Data sources. 
Data is downloaded from the Dropbox link provided in the readme of `https://github.com/Earth-Intelligence-Lab/uncertainty-quantification`. Relevant citations for using the real data:

Lu, K., Bates, S., and Wang, S. (2024). Quantifying uncertainty in area and regression coefficient estimation from
remote sensing maps. arXiv preprint arXiv:2407.13659.

USFS (2023). USFS tree canopy cover v2021.4 (Conterminous United States and Southeastern Alaska).

Trabucco, A. (2019). Global aridity index and potential evapotranspiration (ET0) climate database v2. CGIAR Consortium for Spatial Information.

NASA Jet Propulsion Lab (2020). NASADEM merged DEM global 1 arc second v001 [data set]. NASA EOSDIS Land Processes DAAC.
