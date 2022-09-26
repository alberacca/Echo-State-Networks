# Echo State Networks - tutorial

Self-contained implementation of Echo State Networks (https://doi.org/10.1007/978-3-642-35289-8_36).

Hyperparameter optimization is carried out via Bayesian Optimization using Recycle Validation and K-fold cross Validation as described in Racca and Magri (https://doi.org/10.1016/j.neunet.2021.05.004).

Sparse matrix implementation provides fast training (tens of seconds) and low memory requirements.

As an example the networks are used to time-accurately predict the chaotic Lorenz system.


