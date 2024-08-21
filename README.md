# parallel-bayesopt-experiments

Repository to store notebooks related to MSc project, including analysing experiment results

## Notebooks Contents

### Core
notebooks/process_experiments_ax.ipynb - Code used to analyse the experiment results with comments
notebooks/skopt.ipynb - Code used to perform baseline experiments against the surrogate using the SkOpt implementation

### Intro plots
GP basics plot.ipynb - Code to create visualisations shown in the background section of the report. Functionality described in report, not cleaned up
notebooks/fantasy_points.ipynb - Code to create visualisations shown in the background section of the report. Fantasy points

### Very messy, kept for personal reference
notebooks/ax_test.ipynb - Rough code investigating how to get predictions from the Ax client
notebooks/batch_bo.ipynb - Rough code investigating the idea of using BO to optimise BO
notebooks/compare_sequential_parallel.ipynb - Earlier practice experiments looking at hypervolume trace, abandoned due to poor model fit
notebooks/evaluate_runs_from_raw.ipynb - Earlier practice experiments looking at hypervolume trace, abandoned due to poor model fit
notebooks/kernels.ipynb - Experimenting with how to change the BoTorch kernels
notebooks/levelset.ipynb - Messing around with the level set idea with a 2d synthetic problem. Pretty contour plots.
notebooks/read_surrogate.ipynb - Early attempts at experiments on the surrogate
notebooks/read_surrogate2.ipynb - Further early attempts at experiments on the surrogate
notebooks/simulation_runs.ipynb - Attempts to find the optimal number of simulation runs. Abandonded due to poor model fit.
notebooks/single_vs_multi.ipynb - Earlier practice experiments looking at comparing the hypervolume of single vs multi objective optimisation, looking at how to analyse the data from the single objective with a multi-objective setup for comparison, abandoned due to poor model fit


## Installing requirements
 
 windows command:

 ```
python -m venv venv
venv\Scripts\activate.bat
pip install -r requirements.txt
```

or in powershell:
 ```
python -m venv venv
venv\Scripts\activate.ps1
pip install -r requirements.txt
```
