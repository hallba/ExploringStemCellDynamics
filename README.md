# Exploring Stem Cell Dynamics in F# and Python

[F#](FSharpSimulator.ipynb) [Python](PythonSimulator.ipynb)

These paired jupyter notebooks are intended as an introduction to the methods used to simulate models of stem cell differentiation and analyse experimental data.

Both notebooks perform the same tasks; they describe simulators of histone dilution and lineage tracing experiments, and use those simulators to parameterise models. 
In each case the code can be extended to do different things- changing assumptions in the model for example, or using different experimental datasets for comparison.

These notebooks have been written in both F# and Python to highlight different features of the languages, whilst helping people move between the languages. 
In each case the notebooks use available libraries wherever possible to minimise repetition of work. These are installed automatically in the F# code, 
whilst users of the python notebook should install the appropriate modules through pip or conda. There is an additional appendix to the main notebook 
("OptimisingFSharp.ipynb") that discusses a specific issue (speed of available library functions, and how to write efficient code) found in writing the 
notebook in detail.

Each notebook should take between 5 and 10 minutes to run, and all code should work without modification (after installation of the appropriate python libraries).

This work reimplements functions and uses data presented in the upcoming manuscript by Piedrafita et al. This readme and datasets will be updated once the manuscript is 
publicly available.

[![Azure Notebooks](https://notebooks.azure.com/launch.png)](https://notebooks.azure.com/import/gh/hallba/ExploringStemCellDynamics)
