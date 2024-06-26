This repository is part of the Supporting Information of the paper *Cyclic Steady State Simulation and Waveform Design for Dynamic/Programmable Catalysis*, by Carolina Colombo Tedesco, John R. Kitchin, and Carl D. Laird.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.11116036.svg)](https://doi.org/10.5281/zenodo.11116036)

It contains Jupyter Notebooks with code used to obtain the results and figures discussed in the work. 
The seventeen notebooks are numerated here as mentioned throughout the paper, and can be easily accessed and run in Google Colab through the button besides their names listed below, which are also on the top of the notebooks when accessed in the repo.
The notebooks include a cell (as seen in [this link](https://jckantor.github.io/ND-Pyomo-Cookbook/notebooks/01.02-Running-Pyomo-on-Google-Colab.html#installing-pyomo-and-solvers)) that quickly installs Munch, Pyomo and IPOPT (with the ma27 linear solver), which are needed for obtaining the results.

**Optimization**: This folder contains notebooks with results for the optimization of the waveforms used in the study. 

1-Square_wave_optimization.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Optimization/1-Square_wave_optimization.ipynb)\
2-Sine_wave_optimization.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Optimization/2-Sine_wave_optimization.ipynb)\
3-Triangle-Sawtooth_wave_optimization.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Optimization/3-Triangle-Sawtooth_wave_optimization.ipynb)\
4-Smooth_square_wave_optimization.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Optimization/4-Smooth_square_wave_optimization.ipynb)\
5-Single_Gaussian_pulse_optimization.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Optimization/5-Single_Gaussian_pulse_optimization.ipynb)\
6-Sine_wave_optimization_IPOPT.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Optimization/6-Sine_wave_optimization_IPOPT.ipynb)\
7-Single_Gaussian_pulse_optimization_IPOPT.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Optimization/7-Single_Gaussian_pulse_optimization_IPOPT.ipynb)

**Comparison_IVP_BVP_run_time**: The notebooks in this folder show a comparison between the sequential (IVP) and simultaneous (BVP) simulation approaches for dynamic catalytic systems.  Through the simulations, one can see both metholodgies provide similar results for all means. Additionally, Notebook #8 brings the comparisons of run time for the different methods.

8-Square_wave_BVP_IVP_Comparison+Run_time_Comparisons.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Comparison_IVP_BVP_run_time/8-Square_wave_BVP_IVP_Comparison%2BRun_time_Comparisons.ipynb) \
9-Sine_wave_BVP_IVP_Comparison.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Comparison_IVP_BVP_run_time/9-Sine_wave_BVP_IVP_Comparison.ipynb)\
10-Triangle-sawtooth_wave_BVP_IVP_Comparison.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Comparison_IVP_BVP_run_time/10-Triangle-sawtooth_wave_BVP_IVP_Comparison.ipynb)\
11-Smooth_square_wave_BVP_IVP_Comparison.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Comparison_IVP_BVP_run_time/11-Smooth_square_wave_BVP_IVP_Comparison.ipynb)

**Others**: This folder contains the other notebooks used in the work, including the ones for obtaining Extended Sabatier Volcano plots, uni and bidimensional optimization, and analyzing results with two Gaussian pulses as forcing signal.

12-Double_Gaussian_pulse_analysis.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Others/12-Double_Gaussian_pulse_analysis.ipynb)\
13-Extended_Sabatier_Volcano.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Others/13-Extended_Sabatier_Volcano.ipynb)\
14-One_variable_optimization_duty_cycle.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Others/14-One_variable_optimization_duty_cycle.ipynb)\
15-Two_variable_optimization_duty_cycle_offset.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Others/15-Two_variable_optimization_duty_cycle_offset.ipynb)\
16-Sensitivity_analysis_amplitude_offset.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Others/16-Sensitivity_analysis_amplitude_offset.ipynb)\
17-Number_finite_elements_study.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KitchinHUB/si-dynamic-catalysis-1/blob/master/Others/17-Number_finite_elements_study.ipynb)

Please, feel free to open an Issue or reach out to us in case you find any problems or have any doubt on how to use the notebooks and code provided in this repository. 
