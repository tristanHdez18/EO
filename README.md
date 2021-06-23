# Equilibrium-Optimizer

# Description

“The Equilibrium Optimizer (EO) is inspired by control volume mass balance models used to estimate both dynamic and equilibrium states. In EO, each particle (solution) with its concentration (position) acts as a search agent. The search agents randomly update their concentration with respect to best-so-far solutions, namely equilibrium candidates, to finally reach the equilibrium state (optimal result). A well-defined “generation rate” term is proven to invigorate EO’s ability in exploration.
EO has been designed to solve single objective optimization problems. This algorithm has been implemented in a wide range of programming languages. You can download the source code at the end of this page."
*Seyedali Mirjalili.*

EO performance is validated against 58 mathematical functions, including unimodal, multimodal, hybrid, and composition functions, as well as 3 engineering reference problems, and its performance is compared to three classes of optimization methods; GA and PSO as the best-studied metaheuristics, GWO, GSA, and SSA as newly developed algorithms, and CMA-ES, SHADE, and LSHADE-SPACMA as high-performance optimizers. A full statistical analysis revealed that EO is capable of significantly outperforming PSO, GA, GWO, GSA, SSA, and CMA-ES, while its performance is statistically similar to SHADE and LSHADE-SPACMA.

![Image](https://user-images.githubusercontent.com/70921862/123126538-14977400-d40f-11eb-9d08-847afdfe596a.png)

We adding the next functions:

- [Booth Function](https://www.sfu.ca/~ssurjano/booth.html)
- [Bukin Function N. 6](https://www.sfu.ca/~ssurjano/bukin6.html)
- [Rastrigin Function](https://www.sfu.ca/~ssurjano/rastr.html)
- [Easom Function](https://www.sfu.ca/~ssurjano/easom.html)
- [Schaffer Function N. 4](https://www.sfu.ca/~ssurjano/schaffer4.html)
- [Styblinski-Tang Function](https://www.sfu.ca/~ssurjano/stybtang.html)


# Table of Contents


# Installation

You can get started right away running this in your terminal:
```
git clone https://github.com/tristanHdez18/EO.git
```
**Remember** you must add to path selected folders and subfolders

## Requirements

- MATLAB 2014 or above
- Statistics and Machine Learning Toolbox

# Usage

**`Run_no`** _= Number of independent runs_

**`Particles_no`** _= Number of particles_

**`Max_iteration`** _= Maximum number of iterations_

**`Function_name`** _= Select function_

## List of functions with function names added

- Booth Function _= F24_
- Bukin Function N. 6 _= F25_
- Rastrigin Function _= F26_ 
- Easom Function _= F27_
- Schaffer Function N. 4 _= F28_
- Styblinski-Tang Function _= F29_

# Contributing

# Credits

Mirjalili, S. M. (s. f.). EO. seyedalimirjalili. Recovered June 23, 2021, de https://seyedalimirjalili.com/eo
You can download the main paper here: https://doi.org/10.1016/j.knosys.2019.105190

# License

[Apache License 2.0](EO/LICENSE)
