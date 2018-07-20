## Plotting and Visualization in Julia

Inroductory examples to plotting in Julia using varios libraries

| Launch Live Notebooks | View Static Notebooks |
|:----------------:|:----------------:|
|[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/mirestrepo/julia_plotting_tutorials/master)|[![nbviewer](https://img.shields.io/badge/jupyter_notebooks-nbviewer-orange.svg)](http://nbviewer.jupyter.org/github/mirestrepo/julia_plotting_tutorials/)|

### Last Used:
* July 20, 2018 - CEBI 0971 Summer@Brown: Biomedical Informatics and Data Science Skills for Biomedicine and Health Care 
* June 20, 2018 - BIOL6535 Preclinical Elective Summer 2018 at Brown University.

### Materials:

* Introductory Notebook: [Intro Slides](http://nbviewer.jupyter.org/github)
* PlotlyJS [Notebook Viewer](http://nbviewer.jupyter.org/github/mirestrepo/julia_plotting_tutorials/blob/master/plotlyjs_basics.ipynb)
* Plots [Notebook Viewer](http://nbviewer.jupyter.org/github/mirestrepo/julia_plotting_tutorials/blob/master/plots_basics.ipynb)
* Seaborn [Notebook Viewer](http://nbviewer.jupyter.org/github/mirestrepo/julia_plotting_tutorials/blob/master/seaborn.ipynb)
* Gadfly [Notebook Viewer](http://nbviewer.jupyter.org/github/mirestrepo/julia_plotting_tutorials/blob/master/gadfly_basics.ipynb)
* PyPlot [Notebook Viewer](http://nbviewer.jupyter.org/github/mirestrepo/julia_plotting_tutorials/blob/master/pyplot_basics.ipynb)
* (For instructors) To locally view the notebooks as slide you can install the notebook extension [RISE](https://github.com/damianavila/RISE)


### Files in this directory:

* Intro.ipynb -- Intro notebook
* Intro.ipynb -- Julia script matching the corresponding notebook
* plots_basics.ipynb - Jupyter notebook introducing Plots.jl
* plots_basics.jl - Julia script matching the corresponding notebook
* plotlyjs_basics.ipynb - Jupyter notebook introducing PlotlyJS.jl
* plotlyjs_basics.jl - Julia script matching the corresponding notebook
* seaborn_basics.ipynb - Jupyter notebook introducing Seaborn.jl
* seaborn_basics.jl - Julia script matching the corresponding notebook


### Dependencies:

See install_dependencies.jl if you need to troubleshoot.

```julia
# Packages to add - you may already have some of them
Pkg.add("PyPlot")
Pkg.add("Plots")
Pkg.add("StatPlots")
Pkg.add("PlotlyJS")
Pkg.add("Gadfly")
Pkg.add("Seaborn")
Pkg.add("Pandas")


# Test all used packages
using Plots
using StatPlots
using DataFrames, RDatasets
using PlotlyJS
using Gadfly

using Seaborn
using Pandas
using PyPlot
using PyCall
```
