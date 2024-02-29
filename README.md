This repository is part of the Supporting Information of the paper *Cyclic steady state simulation and waveform design for Dynamic/Programmable Catalysis*, by Carolina Colombo Tedesco, John R. Kitchin, and Carl D. Laird.
It contains Jupyter Notebooks with code used to obtain the results and figures discussed in the work. 
The seventeen notebooks are numerated as they are mentioned throughout the paper, and can be easily accessed and run in Google Colab through the button besides the name of the notebooks listed below for each folder in this repository (the buttons are also on top of the notebooks when accessed in the repo).
All notebooks include a cell that quickly installs Munch, Pyomo and IPOPT (with the ma27 linear solver), which are needed for running most notebooks.

**Optimization**: This folder contains notebooks with results for the optimization, either gradient-free and/or gradient-based, of the waveforms used in the study. 

1-Square_wave_optimization.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Optimization/1-Square_wave_optimization.ipynb)\
2-Sine_wave_optimization.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Optimization/2-Sine_wave_optimization.ipynb)\
3-Triangle-Sawtooth_wave_optimization.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Optimization/3-Triangle-Sawtooth_wave_optimization.ipynb)\
4-Smooth_square_wave_optimization.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Optimization/4-Smooth_square_wave_optimization.ipynb)\
5-Single_Gaussian_pulse_optimization.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Optimization/5-Single_Gaussian_pulse_optimization.ipynb)\
6-Sine_wave_optimization_IPOPT.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Optimization/6-Sine_wave_optimization_IPOPT.ipynb)\
7-Single_Gaussian_pulse_optimization_IPOPT.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Optimization/7-Single_Gaussian_pulse_optimization_IPOPT.ipynb)

**Comparison_IVP_BVP_run_time**: The notebooks in this folder show a comparison between the sequential (IVP) and simultaneous (BVP) simulations approaches for dynamic catalytic systems. 
Through the results obtain, one can see both metholodgies provide similar results for all means. Additionally, Notebook #8 brings a comparison of run time for the methods and bar plots.

8-Square_wave_BVP_IVP_Comparison+Run_time_Comparisons.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Comparison_IVP_BVP_run_time/8-Square_wave_BVP_IVP_Comparison%2BRun_time_Comparisons.ipynb) \
9-Sine_wave_BVP_IVP_Comparison.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Comparison_IVP_BVP_run_time/9-Sine_wave_BVP_IVP_Comparison.ipynb)\
10-Triangle-sawtooth_wave_BVP_IVP_Comparison.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Comparison_IVP_BVP_run_time/10-Triangle-sawtooth_wave_BVP_IVP_Comparison.ipynb)\
11-Smooth_square_wave_BVP_IVP_Comparison.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Comparison_IVP_BVP_run_time/11-Smooth_square_wave_BVP_IVP_Comparison.ipynb)

**Others**: Contains the other notebooks used in the work, including the ones for obtaining Extended Sabatier Volcanos and analyzing results with double Gaussian pulses as forcing signal.

12-Double_Gaussian_pulse_analysis.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Others/12-Double_Gaussian_pulse_analysis.ipynb)\
13-Extended_Sabatier_Volcano.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Others/13-Extended_Sabatier_Volcano.ipynb)\
14-One_variable_optimization_duty_cycle.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Others/14-One_variable_optimization_duty_cycle.ipynb)\
15-Two_variable_optimization_duty_cycle_offset.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Others/15-Two_variable_optimization_duty_cycle_offset.ipynb)\
16-Sensitivity_analysis_amplitude_offset.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Others/16-Sensitivity_analysis_amplitude_offset.ipynb)\
17-Number_finite_elements_study.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Others/17-Number_finite_elements_study.ipynb)

Please, feel free to open an Issue in case you find any problem or have any doubt on how to use the notebooks and code provided here. 
