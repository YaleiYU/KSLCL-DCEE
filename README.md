# k-Step Lookahead Active Concurrent Learning-Based Dual Control (KSLCL-DCEE)

## Overview
This repository provides MATLAB implementations of the **KSLCL-DCEE (k-Step Lookahead Active Concurrent Learning-Based Dual Control of Exploration and Exploitation)** algorithm.

The code supports:
- Numerical simulations for validating the proposed method  
- Photovoltaic (PV) system simulations using Simulink  

It accompanies the paper published in *IEEE Transactions on Cybernetics (2026)*.

---

## Repository Structure

### 🔹 Numerical Simulations
- Required function implementations for the KSLCL-DCEE algorithm 
- `Plot_results` scripts for visualization  
- Four main scripts corresponding to different case studies  

### 🔹 Photovoltaic Simulations
- Simulink model of the PV system  
- Main execution script  
- Result plotting scripts  

> ⚠️ Note: Due to file size limitations, PV simulation data files are not included. Please contact the author to obtain them.

---

## Requirements

- **MATLAB**: R2024b or later  
- **Toolboxes**:
  - Simulink  
  - Simscape  
  - Simscape Electrical  
  - Signal Processing Toolbox  

---

## Usage

Run the provided scripts in MATLAB to reproduce the results:

```matlab
% Example:
run('main_script_name.m')
```

- Numerical simulation results are generated from scripts in the **Numerical Simulations** folder  
- PV simulation results are generated from the **Photovoltaic Simulations** folder (data required)

---


## Results

### Numerical Simulations
Representative outputs:
- Gradient evolution  
- Parameter estimation  
- System output  

![lookahead](Figures/Numerical%20Sim/grad_lksdcee.png)

![lookahead](Figures/Numerical%20Sim/theta_lksdcee.png)

![lookahead](Figures/Numerical%20Sim/y_lksdcee.png)

### Photovoltaic Simulations
Representative outputs:
<!-- - Power generation   -->
- Energy loss  

<!-- ![lookahead](Figures/PV%20Sim/power.png) -->

![lookahead](Figures/PV%20Sim/energy_loss.png)

---

## License
This project is licensed under the **MIT License**. See the LICENSE file for details.

---

## Acknowledgments
- This work was supported by the UK Engineering and Physical Sciences Research Council (EPSRC)  
  - Grant: *EP/T005734/1*  
  - Fellowship: *Goal-Oriented Control Systems: Disturbance, Uncertainty and Constraints*  
- Thanks to the research community and open-source contributors for their support and insights.

---

## Contact
📧 y.yu2@lboro.ac.uk  

---

## Citation
If you use this repository in your research, please cite:

```bibtex
@ARTICLE{11397078,
  author={Yu, Yalei and Jiang, Jingjing and Chen, Wen-Hua and Zuo, Yuefei},
  journal={IEEE Transactions on Cybernetics}, 
  title={k-Step Look-Ahead Active Concurrent Learning-Based Dual Control of Exploration and Exploitation for Auto-Optimization}, 
  year={2026},
  pages={1-14},
  doi={10.1109/TCYB.2026.3660400}
}
```


