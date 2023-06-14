# Clustering Noisy Rings

The project in this repository is inspired by a real subproblem from LHCb experiment conducted at CERN, however this is a much simple version. RICH (Ring Imaging CHerenkov) detectors try to detect round/elliptic patterns which are caused by the impact of Cherenkov radiation: cones of photons emitted by particles resulting from hadrons collisions when such particles travel through a special gas at a speed higher than the speed of light in that gas medium. 

In practice, this solution is able to find circunferences in a given cloud of points using Fuzzy c-Means clustering algorithm. This solution icludes an instance generator, a circunference detector, a visualizer of the data using [matplotlib](https://matplotlib.org/) and a results analyzer.

## Usage

Make sure you have [matplotlib](https://matplotlib.org/) installed. You just need to run each cell of the computational notebook from top to bottom using Jupyter Notebook.
