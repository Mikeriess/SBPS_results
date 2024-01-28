# Simulation demo
The following repository only contain the original code and results produced for the demonstration of the algorithms and overall approach presented in the paper: <i>A parametric simulation framework for the generation of event log data (Riess, 2024)</i>.

<b>PLEASE NOTE!<b> It is _not_ recommended to use the code provided in this repository, as an maintained version of the simulation framework (SynBPS) with various improvements can be found at <a href="https://github.com/mikeriess/SynBPS">, and installed using:

```
pip install SynBPS
```

The code in this repository is provided for transparency and reproducibility of the results presented in the paper, and is not maintained.

# Files
- simulation_experiment.ipynb
	- Example notebook with specification for the experiments in the paper
- analysis/experiments_analysis.ipynb
	- Notebook used for analysis of the results reported in the paper

# Requirements
- Python 3.8
- Numpy
- Pandas
- Pomegranate (version < 1.0, before torch rewrite)
- Pm4py
- Seaborn

# Instructions
- import the /simulation directory to your project
- make sure you have dependencies installed
- run the example notebook, and implement your model code in the for-loop
- store results of your experiments to "current_settings" dictionary
- analyze results via /analysis/simulation_analysis.ipynb