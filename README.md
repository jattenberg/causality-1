# causality
Tools for causal analysis

Nonparametric contains a tool for non-parametrically estimating a causal distribution from an observational data set. You can supply an "admissable set" of variables for controlling, and the measure either the causal effect distribution of an effect given the cause, or the expected value of the effect given the cause.

This repository is in its early phases.  The run-time for the tests is long.  Many optimizations will be made over the course of the coming weeks, including
* Implement fast mutual information calculation, O( N log N )
* Speed up integrating out variables for controlling
* Take a user-supplied graph, and deduce the admissable set
* Various causal inference algorithms
* Front-door criterion method for determining causal effects