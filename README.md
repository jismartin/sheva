# Explainable machine learning for project control

## Intended audience
This repository contains the code to replicate the experiments and results presented in the paper "Explainable machine learning for project management control"

Within project management, project control is a crucial phase aimed at achieving the project objectives according to plan in an integrated manner. The most popular and widespread method for project control is the earned value method with its various refinements. In particular, the triad method, based on Monte Carlo simulation and statistical learning, extends the earned value framework under project uncertainty. In our paper, we show that the Shapley value concept of cooperative game theory often used in explainable machine learning may improve the analysis and understanding of the project management control. 

In this repository, you will find a set of Jupyter Notebooks to replicate the Monte Carlo simulations, the machine learning model selection and fitting, and the calculation of the Shapley values of the project activities under different simulation scenarios and prediction models using [SHAP](https://github.com/slundberg/shap) package.

## Key results

The notebooks are:
* "sheva_monte_carlo_simulation.ipynb": the Monte Carlo simulation of the two scenarios proposes in the paper.
* "sheva_preliminary_analysis.ipynb": preliminary analysis of simulation results to verify
* "sheva_model_selection.ipynb": the selection of the machine learning models of the regression and classification problems, and the subsequent adjustment of hyper-parameters of the chosen models.
* "sheva_shapley_forward_analysis.ipynb": forward analysis focused on the general behavior of the models.
* "sheva_shapley_backward_analysis.ipynb": backward analysis focused on a particular study case.


In case you have render problems viewing some notebooks in GitHub, you can use Nbviewer:

## Licence
Copyright (c) 2022 José Ignacio Santos Martín

The name of this repository corresponds to the acronym for Shapley values for Earned VAlue management.
This reposiotory is distributed under the MIT License. See LICENSE file for details.
