# Echo State Networks - tutorial

Self-contained implementation of Echo State Networks.

Hyperparameter optimization is carried out via Bayesian Optimization using Recycle Validation and K-fold cross Validation as described in Racca and Magri (https://doi.org/10.1016/j.neunet.2021.05.004).

Sparse matrix implementation provides fast training (tens of seconds) and low memory requirements.

As an example the networks are used to time-accurately predict the chaotic Lorenz system (https://doi.org/10.1175/1520-0469(1963)020<0130:DNF>2.0.CO;2).


